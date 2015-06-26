# Generic Epic Fantasy Constructor Playtest

## Game mechanics

There is a number of aspects in the game and points attached to each aspect
with point maximum equal to the score in its aspect. As a character gets
another point in aspect, they get some options in this aspect.

An exception is Combat, which uses two special aspects in the game — *phy*
(physical development) and *men* (mental development). Those two special
aspects don't define options, instead governing fundamental interactions with
the world. Combat grants combat options (see “Basic Interactions. Combat.”
below.

### Dice pools and bonuses

There are two types of dice rolls in Role. — checks and clashes. Consult
“rules.org” for details.


| Level  | ·  | ·· | ··· | ···· | ····· | ······ |
|--------|---:|---:|----:|-----:|------:|-------:|
| Power  | 1  | 1½ | 2   | 4    | 4½    | 5      |

Notice the spike of option power between third and fourth level of aspect!

Some abilities grant bonuses, bonuses with the same name (type) don't stack.
Types of bonuses are

 + Luck
 + Armor
 + Weapon
 + Equipment
 + Tactical
 + Engagement
 + Precision
 + Competence
 + Crawling
 + Travel
 + Fatigue
 + Exhaustion
 + Magic

To calculate total of a bonus, take largest bonus of a name, take largest
(by absolute value) penalty of a name and add them together.

### Abilities and effects

Options provide abilities — some of those are triggered, some of those are
activated, some have costs, 
Some options outright yield continuous effects. Consult relevant rules of
“Magic: the Gathering” to get intuition about how abilities and effects work.

### Power

Pools scale linearly; option of power scales under this progression:

## Wheel of aspects

![Wheel of aspects](./wheel.png)

There are five aspects to a fantasy game —

 * combat (tactical engagements)
 * crawling (getting out of the trouble, doing things between combat in dangerous places)
 * travel (getting from point A to point B effectively)
 * wealth (being able to effectively function within economy system)
 * socialization (fitting into the community, gethering infomration)

As you generate a character, you can pick one primary aspect and two secondary
ones.  Wealth aspect as crafting, artificing and enchanting is closed for
player characters in Generic Epic Fantasy Constructor Playtest. Instead, there is
an adventuring-oriented aspect.

Primary aspects are more developed than secondary aspects: Nth level of primary aspect
grants access to options of Nth level of this aspect, whilst Nth level of secondary
aspect grants access to options of N-1st level of options of this aspect.

As you get access to a level N of options of an aspect, you may pick one option of each
level of this aspect, up to N (including).

You can also choose to have all five aspects as your secondary aspects, see “Mage”.

### Basic interactions

Every aspect of the game has at least one basic interaction that is used as a
baseline for balancing player-constructed abilities. All the basic interactions
within an aspect are considered to be a priori balanced against each other.

#### Combat (health | physical development, mental development)

   + **Move**: Anchored — as a move action, move up to your *(tactical)* speed.
     *(Anchored — this part of the option doesn't scale using the constructor;
     move action — each round consists of a free action, a move action and a
     standard action, you may replace latter actions with former ones)* As you
     use **move** option, choose one — 

      + Move *aggressively*, engaging opponent that tries to interfere with your
        move. If you do, you may attempt to gain initiative; 
      
      + Move *defensively*, escaping or outrunning your opponents. You gain
        defensive until end of the round;

      + *Flee*, straight up running towards your destination, ignoring everything
        and everyone that doesn't pose lethal threat.

      + *Surprise* Move up to half your move speed without
        drawing attention to it. Reduce this movement by half for every opponent beyond
        first.
        Anchored — Use this option only if you are in full cover against every opponent
        and you end the round in full cover against every opponent.

   + **Attack**: Attack for 1 *(To attack for X, clash phy vs phy, honoring
     equipment and tactical bonuses and penalties. If you win, deal X damage to
     target)*

   + **Charge**: When not engaged in melee combat and having a straight
     unencumbered line of terrain between you and target character, you may attack for 1
     combined with moving up to twice your *(tactical)* spped straight to the
     target. If you do, you take 1 dp *engagement* penalty on all defensive clashes 
     until the end of the round and gain except defensive clashes that
     interrupt movement. You gain initiative until end of the round.

   + **Grapple**: Clash with your *phy*, if you win, you and your opponent
     become grappled *(while grappled, you can't use options and take 1 dp
     *engagement* penalty to defesive clashes. You may choose to stop being
     grappled if you do, your opponent gets a chance to grapple you in
     response)*. Use this option only if you have at least as many free limbs
     as your opponent.

   + **Bull rush**: You may try to intercept target opponent. If you win the
     phy clash, your opponent's movement is interrupted. If you moved this turn,
     opponent gets prone until end of round *(opponent can only crawl at half the
     speed or spend or spend move action to stand up, providing an opening, she
     gets 1 dp *engagement* penalty to defensive clashes against melee attacks
     and 1 dp *engagement* bonus to defensive clashes against ranged attacks).

   + **Disarm**: While having *initiative*, you may choose to clash *phy* vs *phy*.
     If you win, your opponent is disarmed.
      
   + **Stance**: while engaged in combat, at the beginning of the round you may
     choose one —

      + Gain initiative against target opponent engaged into melee with you:
        you gain *initiative*. If opponent chosen to gain initiative as well, clash
        *phy* vs *phy*, the winner gains initiative *(get 1 *stance* dp bonus on your
        attacks against target opponent in melee and provide an opening with your attacks)*.

      + Stay on the defense: you gain *defensive*.

      + Parry the blows of target opponent: you gain *parrying*. You can't
        choose attack. First unsuccessful melee attack this round against you
        provide opening. You get 1 dp *stance* penalty on attacks this round and 1
        dp *stance* bonus on defensive clashes against target opponent.

      + Snipe: spend a move action to gain 1 dp *stance* bonus to your ranged
        attack clashes against target opponent until end of round.

      + Just shoot the dam thing: you gain *defensive*.

      + Rapid reload: gain 2 dp *precision* penalty to your ranged attacks. You reload
        one category faster. *(you can move after you shot shortbow-class weapons;
        longbow-class weapons reload as a part of stanadrd action you fired it in,
        instead of taking additional move action; 
        light-crossbow-class weapons reaload as move action; heavy-crossbow-class
        weapons reaload as a standard action)*.

      + Surprise: Use a standard action and opponents gain *surprised* until end of
        round, opponents who readied a relevant action to your action clash *men*
        or *phy* against your *phy*, if they win, their readied action is
        triggered and they lose *surprised*.
        Anchored — Use this option only if you are in full cover against every opponent
        and you end the round in full cover against every opponent.

     
##### Magical Combat

Spend 1 mental point: restore 1 hit point or structure point of target character.
     
#### Crawling (resource restoration | elusiveness, consequences of harm)

   + **Run, Tordek, run!**: Pay 1 crawling point: Both speeds of a target character 
     who forfieted an encounter becomes equal to respecting speeds of the character
     with the highest respecting speeds among characters who participated in this
     encounter for the amount of minutes equal to your crawling.
 
   + **Restoration**: Pay 1 crawling point: Grant 1 *crawling* temorary hit point to target
     character over a short rest *(To short rest, spend one hour
     not engaged in a combat)*. No retry *(the same character can't try this
     several times before taking at least a short rest)*

   + **Crawljutsu**: Pay 1 crawling point: Gain a *competence* emblem with "You
     gain bonus equal to your *crawling* to your perception and stealth dp".
     *(Emblem — continuous effect that lasts until the beginning of next full
     rest, some emblems have triggers and they disappear when triggered)*. Linked.
     *(Linked — costs, drawbacks and effects scale together)*.

   + **Endure distractions**: Make a DC 1 *crawling + 1dp* check to continue an interrupted
     short rest. No retry.

   + **Mental map**: Make a DC 1 *crawling + 1dp* check to ignore traveling-based confusion
     while crawling.

   + **Tomb raider's craft**: Make a DC 1 *crawling* check to accomplish one of the following —

      + detect or set up item level 1 traps or secret doors; 
      
      + apply level 1 poison; 

      + use grappling hook or a rope as a standard to perform a simple *(under
        circumstances)* action.

      + grant 1 *crawling* temporary structural point to an equipment or
        crawling gear. At all times you can spend a short rest to restore 1
        structural point of an equipment or crawling gear.

   + **Tomb raider's knowledge**: Make a DC 1 *crawling* check to determine a minor fact about
     a construction, a piece of architecture, a dungeon room, a treasure, an equipment, a gear,
     a poison, tactical properties of terrain, etc. At all times you know how to set up camps and
     take care of equipment and gear.

##### Magical Crawling

Spend 1 mental point: target square becomes difficult terrain of chosen type.

#### Travel (distance | pathfinding, speed)
 
   + **Quick march**: Pay 1 travel point: for the next travel, each character
     in the party gets +1 mile/hour *traveling* strategic speed bonus *(see
     “Strategic movement”)*

   + **Extend stamina**: Pay 1 travel point: get an extra hour of full-speed
     traveling

   + **Second wind**: Pay 1 travel point: for an hour, ignore exhaustion or
     fatigue caused by traveling (exhaustion and fatigue should be paid
     separately)
   
   + **Travel safe**: Make a DC 1 *travel + 1dp* check to predict
     well-known dangerous places along your path

   + **Intuit general direction**: Make a DC 1 *travel + 1dp* check to
     intuit where is northen hemisphere (or hemiplane, if you're in Discworld)

   + **Traveler's knowledge**: Make a DC 1 *travel* check to determine a minor
     fact about land, plane, location, nation or inhabitants of a location, etc.; At
     all times *(“at all times” means that even a mage who has this option has
     the following effect)* you know how to use and take care of traveling tools
     and mounts.

   + **Traveler's craft**: Make a DC 1 *travel* check to grant 1 *traveling*
     temporary hit point to a mount or 1 *traveling* temorary structural point to
     a vehicle. No retry *(the same character can't try this several times before
     taking at least a short rest)*.; At all times you can spend a short rest to
     grant 1 *traveling* temorary hit point to a mount or 1 *traveling* temorary
     structural point to a vehicle; At all times you can craft level 1 traveling
     tools and level 1 vehicles.

##### Magical Travel

Spend 1 mental point: Summon a level-1 mount for one travel.
   
#### Wealth (active | wealth category, possessions)

*Wealth is the shape it exists for NPC artificers and enchanters is not
available to player characters. It governs management, resource allocation,
crafts, enchanting, etc.*

Wealth points don't restore after full rest. You can't improve your wealth
score by spending experience points except for experience points spent during
character creation.

  + **Shut up and take my money**: Pay 1 wealth point: If you lost in an
    encounter, if agenda of opponents permits bribe, flee successfully.

  + **Butter up**: Pay 1 wealth point: Increase standings with target faction
    by 1 category over a week.

  + **Would you kindly**: Pay 1 wealth point: Suggest a minor decision to at
    least a loyal faction.

  + **Gather more information**: Make a DC 1 *wealth + 1dp* check to get +1
    *competence* replacement bonus on your next gather information check. If you
    fail, get -1 *competence* replacement penalty on it. You pay according amount
    of WU.

  + **Consult maps**: Make a DC 1 *wealth + 1dp* check to get +1 *competence*
    replacement on your next travel planning check. If you fail, get -1
    *competence* replacement penalty on it. You pay according amount of WU.

  + **Aristocratic memory**: Make a DC 1 *wealth* check to get +1 *competence*
    replacement bonus on your next mental map check. If you fail, get -1
    *competence* replacement penalty on it.

  + **Wait!**: Make a DC 1 *wealth* check to get unfriendly opponents agenda of
    which permits bribe to talk before the combat starts or continues beyond
    surprise round.

##### Magical Wealth

Spend 1 mental point: Target character gets *luck* emblem with "next time you
would receive wealth units, you get twice that amount instead".
   
#### Socialization (identity | gather information, standings)

   + **Friendly**: Pay 1 socialization point: move one relation category of a
     non-hostile character during a social interaction. This effect is of type
     *charm*.

   + **Sense and conceal motive**: Pay 1 socialization point: get to know or
     hide a minor fact during conversation. This effect is of type *charm*.
     *(Please note that you can try to lie or try to understand the motives of
     characters you encounter outside of mechanical aspects, however activating
     ability granted by this option you know for sure that a certain fact is
     well-hidden or some hidden fact is revealed)*

   + **Inspire**: Pay 1 socialization point: inspire someone to do something,
     make them believe in themselves, calm someone down or reduce an effect of
     insanity.

   + **Gather information**: Make a DC 1 *socialization + 1dp* check to gather
     a piece of minor information in a densely inhabited place.

   + **Suggest**: Clash *socialization* vs (*men* or *socialization*) to suggest
     a minor action to someone.

   + **Honey**: Make a DC 1 *socialization* check to find out how to approach the
     target.

   + **Impromptu**: Make a DC 1 *socialization* check to quickly come up with an
     excuse or plausible explanation of minor fact. *(Mechanically that means that
     DM will give you, the player, time to come up with a good excuse for a certain
     question about minor fact, such as party breaking into a house, hiding, pick
     pocketing, etc)*

##### Magical Socialization

Spend 1 mental point: Target character gets *luck* emblem with "next time you
would discover minor fact, discover lesser fact instead". *(Facts are minor,
lesser, concealed, major, secret)*

### Combat

Combat happens on a D&D-esque tactical battlefield. Each player has four tokens —
character token and grey, red and blue character tokens. Grey denotes flee move,
red denotes aggressive move, blue denotes defensive move.

Standard D&D intuitions about difficult terrain and cover apply.

Requests of actions are told to DM and all resolved together in round-like time
frames.

Physical points denote ability to perform safely and soundly in combat. When
physical points are at 0, it's extremely unsafe for a character to participate
in any risky activities. Next blows delivered will make character wounded,
if the character will happen to be continuously targeted after she's out of combat
and drops below -*phy*, she drops unconcious. A character with phy points below
zero can't participate in combat.

### Crawling

Crawling denotes how well characters can survive lengthy strolls behind the enemy
lines. Also, how well they can escape after a lost encounter. A character with good
crawling score knows how and when throw thunder stones and nets, use some control
magic to make sure that even the slowest of their allies manage to flee.

*TODO*

### Travel

Each character has the amount of travel points equal to her travel rank.

For each quarter of a mile deep in an unknown area without good landmarks,
character must succeed DC 1 travel check or suffer 1 travel damage.  If a
character suffered 2 or more travel damage during one session of orientation,
she becomes confused — she can still backtrack the path to the initial
position. If a character suffers 3 or more travel damage or has 0 travel
points, she is lost and can only wander around in hopes of getting a good
landmark or randomly walk out to a more familiar / open space.

A character can travel long distances with a map with precision depending on
the quality of the map, landmarks and travel check. Traveler should assign the
speed of the march if traveling requires physical activities. Fatigued
travelers can't flee from an encounter. Travelers can travel up to PHY of the
mount (or themselves) hours at full strategic speed and twice the PHY hours at
half of strategic speed. To attempt a flee from an encounter, all the mounts
must have to have at least one full hour of full-speed travel. Experienced
traveler (who has access to *Travel* aspect) may choose to spend a travel point
to get an hour of full-speed travel.

Medium loaded mounts travel half the normal speed; heavily loaded mounts travel
one third the normal speed. Dragging treats dragged load as half the load (you
still have to be able to carry it to start dragging); using a wheeled vehicle
treats carried load as quarter the weight (you still have to be able to cary
half the load to start rolling).

#### Loads (pounds) per phy level and penalties 

| Phy    | ·  | ·· | ··· | ···· | ····· | ······ | Strategic speed    | Tactical speed        |
|--------|---:|---:|----:|-----:|------:|-------:|:------------------:|:---------------------:|
| Light  | 15 | 20 | 33  | 76   | 104   | 132    | —                  | —                     |
| Medium | 30 | 40 | 66  | 111  | 146   | 182    | half the speed     | two thirds the speed  |
| Heavy  | 60 | 80 | 132 | 181  | 231   | 282    | quarter the speed  | half the speed        |

#### Fatigue and exhaustion

Fatigued character suffers -1 *fatigue* pool penalty on physical checks.

Exhausted character suffers a -1 *exhaustion* pool penalty on physical and
mental checks.  

Traveling characters can spend a travel point to ignore effect of fatigue or
exhaustion for an hour; Crawling characters can do the same with crawling
points.

#### Strategic speed

| Type (size) / Template      | Strategic speed | Speed bonus (for each point in Phy beyond third) |
|-----------------------------|-----------------|:-------------------------------------------------|
| Humanoid (large)            | 5 miles/hour    | +1                                               |
| Humanoid (medium)           | 4 miles/hour    | +1                                               |
| Humanoid (small)            | 3 miles/hour    | +1                                               |
| Four-legged animal (large)  | 25 miles/hour   | +2                                               |
| Four-legged animal (medium) | 15 miles/hour   | +2                                               |
| Four-legged animal (small)  | 5 miles/hour    | +2                                               |
| Unliving                    | -1 miles/hour   | +1                                               |

#### Tactical speed

| Type (size) / Template      | Tactical speed  | Speed bonus (for each point in Phy beyond third) |
|-----------------------------|----------------:|--------------------------------------------------|
| Humanoid (large)            | 40ft            | +5                                               |
| Humanoid (medium)           | 30ft            | +5                                               |
| Humanoid (small)            | 20ft            | +5                                               |
| Four-legged animal (large)  | 70ft            | +10                                              |
| Four-legged animal (medium) | 50ft            | +10                                              |
| Four-legged animal (small)  | 40ft            | +10                                              |
| Unliving                    | -10ft           | +5                                               |

### Wealth

As an aspect of makers, artificers and managers, wealth is not available to PCs.
Wealth points, however show the wealth category of a character.

| Wealth | ·  | ·· | ··· | ···· | ····· | ······ | “Free” transactions | Usable active         |
|--------|---:|---:|----:|-----:|------:|-------:|:-------------------:|:---------------------:|
| WU     | 10 | 50 | 250 | 1250 | 6500  | 32500  | 1:100               | 1:10                  |
| Income |  1 |  4 |  16 |   64 |  256  |  1024  | —                   | —                     |

### Socialization

*TODO*

### Magic

Mages can do everything. Worse than experts, yet they really can.

When you create a character, you can choose to be a mage. If you do so, you may choose
if you want to play arcane magician (Art) who uses Weave to construct spells or divine
magician (Might) who uses divine power to perform miracles.

Arcane magicians can furthermore choose to either be a Wizard or a Sorcerer.
Wizards prepare spells but have more spell slots, Sorcerers cast spells spontaneously
(much like divine mages), but have less spell slots.

All the divine mages are spontaneous casters. Divine mages aren't affected by armor but
lose one aspect, while gaining an additional cantrip in one of the aspects. 

#### Cantrips and basic interactions

A mage selects one basic interaction per aspect in which she has at least ·· — she can
use this option at will as a spell-like effect. When mage achieves ·· in an aspect
she selects one more basic interaction and can cast it as a spell. Mages also get
“Magical Aspect” options for each aspect when she gets · in this aspect (see
“Magical Travel” for a reference).

#### Spell slots

Wizard of level L may prepare up to L spells of level 1, L-1 of level 2, ... 1 of level L.
Sorcerers have those numbers reduced by 1 at a minimum of 1 (sorcerer ··· has 2 1st level
spell slots, 1 2nd level and 1 3rd level).

#### Casting for mental points

At any time, a caster may cast any spell she may cast by spending a mental point.
Wizards, however, have to prepare those spells as well.

#### Spell book and foci

Wizards ought to have a spell book to prepare spells for a day. Divine mages ought to
have a focus through which they're casting spells — a holy symbol for a cleric, a 
staff for a druid, what have you. Losing focus means that a character can't channel 
divine energy. A character may have more than one focus or obtain a new focus.

A spell book costs 10 wu + 1 wu for each 1st level spell inscribed, a focus costs 1 wu.

### Equipment and items

Equipment has levels, each next level is more powerful than previous (consult
“Option Power” table); Each next level costs ten times as the cost of current level.

Basic tools required for checks such as disarming traps or mending things add 0 dp to
checks and cost one tenth of a wu. Second level tools add 1 dp, third level tools
add 1 dp and +1, fourth level tools add 3 dp and +1, fifth level tools add 3 dp and +2, 
sixth level tools add 4 dp and +2.

#### Armor

##### Light armor

Base price: 0.1 wu

Light armor adds temporary *armor* physical points — 1 at first level.

##### Medium armor

Base price: 1 wu

Medium armor causes wielder to be medium loaded. First level medium armor
grants -1 *armor* arcane casting dp penalty, 1 temporary *armor* physical point
 and +1 defense *armor* dp bonus.

##### Heavy armor

Base price: 10 wu

Heavy armor causes wielder to be heavy loaded. First level heavy armor grants
-2 *armor* arcane casting dp penalty, 2 temporary *armor* physical points and
+1 defense *armor* dp bonus.

##### Shield

Base prices: 0.1 wu, 1 wu, 5 wu

Shields grant -1 *equipment* attack dp penalty and +1 *equipment* defense dp bonus.
Large shield increases penalties and bonuses to 2.
Tower shield provides cover but you may not perform attacks in the direction covered
with a tower shield.

#### Weapons

All bonuses and penalties weapons grant are of type *weapon*.
Two-handed weapons grant +1 damage and anchored defense dp penalty of the same
absolute value.

##### Martial

Base price: 1 wu

###### Sword-likes

First level sword grants +1 attack dp.

###### Axe-likes

First level axe grants +1 attack dp and -1 defense dp.
While having initiative axes grant +2 attack dp instead.
You may attack axe wielders normally with any weapon.
You can't parry with an axe.

###### Mace-likes

Same as axes, except you get +1 defense dp bonus instead
while defending and initiative doesn't grant bonuses.

###### Spear-likes

First level spear grants -1 defense dp and doesn't provide
damage bonus of a two-handed weapon. Spear-likes is a long weapon, so wielder
of a spear cannot be attacked in melee unless flanked or surprised.

##### Simple

Base price: 0.1 wu

###### Dagger-likes

First level dagger doesn't provide any bonuses or penalties. It is a short weapon,
you can't attack wielders of normal-sized or long weapons unless flanking or
them being surprised.

###### Sling-likes

Anchored range increment: 15ft. -1 *weapon* attack dp penalty. Reload: move action,
may be combined with non-surprise movement.

###### Staff-likes

Long weapon, -1 *weapon* dp penalty to both attack and defense. Can be used to
parry, if used as such, loses two-handed bonus damage and *long* attribute.
Change mode of staff is a move action that can be combined with movement.

##### Exotic

Base price: 10 wu

Designed by players with a proof of equivalence to a first level power of a
martial weapon, or a bow, or a crossbow.

##### Bows

###### Short-bow-likes

Range increment: 60 ft. Reload: free action. You can't move in the round when
you reload a short bow.

###### Long-bow-likes

Range increment: 100 ft. Reload: move action.

##### Crossbows

##### Light-crossbow-likes

Range increment: 120 ft. Reload: standard action.
Anchored +1 *weapon* damage bonus.

##### Heavy-crossbow-likes

Range increment: 210 ft. Reload: full round action.
Anchored +1 *weapon* damage bonus.

### Mounts and vehicles

*TODO*

### Magic items

Magic items are created by attaching auras. If you attach an aura, you become
*linked* to this item and your mental points maximum is reduced by 1.  As a
ritual, you may transfer ownership to a willing character. If you do, your
mental points maximum is no longer reduced due to enchanting this item and
willing character's mental points maximum is reduced by 1.

As a ritual, owner of a magic item can unlink the item if she does, item gets
disenchanted at next dawn. An arcane mage can spend a ritual to link an unlinked
magic item.

If the owner gets too far from the linked magic object, the object becomes
unlinked.

### Constructing game entities

All the options except for basic ones are constructed by players and stored in a
publicly available repository. You may compose different effects within "aspect pie"
for which you're designing an option. For half-a-level of power, you may add a “twist” to
your option — a highly conditional effect that will happen on average, approximately once
or twice per combat. You can't make twists specifically targeting playable races or PCs.
You may limit a core (non-twist) effect to target playable races or PCs gaining 
one-quarter-of-an-option-power-level for this drawback. While constructing an option, you
can spend power level gained that way to acquire twists, not core options.

Please provide an evidence of balance while constructing options, the closer it is to a
mathematical proof, the less work DM will have to do to check if it is balanced.

If there is a serious concern about a certain option, a computer program shall
be written to check the balance of effects against same level of basic
interactions (see “Balance criteria” in other system documents).

### Character sheet

```
# Character
Race Subrace Size
Name
Diety
States: []
Primary aspect:
Secondary aspects:

# Combat Phy 1/1 Mnt 1/1
Physical development ·
Mental development ·

# Crawling 1/1
Consequences []

# Travel 1/1
Strategic speed 3mi/h

# Wealth 0/1
Posessions []
Linked items []
Active 10 wu

# Socialization 1/1
Identities: true identity
Standings []

# Options
## Combat
## Crawling
## Travel
## Socialization

# MLPc
Motive:
Loyalties:
Passions:
Credo:
```
