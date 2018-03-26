# Attacks

## Code Freeze 
```
while (turns < 2) {freezeAllVars();}
```
Blocks all vars for 2 turns.

## Var Freeze
```
while (turns < 2) {freezeOneVar();}
```
Blocks 1 var for 2 turns.

## Legacy code

Only allows to play +/-1 or +/-2 values on your vars.

## Condition

```
if (varA > varB) {cancelCard();}
```

Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resoluton.

```
if (varB < varA) {cancelCard();}
```
Forbids any card that is breaking this condition. If the condition is already broken, then forbids any card that is not going towards its resoluton.

## Memory Leak

```
if (var % 3 == 0) {var = 0;}

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
```
git checkout varA && git rebase varB
```
or
```
git checkout varB && git rebase varA
```
Merge (rebase) vars A and B

## Continuous deployment

```
if (var % 7 == 0) {playTwice();}

```
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
