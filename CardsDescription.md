
# All card types

5 categories of cards: 
* *value*: used to increase or decrease the value of a Var, remember the goal is to reach exactly 42 point.

* *loop*: repeat the next card to be played on a variable, you will need them to go reach faster 42 or you can use them on their opponents to redeuce their score.

* *attacks*: freeze var, slow down speed or add requirements to your opponent stack. When you will have play several time you will eventually find some good opportunities to some on them on yourself.

* *defense*: Memory leak, refatoring or firewall, different way to counter attacks. Some of them will allow you to rewrite the history of you favorite variable.

* *bonus*: Game changer cards! You will definitively love those ones!

| Type | Card Name | Description |
|---------|--------|-------------|
| Value cards | Increment one var by 1 | Increment one var by 1. It can be any player's var. |
| Value cards | Increment one var by 2 | Increment one var by 2. It can be any player's var. |
| Value cards | Increment one var by 3 | Increment one var by 3. It can be any player's var. |
| Value cards | Increment one var by 5 | Increment one var by 5. It can be any player's var. |
| Value cards | Increment one var by 8 | Increment one var by 8. It can be any player's var. |
| Value cards | Decrement one var by 1 | Decrement one var by 1. It can be any player's var. |
| Value cards | Decrement one var by 2 | Decrement one var by 2. It can be any player's var. |
| Loop | Repeat x2 | The next yellow card put on this one is valued twice. |
| Loop | Repeat x3 | The next yellow card put on this ones is valued three times. |
| Loop | Repeat ${PlayersCount} | The next yellow card is valued as many times as there are players in the game. |
| Attack | Code Freeze  | Blocks all vars for 2 turns. |
| Attack | Var Freeze   | Blocks 1 var for 2 turns. |
| Attack | Legacy code  | Only allows to play +/-1 or +/-2 values on your vars. |
| Attack | Condition (varB < varA) | Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resoluton. |
| Attack | Condition (varA < varB) | Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resoluton. |
| Attack | Memory Leak  | Reset to 0 the var if its values is a multiple of 3. |
| Defense | Rollback  | Remove last card put on any player's game. |
| Defense | Refactoring  | Remove a _Legacy code_ or _Condition_ card. |
| Defense | Firewall  | Return any attack to its sender's game.  |
| Bonus  | Pair programming | Draw 3 cards with another player and agree on how to use them or discard everything! |
| Bonus  | Pull request | Merge (rebase) vars A and B. So either move all your Value cards from A on top of B, or from B on top of A. |
| Bonus  | Continuous deployment | Play twice when the selected var is a multiple of 7. |
| Bonus  | Feature Flipping | Delete 1 card anywhere (on any player, any vars, any hands) |
| Bonus  | Open Source | All players put their hand face up on the table for 2 rounds. |
| Bonus  | Mob Programming | All cards change hands in the direction decided by the card player. |


# Attacks

## Code Freeze 

Blocks all vars for 2 turns.

## Var Freeze

Blocks 1 var for 2 turns.

## Legacy code

Only allows to play +/-1 or +/-2 values on your vars.

## Condition

- (varB < varA): Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resoluton.
- (varA < varB): Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resoluton.

## Memory Leak

Reset to 0 the var if its values is a multiple of 3.

# Defense

## Rollback

Remove last card put on any player's game.

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
