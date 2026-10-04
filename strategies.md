# Everdell Strategy Guide

This guide follows the project source order in `instruction.md`: `cards.json` is the canonical card catalog, while `instruction.md` supplies gameplay rules and constraints. It gives two kinds of advice:

- **High-ceiling plans:** strong when the required cards, resources, and Events line up.
- **Universal plans:** reliable when the Meadow, starting hand, or opponents do not cooperate.

`cards.json` supplies card color, Common/Unique rarity, costs, printed `basePoints`, city spaces, structured effects, end-game scoring, quantities, and paired occupation cards. It does not provide Event requirements or rewards or a full game state. Strategic rankings and score estimates are therefore conditional, not a mathematically proven maximum. Follow the documented quantity discrepancy rather than treating card counts as verified odds.

## Core Principle

A good city does three jobs at once:

1. It produces resources or cards efficiently.
2. It turns those resources and cards into points.
3. It preserves enough city space and workers to keep taking valuable actions through Autumn.

Do not judge a card only by its printed points. Judge it by its total value over the remaining seasons, including production activations, free plays, card draw, Event access, and city space consumed.

## Ranked High-Ceiling Strategies

### 1. Event Control: King plus Event Density

**Goal:** complete several Events, then amplify them with the King.

The King is a Unique, 4-point Prosperity Critter costing 6 berries. Its end-game effect adds 1 point per Basic Event and 2 per Special Event achieved. It is excellent only when the city can realistically meet multiple Event requirements. Since its bonus is scored at game end, it does not need to be played before claiming Events.

**Build around it with:**

- **Queen:** each worker placement there may play a card from hand or Meadow worth up to 3 base points for free.
- **Inn:** when placing a worker there, play a Meadow card for 3 fewer resources of your choice.
- **Cemetery:** play one revealed card for free, while also creating a permanent worker commitment.
- **Ranger:** move a deployed worker and unlock the second Dungeon cell.
- **Wanderer, Teacher, Fair Grounds, Historian, and Ruins:** increase access to cards and improve the chance of finding Event-enabling pieces.

**Execution:**

1. Check the visible Event requirements before committing to the King.
2. Build only the card types needed for the Events you can actually reach.
3. Use free-play and draw effects to satisfy requirements without spending the whole game on raw resources.
4. Claim the easiest Events first when another player could take them.
5. Play the King when its 4 printed points and expected Event bonus justify its 6-berry cost and city space; Events achieved before playing the King still count.

**Failure condition:** if two or more Event requirements are unavailable by late Summer, stop investing in the King and use its space and resources for direct points or production.

### 2. Production Conversion: Farms into Point Tokens

**Goal:** generate surplus berries and resources, then convert repeated production into points.

The core engine is early green Production plus cards that either increase resource output or convert surplus to points. Key catalog entries:

| Card | Color / rarity | Base points | Cost | Engine effect |
|---|---|---:|---|---|
| Farm | Production / Common | 1 | 2 twigs, 1 resin | 1 berry on play and during Production |
| General Store | Production / Common | 1 | 1 twig, 1 pebble | 1 berry, or 2 if you have a Farm |
| Barge Toad | Production / Common | 1 | 2 berries | 2 twigs per Farm on play and during Production |
| Chip Sweep | Production / Common | 2 | 3 berries | Activates one Production card on play and during Production |
| Doctor | Production / Unique | 4 | 4 berries | May pay up to 3 berries for 1 point each on play and during Production |
| Woodcarver | Production / Common | 2 | 2 berries | May pay up to 3 twigs for 1 point each on play and during Production |
| Monk | Production / Unique | 0 | 1 berry | May give up to 2 berries to an opponent for 2 points each on play and during Production |
| Shepherd | Traveler / Unique | 1 | 3 berries | On play: gain 3 berries and 1 point token per point token on your Chapel |

**Execution:**

1. Establish one or two green Production cards early. In the base game they activate when played and when Spring and Autumn Production activate; Summer draws cards instead.
2. Add converters only when the resources can be paid. Do not spend the same resource more than once.
3. Use Chip Sweep on a Production card whose effect is useful now; Chip Sweep activates that card, it does not independently grant resources.
4. Convert excess berries or twigs before the game ends rather than leaving them unused.
5. Weigh the Farm's 2-twig, 1-resin cost and one-space use against the remaining Production activations. Avoid overbuilding Farms.

**Best use:** this is a strong answer when the Meadow supplies Farms, General Store, Barge Toad, Doctor, or Woodcarver, but Events are contested or unreliable.

**Failure condition:** if production cannot activate twice, stop adding engine pieces and take direct points, free plays, or card-draw actions instead.

### 3. Construction Multipliers: Castle, Palace, School, and Theater

**Goal:** fill the city with the exact card classes that increase end-game bonuses.

These Unique Prosperity Constructions reward density, so treat them as a package rather than isolated cards:

| Card | Base points | Cost | End-game bonus |
|---|---:|---|---|
| Castle | 4 | 2 twigs, 3 resin, 3 pebbles | 1 point per Common Construction |
| Palace | 4 | 2 twigs, 3 resin, 3 pebbles | 1 point per Unique Construction, including itself |
| School | 2 | 2 twigs, 2 resin | 1 point per Common Critter |
| Theater | 3 | 3 twigs, 1 resin, 1 pebble | 1 point per Unique Critter |

