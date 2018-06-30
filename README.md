## Welcome to Variables War, the coding playing card game

<p align="center">
    <a href="https://kids-code-games.github.io/variables-war/" target="_blank">
    <img width="500" src="./images/variables-war.png" alt="Variables WarCard Game">
    </a>
</p>
[Github pages of this project](https://kids-code-games.github.io/variables-war/)


![Image](https://www.anthonyherve.fr/uploads/images/855b41d0232d6b2a4ba39f8625ef7644bf18e394.gif)

### What is this game about?

TODO

### The rules

TODO

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
| Defense | Rollback  | Remove last card put on any player's game. |
| Bonus  | Pair programming | Draw 3 cards with another player and agree on how to use them or discard everything! |
| Bonus  | Pull request | Merge (rebase) vars A and B. So either move all your Value cards from A on top of B, or from B on top of A. |
| Bonus  | Continuous deployment | Play twice when the selected var is a multiple of 7. |
| Bonus  | Feature Flipping | Delete 1 card anywhere (on any player, any vars, any hands) |
| Bonus  | Open Source | All players put their hand face up on the table for 2 rounds. |
| Bonus  | Mob Programming | All cards change hands in the direction decided by the card player. |



### Want to contributes, suggest cards?

<img width="2000" src="./images/pull-request.gif" alt="Variables War Card Game">
   

## License

[Apache Version 2.0, January 2004](https://www.apache.org/licenses/LICENSE-2.0)

