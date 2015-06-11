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
 
   + Restore 1 health point to allies over a short rest *(To short rest, spend one hour not engaged in a combat)*

   + Make a DC X *crawling + elusiveness* check to detect or set up traps or secret doors; or apply poison; or use grappling hook or a rope swiftly; where X is the item level of corresponding trap, secret door or posion; or circumstance difficulty of using a hook or a rope.

 * travel (distance | pathfinding, speed)
 
   + Strategic speed of the party is increased by 1 *(see “Strategic movement”)*
   
   + Make a DC 1 *travel + pathfinding* check to predict well-known dangerous places along your path.
   
 * wealth (active | wealth category, possessions)

   + As you get this option, restore 1 wealth point. If you can't, add wealth units to your active equal to half of the unit value of your maximum wealth category.

   + Spend 50 wu to make a DC 1 *wealth + wealth points* check to reveal a minor fact about a certain obscure lore, or a major fact about a widely-known lore or hire an outlook for a day. *(Wu stands for “wealth units” — the measure of wealth that is held in a character's inventory)*
   
 * socialization (identity | gather information, standings)

   + As you get this option, increase a standing with any faction by 1.

   + Spend a short rest to make a DC 1 *socialization + gather information* check to reveal a minor fact about a certain obscure lore or a major fact about a widely-known lore.

### Character sheet

```
# Character
Race Subrace Size
Name
Diety
Primary aspect:
Secondary aspects:

# Combat
Physical development ·
Mental development ·
HP 1/1
MP 1/1

# Crawling
Elusiveness ·
Consequences []

# Travel
Pathfinding ·
Strategic speed ·

# Wealth
Wealth category 1/1
Posessions []
Wealth Points 1/1
Active 50 wu

# Socialization
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