**Execution:**

1. Decide whether the available cards favor Constructions or Critters.
2. Choose one primary multiplier and possibly one secondary multiplier. Chasing all four usually wastes spaces.
3. Play the multiplier before the final cards it will score, unless a free-play opportunity makes the order clearly better.
4. Courthouse is a Unique, 2-point Governance Construction costing 1 twig, 1 resin, and 2 pebbles; it gains one twig, resin, or pebble after you play each other Construction.
5. Shopkeeper is a Unique, 1-point Governance Critter costing 2 berries; it gains one berry after you play each other Critter.
6. Use Palace or Castle only when enough matching Constructions are available. Use School or Theater only when enough matching Critters are available.

**Space warning:** a multiplier card can be worth less than a normal point-producing card if the city lacks enough matching cards. Count the remaining empty spaces before committing.

### 4. Worker Conversion: Monastery, Chapel, and Clocktower

**Goal:** turn worker placements into points while preserving action efficiency.

| Card | Color / rarity | Base points | Cost | Worker / scoring effect |
|---|---|---:|---|---|
| Monastery | Destination / Unique | 1 | 1 twig, 1 resin, 1 pebble | Pay 2 resources for 4 points; worker stays permanently. A second worker requires Monk. |
| Chapel | Destination / Unique | 2 | 2 twigs, 1 resin, 1 pebble | Place 1 point token and draw 2 cards per token on Chapel. |
| Clocktower | Governance / Unique | 0 | 3 twigs, 1 pebble | Starts with 3 tokens; before season preparation, spend at most 1 to activate a Basic or Forest location where you have a worker. Remaining tokens score 1 each. |
| University | Destination / Unique | 3 | 1 resin, 2 pebbles | Worker action discards one city card, refunds its printed cost, gains 1 resource and 1 point; point tokens on the discarded card are lost. |

**Execution:**

1. Use Monastery when the payment is affordable and the permanent worker will not cost more than 4 points in lost actions.
2. Use Chapel early enough that its card draw can influence later plays. A late Chapel placement is mainly a point-token action.
3. Use Clocktower to repeat the strongest occupied Basic or Forest location, not merely to recover a small resource.
4. Use University to replace a low-value or obsolete card, especially when the returned resources fund a stronger end-game card.
5. Treat permanent worker placements as a real cost: they remove workers from future resource and Event locations.

This package is especially strong when the board has valuable worker locations and the city already has enough production to pay its costs.

### 5. Free-Play and Space Efficiency

**Goal:** acquire expensive effects without paying their full costs or consuming unnecessary spaces.

Important tools include:

- **Queen:** Unique, 4-point Destination Critter costing 5 berries; worker action plays one card from hand or Meadow for free, with up to 3 base points.
- **Inn:** Common, 2-point Destination Construction costing 2 twigs and 1 resin; worker action plays a Meadow card for 3 fewer resources of your choice.
- **Cemetery:** Unique, 0-point Destination Construction costing 2 pebbles; worker action reveals 4 cards from deck/discard and plays one free, but the worker stays permanently.
- **Postal Pigeon:** Common, 0-point Traveler Critter costing 2 berries; on play, reveal 2 cards and play one card worth up to 3 base points for free.
- **Innkeeper:** Unique, 1-point Governance Critter costing 1 berry; discard it to reduce a Critter's cost by 3 berries.
- **Crane:** Unique, 1-point Governance Construction costing 1 pebble; discard it to reduce a Construction's cost by 3 resources of your choice.
- **Dungeon:** place a Critter beneath it to reduce a later card cost by 3; the prisoner no longer scores or occupies normal city status.
- **Wanderer:** draws 3 cards without using a city space.
- **Husband + Wife:** share one space, and the Wife is worth 3 points when paired; with a Farm, the Husband also produces a flexible resource during Production.

**Execution:**

1. Use free-play effects on cards with strong production, end-game bonuses, or Event value.
2. Do not spend a Queen or Cemetery activation on a card that could be cheaply played from resources.
3. Use Dungeon on a low-value Critter only when the discount enables a substantially better card.
4. Use Ruins or University to recover value from a card that has stopped contributing.
5. Keep at least one or two spaces open for late opportunities unless a multiplier strategy makes every remaining space predictable.

## Universal Strategy

When the game state is unclear, follow this priority order:

1. **Create one dependable engine.** A Farm, Mine, Resin Refinery, Twig Barge, General Store, or another green Production card is usually more useful than several unrelated one-shot cards.
2. **Increase options.** Wanderer, Teacher, Fair Grounds, Historian, Chapel, and Ruins reduce the chance that a poor hand locks the plan.
3. **Use flexible costs.** Judge replaces one resource type, Peddler trades up to two resources, Inn reduces a card cost, and Queen provides a free low-point card.
4. **Claim achievable Events.** Events are valuable, but an Event that requires a city-wide rebuild is not automatically worth pursuing.
5. **Convert surplus before passing.** Doctor, Woodcarver, Monk, Shepherd, Monastery, and other point-token effects prevent resources from becoming dead leftovers.
6. **Protect space and workers.** Filling all 15 card spaces, taking too many permanent workers, or delaying a season transition can erase the value of a good engine.

