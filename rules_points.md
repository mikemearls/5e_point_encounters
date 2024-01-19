# How to Build Encounters Using Points
This system complements CR and tries to find an easier way to scale encounters up and down.
## Encounter Budgets in Points
A combat encounter has a points budget based on the number of characters in the party and the desired level of difficulty.

| Difficulty | Expected Party Hit Point Loss | Points Per Character |
| ---------- | ------------------------------| -------------------- |
| Easy | 10% | 0.5 |
| Moderate | 25% | 1 |
| Tough | 50% | 2 |
| Deadly | 75% | 3 |
| Lethal | 100% | 4 |

## Monster Point Values
For existing monster, convert Challenge Rating (CR) to a point cost based on a creature's CR relative to the party's level.

| Monster CR vs. Party Level | Point Value |
| -------------------------- | ----------- |
| CR = Party Level + 5 | 24 |
| CR = Party Level + 4 | 16 |
| CR = Party Level + 3 | 12 |
| CR = Party Level + 2 | 8 |
| CR = Party Level + 1 | 6 |
| CR = Party Level | 4 |
| CR = Party Level - 1 | 3 |
| CR = Party Level - 2 | 2 |
| CR = Party Level - 3 | 1.33 |
| CR = Party Level - 4 | 1 |
| CR = Party Level - 5 | 0.5 |

I'd worry more about that ugly 1.33 value if I knew these points would change as I test this system and get feedback from DMs and designers.

## Example
Suppose you have a party of 4 adventurers at level 5 each. If you wanted to plan a Tough encounter, 
you would have a budget of 2 points per character, for a total of 8 points. This means you could have them 
encounter any of the following:
  * A single CR 7 creature (party level 5 + 2)
  * Two CR 5 enemies
  * Eight CR 1 monsters
