
# All card types

5 categories of cards: 
* *value*: used to increase or decrease the value of a Var, remember the goal is to reach exactly 42 points.

* *loop*: repeat the next card to be played on a variable, you will need them to go reach faster 42 or you can use them on their opponents to reduce their score.

* *attacks*: freeze var, slow down speed or add requirements to your opponent stack. When you will have played several times you will eventually find some good opportunities to play some of them on yourself.

* *defense*: Memory leak, refactoring or firewall, different way to counter attacks. Some of them will allow you to rewrite the history of your favorite variable.

* *bonus*: Game changer cards! You will definitively love those ones!

If you have any question about how to play those cards, [please ask us](https://github.com/kids-code-games/variables-war/labels)!

*Tons of alternatives cards could be added, [we are waiting for your suggestions](https://github.com/kids-code-games/variables-war/labels)!*

|Number of cards in a deck| Type | Card Name | Description |
|---|---------|--------|-------------|
|x6| Start Card | Variable A | Given to every playing at the beginning of the game. (Not to be played) |
|x6| Start Card | Variable B | Given to every playing at the beginning of the game. (Not to be played) |
|x6| Value cards | Increment one var by 1 | Increment one var by 1. It can be any player's var. |
|x10| Value cards | Increment one var by 1 | Increment one var by 1. It can be any player's var. |
|x10| Value cards | Increment one var by 2 | Increment one var by 2. It can be any player's var. |
|x10| Value cards | Increment one var by 3 | Increment one var by 3. It can be any player's var. |
|x8| Value cards | Increment one var by 5 | Increment one var by 5. It can be any player's var. |
|x4| Value cards | Increment one var by 8 | Increment one var by 8. It can be any player's var. |
|x7| Value cards | Decrement one var by 1 | Decrement one var by 1. It can be any player's var. |
|x4| Value cards | Decrement one var by 2 | Decrement one var by 2. It can be any player's var. |
|x3| Loop | Repeat x2 | The next yellow card put on this one is valued twice. |
|x3| Loop | Repeat x3 | The next yellow card put on this ones is valued three times. |
|x1| Loop | Repeat ${PlayersCount} | The next yellow card is valued as many times as there are players in the game. |
|x3| Attack | Code Freeze  | Blocks all vars for 2 turns. |
|x3| Attack | Var Freeze   | Blocks 1 var for 2 turns. |
|x6| Attack | Legacy code  | Only allows playing +/-1 or +/-2 values on your vars. |
|x3| Attack | Condition (varB < varA) | Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resolution. |
|x3| Attack | Condition (varA < varB) | Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resolution. |
|x2| Attack | Memory Leak  | Reset to 0 the var if its values is a multiple of 3. |
|x5| Defense | Rollback  | Remove the last card put on any player's game. |
|x7| Defense | Refactoring  | Remove a _Legacy code_ or _Condition_ card. |
|x2| Defense | Firewall  | Return any attack to its sender's game.  |
|x3| Bonus  | Pair programming | Draw 3 cards with another player and agree on how to use them or discard everything! |
|x2| Bonus  | Pull request | Merge (rebase) vars A and B. So either move all your Value cards from A on top of B, or from B on top of A. |
|x2| Bonus  | Continuous deployment | Play twice when the selected var is a multiple of 7. |
|x4| Bonus  | Feature Flipping | Delete 1 card anywhere (on any player, any vars, any hands) |
|x2| Bonus  | Open Source | All players put their hand face up on the table for 2 rounds. |
|x2| Bonus  | Mob Programming | All cards change hands in the direction decided by the card player. |

# Anatomy of a card

<div align="center">
<img width="600" src="./images/board-cards.jpeg" />
</div>


# Attacks

## Code Freeze 

Blocks all vars for 2 turns.

## Var Freeze

Blocks 1 var for 2 turns.

## Legacy code

Only allows playing +/-1 or +/-2 values on your vars.

## Condition

- (varB < varA): Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resolution.
- (varA < varB): Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resolution.

## Memory Leak

Reset to 0 the var if its values is a multiple of 3.

# Defense

## Rollback

Remove the last card put on any player's game.

## Refactoring

Remove a _Legacy code_ or _Condition_ card.

## Firewall

Return any attack to its sender's game. 

# Bonus

## Pair programming

Draw 3 cards with another player and agree on how to use them or discard everything!

## Pull request

Merge (rebase) vars A and B. So either move all your Value cards from A on top of B, or from B on top of A.

## Continuous deployment

Play twice when the selected var is a multiple of 7.

## Feature Flipping

Delete 1 card anywhere (on any player, any vars, any hands)

## Open Source

All players put their hand face up on the table for 2 rounds.

## Mob Programming

All cards change hands in the direction decided by the card player.

# Value cards

## Increment

- by 1: Increment one var by 1. It can be any player's var.
- by 2: Increment one var by 2. It can be any player's var.
- by 3: Increment one var by 3. It can be any player's var.
- by 5: Increment one var by 5. It can be any player's var.
- by 8: Increment one var by 8. It can be any player's var.

## Decrement 

- by 1: Decrement one var by 1. It can be any player's var.
- by 2: Decrement one var by 2. It can be any player's var.

## Repeat

- 2: The next yellow card put on this one is valued twice.
- 3: The next yellow card put on this ones is valued three times.
- ${PlayersCount}: The next yellow card is valued as many times as there are players in the game.
