# Magic: The Gathering

## How to Install:
..* Compile the quake2.sln
..* Add the config to the mod folder
..* drag .dll to the mod folder


## Overview:
* Guns are replaced by spells and lands.
* There are three colors of lands, and 3 decks in this mod. These decks are of two colors each. (Rakdos, Izzet, Dimir)
* Every 30 seconds, there is a simultaneous upkeep/untap/draw step. Additionally, there is a "cleanup" step here, where the player's hand size is reduced to a size of 7 if it is greater than 7.
* Some spells maintain their utility as weapons from the base game.
* Pressing F1 will give some more organized info on your hand and board state.
* Players may play any number of lands per turn.

## Weapons/Spells:
* Ancestral Recall {U} - Draw 3 cards.
* Cyclonic Rift {U}{U}{U}{U}{U}{U} - "Return each creature you don't control to it's owner's hand" (It's just the BFG.)
* Goblin Lore {R}{R} - Draw 4 cards, discard 3 at random.
* Lightning Bolt {R} - Deal 3 damage.
* Fireball {X}{R} - Expend all your mana. Damage multipled by mana consumed.
* Sign in blood {B}{B} - Lose 2 life, draw 2 cards.
* Doomblade {B}{B} - Destroy target non-black creature. (None of these creatures are black :) )
* Dark Ritual {B} - Add {B}{B}{B}.
* "Grapeshot" {0} - Deals X damage, where X is half of the number of times Grapeshot has been cast this turn. 

## Lands:
*naturally...*

* Mountain
* Island
* Swamp

## Commands: 

### debug
Debug mode toggle. (Toggle cleanup step.)

### viewdeck
List Decks. 

### setdeck [0-2]
Selects the deck. Doesn't clear hand, but will affect future draws.

### countdeck
Reports cards in hand.

## lands
Reports number lands in play.

## draw
Draw a card.

## discard
Discards a card at random.

##demo
Distribute cards for demonstration purposes. (Recommended to use debug mode.)


