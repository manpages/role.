# Generic Epic Fantasy Constructor Playtest

## Wheel of aspects

![Wheel of aspects](./wheel.png)

There are five aspects to a fantasy game —

 * combat (tactical engagements)
 * crawling (getting out of the trouble, doing things between combat in dangerous places)
 * travel (getting from point A to point B effectively)
 * wealth (being able to effectively function within economy system)
 * socialization (fitting into the community, gethering infomration)

As you generate a character, you can pick one primary aspect and two secondary ones.
Right now, to impose interesting restrictions and be tropey, it's allowed to pick any
aspect as primary and its neighbours as secondaries.

Primary aspects are more developed than secondary aspects: Nth level of primary aspect
grants access to options of Nth level in this aspect, whilst Nth level of secondary
aspect grants access to options of N-1st level of options i this aspect.

You can also choose to have all five aspects as your secondary aspects, see “Mage”.

### Basic interactions

Every aspect of the game has at least one basic interaction that is used as a baseline for balancing
player-constructed abilities. All the basic interactions within an aspect are considered to be a priori balanced against each other.

 * combat (health | physical development, mental development)
 
   + Attack for 1 *(To attack for X, clash phy vs phy, honoring equipment and tactical bonuses and penalties. If you win, deal X damage to target)*
   
 * crawling (resource restoration | elusiveness, consequences of harm)
 
   + Grant 1 *crawling* temorary hit point to yourself and each friendly character resting with you over a short rest *(To short rest, spend one hour not engaged in a combat)*. No retry *(the same character can't try this several times before taking at least a short rest)*

   + Make a DC 1 *crawling + elusiveness* check to detect or set up traps or secret doors; or apply poison; or use grappling hook or a rope swiftly to perform a simple action; for items with item level 1, minorly hidden secret door or posion with item level 1

 * travel (distance | pathfinding, speed)
 
   + **Quick march**: Pay 1 travel point: for the next travel, each character in the party gets +1 mile/hour *traveling* strategic speed bonus *(see “Strategic movement”)*

   + **Extend stamina**: Pay 1 travel point: get an extra hour of full-speed traveling

   + **Second wind**: Pay 1 travel point: for an hour, ignore exhaustion or fatigue caused by traveling (exhaustion and fatigue should be paid separately)
   
   + **Travel safe**: Make a DC 1 *travel + pathfinding* check to predict well-known dangerous places along your path

   + **Intuit general direction**: Make a DC 1 *travel + pathfinding* check to intuit where is northen hemisphere (or hemiplane, if you're in Discworld)

   + **Traveler's knowledge**: Make a DC 1 *travel* check to determine a minor fact about land, plane, location, nation or inhabitants of a location; At all times *(“at all times” means that even a mage who has this option has the following effect)* you know how to use and take care of traveling tools and mounts

   + **Traveler's craft**: Make a DC 1 *travel* check to grant 1 *traveling* temorary hit point to a mount or 1 *traveling* temorary structural point to a vehicle. No retry *(the same character can't try this several times before taking at least a short rest)*.; At all times you can spend a short rest to grant 1 *traveling* temorary hit point to a mount or 1 *traveling* temorary structural point to a vehicle.
   
 * wealth (active | wealth category, possessions)

   + As you get this option, restore 1 wealth point. If you can't, add wealth units to your active equal to half of the unit value of your maximum wealth category.

   + Spend 50 wu to make a DC 1 *wealth + wealth points* check to reveal a minor fact about a certain obscure lore, or a major fact about a widely-known lore or hire an outlook for a day. *(Wu stands for “wealth units” — the measure of wealth that is held in a character's inventory)*
   
 * socialization (identity | gather information, standings)

   + As you get this option, increase a standing with any faction by 1.

   + Spend a short rest to make a DC 1 *socialization + gather information* check to reveal a minor fact about a certain obscure lore or a major fact about a widely-known lore.

### Crawling

### Travel

Each character has the amount of travel points equal to her travel rank.

For each quarter of a mile deep in an unknown area without good landmarks, character must succeed DC 1 travel check or suffer 1 travel damage.
If a character suffered 2 or more travel damage during one session of orientation, she becomes confused — she can still backtrack the path
to the initial position. If a character suffers 3 or more travel damage or has 0 travel points, she is lost and can only wander around in
hopes of getting a good landmark or randomly walk out to a more familiar / open space.

A character can travel long distances with a map with precision depending on the quality of the map, landmarks and travel check. Traveler should
assign the speed of the march if traveling requires physical activities. Fatigued travelers can't flee from an encounter. Travelers can travel
up to PHY of the mount (or themselves) hours at full strategic speed and twice the PHY hours at half of strategic speed. To attempt a flee from
an encounter, all the mounts must have to have at least one full hour of full-speed travel. Experienced traveler (who has access to *Travel* aspect)
may choose to spend a travel point to get an hour of full-speed travel.

Medium loaded mounts travel half the normal speed; heavily loaded mounts travel one third the normal speed. Dragging treats dragged load as half
the load (you still have to be able to carry it to start dragging); using a wheeled vehicle treats carried load as quarter the weight (you still
have to be able to cary half the load to start rolling).

#### Loads (pounds) per phy level and penalties 

| Phy    | ·  | ·· | ··· | ···· | ····· | ······ | Strategic speed    | Tactical speed        |
|--------|---:|---:|----:|-----:|------:|-------:|:------------------:|:---------------------:|
| Light  | 15 | 20 | 33  | 76   | 104   | 132    | —                  | —                     |
| Medium | 30 | 40 | 66  | 111  | 146   | 182    | half the speed     | two thirds the speed  |
| Heavy  | 60 | 80 | 132 | 181  | 231   | 282    | quarter the speed  | half the speed        |

#### Fatigue and exhaustion

Fatigued character suffers -1 *fatigue* pool penalty on physical checks.
Exhausted character suffers a -1 *exhaustion* pool penalty on physical and mental checks.
Traveling characters can spend a travel point to ignore effect of fatigue or exhaustion for an hour;
Crawling characters can do the same with crawling points.

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
Elusiveness ·
Consequences []

# Travel 1/1
Pathfinding ·
Strategic speed ·

# Wealth 1/1
Wealth category ·
Posessions []
Active 50 wu

# Socialization 1/1
Identities: true identity
Gather infromation ·
Standings []

# Options
## Combat
## Crawling
## Travel
## Wealth
## Socialization

# MLPc
Motive:
Loyalties:
Passions:
Credo:
```
