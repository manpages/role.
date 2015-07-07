# Balancer

Intuitively, a system is balanced if there are no outstandingly superior
options. If there is a small amount of outstanding options, system will degrade
into all the players picking those over inferior options.

Rich gameplay should be ensured by having modules where different interaction
classes being relevant together with options within one interaction class being
feasible.

Players tend to prefer playing proactively balanced systems versus retroactively
balanced systems. Ad-hock solutions for retroactive balancing are known but not
adopted en mass. For a reference, see tiers for PC-classes and relevant 
house-rules in D&D 3.5E.

# Constructor

Having inherently balanced system allows us to let the players define options
of their characters in terms of

 + Basic interactions
 + Interaction augmentations
 + Sources and entities

To ensure lack of mundane minimaxing, lack of options shouldn't affect power
level of constructed options. Comepletely informally — player characters
shouldn't be one trick ponies, they should at least be *some* trick ponies.

Some setting-dependant *basic interactions* are constructed and balanced by DM
(see “Lesser balance theorem” below). 

Global, major and minor entities that describe setting are written down by DM.
This step may happen progressively, to fit the needs of the group. These keywords
will be used by players to add flavor and mechanics to the interactions they are
constructing.

A set of rules for selecting entities for character description is defined by DM
along with rules for basic interaction access. We call a group of entities together
with quantifiable semantics and flavor *a source*.

# Model of a tabletop RPG

Virtually any tabletop RPG can be dissected into Wealth, equipment and
possessions; Social interactions; Traveling; Dungeon-crawling; and Combat. We
will call those *aspects of a game* and assign shorter names:

 + Combat
 + Crawl
 + Travel
 + Social
 + Wealth

We model a tabletop RPG as follows: a party (or degenerate party of one — a character)
with fixed, average, attributes is crawling dungeons where they face vanilla
N/N creatures (where N is normally distributed in some range) and tactically
fight those using some options, between combat they keep crawling dungeons,
resting greedily and, upon completion of their quest (finding a featureless
white cube in the dungeon) travel to safety to increase Social standings and
Wealth, and get to know some facts.

Here are some pseudo-types we might consider using:

```
Social = (Standings, Goal) 
  where
    Goal      = (SecrecyLevel, String)
    Standings = [(Faction, Score)]

Travel = (Distance, MaxSizeDistribution)
  where MaxSizeDistribution = Dist (Size, Penalty)

Crawling = (Hideable, ObstaclePerRoundProb, TerrainDistribution)
  where
    Hideable             = Int
    ObstaclePerRoundProb = Probability
    TerrainDistribution  = Dist (Terrain, Penalty)

-- Penalty here — how long of a distance a character will have to cover to ignore this
-- terrain or size limitation of a traveling pathing.

Combat = (Field, Enemies)
  where
    Field   = [(Terrain, [Token])]
    Enemies = [([Resource], [Flag], Coord)]

C = [([Resource], [Flag], Coord)]

Action = C -> [C] -> Dist [C]

Wealth = Int
```

## Large balance theorem

Formal balance criteria — for each party P of characters there should exist a
party Q having the same ability total and options selected, such that 

1. For every character in P no character in Q shares more than half of the
options within a certain interaction class; 

2. Probability of Q beating P is no less than 50%.

Informally, that means, that for every party P there exists party Q that at
least soft-counters P.

Please notice that this balance criteria is applied to all the relevant aspects
of the setting.  If your setting is pre-Qui-Gon-Jin Tatooine, you balance
against trading, pod-racing and combat against sand people.

This formal criteria can be checked in a proramming language capable of lazy
evaluation strategy by simply building infinite tree of all possible decisions,
then folding it over weighted outcomes of *all* (approach akin to 
[tracing simulation function from Numeric.Probability.Simulation](https://hackage.haskell.org/package/probability-0.2.4.1/docs/src/Numeric-Probability-Simulation.html#~..))
or *some* (approach akin to 
[randomized transition simulation from Numeric.Probability.Simulation](https://hackage.haskell.org/package/probability-0.2.4.1/docs/src/Numeric-Probability-Simulation.html#~.))
possible decisions on a given depth, after which picking a random path in the
tree and repeating adding weighted effects of all or some of the decisions.

Please notice, that ~.-program-schema is merely a check, while ~..-program-schema
is a proof of balance.

The only way to get a proof that the system is balanced within our setting
model (remember, we have to know whether or not we're balancing pod racing!) is
to analytically prove that options are feasible.

Analytical approach is to pick an option within an interaction class and call
it "basic interaction".  Then, based on how it diminishes resources. The way it
diminishes resources is described by tree of probabilities that is regular and
analytically deductible with just xBeatsY function, which is 
``xBeatsY x y = 1 - 1/2 * (kInN 0 (abs $ x - y))``

Proof of correctness of this formula:
If x and y are of the same size, the probability is 1/2 (symmetry);
Else, say x > y, then x = y + p; p > 0.
Which means that if pool x gets 0 tails in p (kInN 0 p), it still has 1/2
chance of winning.
It yields formula
``xBeatsY x y = 1 - (1/2 * (kInN 0 p))`` which, when we reverse
substitution, yields aforementioned forumla. 

A value, or power of an option is derived by comparing qualities of tree
for this option to the tree of the basic interaction.

A way to analytically work with options within interaction classes was
proposed by Ilya Deift.

It should be noted though that analytical balancing doesn't tend to be
applicable to diverse systems due to complexity explosion, hence we'll stick
to illustrative/probabilistic balancing and instead of proving Large balance
theorem for our systems, we'll concentrate on justifying it by showing that
with high enough probability it is true.

## Lesser balance theorem

Survivability is invariant over fixed basic interactions respecting equipment.

Informally speaking, no matter which one basic interaction per interaction
class a character uses, its life expectancy in [Gygax's Meatgrinder](http://www.goodreads.com/book/show/235762.Tomb_of_Horrors)
is constant. Also, each piece of basic equipment prolongs life expectancy
of character in Tomb of Horrors by a constant.

By proving or justifying this theorem we have a proof or justification of
balance amongst basic interactions and basic equipment. Now we can measure
interaction augmentations and improved equipment.

## Gameplay diversity theorem

Options form a system.

Informally speaking, by combining options within encounters one may achieve
more than by using each option separately. Options-as-whole are greater than
sum of options.

## Source balance theorem

For every option Os in every S there exists option of the same level Ot in some
source T such that Ot has at least the same power as Os.

# Let's play!

If you're interested in such a system, contact me.
Contact details — http://memorici.de/me.html