This plan is less explosive than a perfect King or multiplier build, but it performs well across many Meadow layouts because it values production, draw, flexible costs, direct points, and late-game conversion.

## Seasonal Playbook

### Spring

- Set up production and card draw.
- Green Production cards activate when played and again when Spring Production activates; cards already in the city can activate again in Autumn.
- Do not rush expensive end-game multipliers before knowing which card classes are available.
- Prepare as soon as the next worker and production activation are worth more than another weak action.

### Summer

- Summer is the card-draw season, not a green Production activation; use its draws and your existing engine to build a coherent package.
- Use Queen, Inn, Cemetery, Crane, or Innkeeper to bypass a difficult cost.
- Pursue Events once their requirements are visible and attainable.
- Add the main multiplier only after confirming there are enough cards for it to score.

### Autumn

- Stop expanding a weak engine.
- Use workers for Events, Monastery, Chapel, Clocktower, or other direct-value actions.
- Fill remaining spaces with the highest point or end-game bonus available.
- Use University or Ruins to recover value from a card that no longer fits.
- Spend or convert resources before passing; leftover resources are only useful when a card such as Architect rewards them.

## Decision Rules and Pivots

- **Good production, weak Events:** choose Production Conversion.
- **Many matching Constructions:** choose Castle or Palace, then support it with Courthouse.
- **Many matching Critters:** choose School or Theater, then support it with Shopkeeper.
- **Several attainable Events:** choose Event Control and consider King.
- **Strong direct-point locations:** choose Worker Conversion, but price permanent workers against lost actions.
- **Multiple free-play cards:** choose a tempo build and spend free plays on the most expensive or most synergistic cards.
- **No coherent package by late Summer:** stop chasing bonuses and maximize immediate points, resources-to-points conversions, and Events that are already achievable.

## Common Mistakes

- Playing King without a realistic Event plan.
- Playing Castle, Palace, School, or Theater without enough matching cards.
- Building too many Farms or production cards to benefit from them before Autumn.
- Filling all 15 spaces too early and losing access to better late cards.
- Treating permanent Monastery or Cemetery workers as free.
- Using a free-play effect on a low-impact card.
- Holding resources for a future plan that cannot be completed.
- Delaying season preparation after all useful actions are gone.

## Remaining Data Limits for Numerical Optimization

`cards.json` now provides structured card colors, Common/Unique rarity, costs, printed points, spaces, prerequisites, effects, end-game scoring, quantities, and occupation pairings. Exact score optimization still requires:

- Basic and Special Event requirements and values;
- Meadow, deck, discard, opponent, and worker state.

Structured effects encode the available card text and should be checked against the official rules before use in a legal-action simulator. The sourced quantities total 129, while the official rules state 128 cards. Preserve individual sourced quantities, but do not use them to calculate deck odds or assume the total is verified. Without Event data and a concrete game state, no program can honestly calculate the exact maximum score or prove that one sequence is optimal. Use strategic packages, conditional estimates, and explicit assumptions instead of unsupported precision.

## Potential Calculator or Simulator Extensions

The current card schema supports this shape:

```json
{
  "name": "Farm",
  "category": "Construction",
  "color": "Production",
  "rarity": "Common",
  "basePoints": 1,
  "cost": {"twigs": 2, "resin": 1},
  "spaces": 1,
  "prerequisites": [],
  "effects": [
    {"trigger": "onPlay", "action": "gainResource", "resource": "berries", "amount": 1},
    {"trigger": "production", "action": "gainResource", "resource": "berries", "amount": 1}
  ],
  "endGameScoring": [],
  "quantity": 8,
  "pairedCritter": ["Husband", "Wife"],
  "description": "When played and during Production, gain 1 berry."
}
```

For example, the Farm entry costs 2 twigs and 1 resin and its structured effects award one berry when played and during Production. Do not replace sourced values with outdated illustrative data.

The game-state model should include:

- season and available workers;
- resources, hand, Meadow, deck, and discard pile;
- city cards and occupied spaces;
- temporary versus permanent worker placements;
- completed Events and remaining Event requirements;
- opponent-visit assumptions and contested locations;
- all point tokens and end-game bonuses.

A practical optimizer can then:

1. Generate only legal actions from the current state.
2. Apply card, worker, season, resource, and Event effects.
3. Prune states that have fewer points, resources, options, and available spaces than an equivalent state.
4. Search promising action sequences with branch-and-bound or dynamic programming.
5. Score base points, point tokens, Events, Journey points, purple bonuses, and leftover-resource bonuses at the end.
6. Report both the highest theoretical score and a robust alternative that performs well across Meadow and opponent variations.

Before trusting the optimizer, test card effects, season transitions, permanent workers, city-space exceptions, Husband/Wife pairing, Dungeon prisoners, Wanderer, Events, and end-game scoring independently.
