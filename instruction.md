# Everdell

## Objective

Build the most valuable woodland city by collecting resources, playing Critter and Construction cards, completing Events, and using workers efficiently. The player with the most points at the end wins.

## Components

The base game includes:

- Game board and Ever Tree
- 128 Critter and Construction cards
- Forest cards
- Basic Event tiles and Special Event cards
- Workers
- Berries, twigs, resin, and pebbles
- Point tokens and occupied tokens

## Setup

1. Place the board on the table and place the Ever Tree on its stump.
2. Put the four resources in supply piles beside the river. Place point tokens and occupied tokens beside the board.
3. Shuffle the Forest cards and place them on the Forest clearings. Use 3 Forest cards in a two-player game, or 4 in a three- or four-player game.
4. Place the 4 Basic Event tiles along the river. Shuffle the Special Event cards and place 4 on the lower branches of the Ever Tree.
5. Shuffle the main deck and place 8 cards face up in the Meadow. Put the remaining deck inside the Ever Tree.
6. Each player chooses a color and starts with 2 workers.
7. Deal starting cards according to player order: the first player draws 5, the second draws 6, the third draws 7, and the fourth draws 8.
8. Place each player's other 4 workers on the Ever Tree: 1 on Spring, 1 on Summer, and 2 on Autumn.
9. Choose a first player.

There is no resource limit. Use substitutes if a supply runs out.

## Turn Structure

Starting with the first player, take one action on your turn. Continue taking turns until all players have finished. The three possible actions are:

1. **Place a Worker**
2. **Play a Card**
3. **Prepare for the Next Season**

After resolving the action, the turn passes to the next player.

### Place a Worker

Take one of your available workers and place it on an unoccupied location. Locations may be:

- A basic location on the board
- A Forest location
- An Event
- A Construction in your city that has a worker-placement ability
- An opponent's open destination, when its ability allows visits

Resolve the location immediately. A location may provide resources, cards, points, or another effect. Some locations keep the worker permanently; others return it when you prepare for a season.

### Play a Card

Play one Critter or Construction card from your hand or from the Meadow.

To play a card:

1. Check that your city has room.
2. Pay the resources shown on the card, unless an ability lets you play it for free or at a discount.
3. Place the card in your city and resolve its immediate ability.
4. Replenish the Meadow if the card came from the Meadow.

A card may also be played by using a matching **open** occupation symbol or another card ability. Follow the ability on the card that enables the play. A card-playing ability cannot be combined with another card-playing ability when the card specifically forbids it.

The city can contain at most 15 card spaces. Each Critter or Construction normally uses one space. Event cards do not count toward this limit. A Husband and Wife pair share one space, and the Wanderer does not use a city space.

### Prepare for the Next Season

You may prepare when all of your workers are deployed and you cannot, or do not wish to, play another card.

1. Bring back all of your deployed workers.
2. Take the worker or workers shown for the next season from the Ever Tree.
3. Resolve the next season's listed bonus.
4. End your turn.

Players prepare for seasons independently; they do not wait for one another. The season order is **Spring, Summer, Autumn**. Autumn is the final season. Do not prepare for another season after Autumn.

Season bonuses are shown on the Ever Tree. They add workers and may activate Production cards, draw cards, or allow other listed actions. Resolve all parts of the bonus when you enter the season.

## Card Types

Cards have one of five colors and roles:

- **Tan Traveler:** Activates once immediately when played and never again.
- **Green Production:** Activates immediately when played and again when the appropriate season bonus activates Production cards.
- **Red Destination:** Activates when a worker is placed on it. An open destination may be visited by opponents.
- **Blue Governance:** Gives bonuses after certain cards are played or provides card discounts and related effects.
- **Purple Prosperity:** Provides its base points and its listed end-game bonus.

The complete scraped card effects are in [`cards.json`](cards.json).

## Resources

The four resources are:

- Berries
- Twigs
- Resin
- Pebbles

Collect resources from locations and card abilities. Spend them to play cards. Resource costs must be paid unless an effect reduces or replaces part of the cost.

## Events

Basic and Special Events provide additional objectives. Place a worker on an Event only when you meet its requirement, then claim it and score it according to its rules. Events do not use city spaces.

## Ending the Game

After reaching the end of Autumn, a player who cannot or does not want to take another action finishes the game and passes. A player who has passed cannot receive cards or resources. Other players continue until everyone has passed.

Add up each player's points from:

- The base value of cards in the city
- Point tokens
- Purple Prosperity bonuses
- Journey points, if applicable
- Completed Basic and Special Events
- Any other end-game card abilities

The player with the highest total wins. If tied, the player who completed the most Events wins. If still tied, the player with the most leftover resources wins.

## Practical Strategy

- Build at least one reliable resource engine early, such as Production cards.
- Plan city space before playing expensive cards.
- Use the Meadow as an opportunity for cards that do not appear in your hand.
- Watch the season workers on the Ever Tree so you can prepare at a useful time.
- Prefer cards whose effects support one another, such as Farms with cards that produce extra berries or cards that reward specific card types.
- Do not delay the final season indefinitely: the game ends after Autumn and players must eventually pass.
