``` mermaid
graph TD
    A[Begin the Amazing Number game.] --> B(Player Guesses a number)
    B --> C{Computer asseses the number and compares it to its randomly generated number}
    C -->|If the Players number is higher than the computers number.| D[The computer outputs, _**Too High**_]
    C -->|TIf the Players number is lower than the computers number.| E[The computer outputs, _**Too Low**_]
    C -->|If the Players number is equal to the computers number.| F[The computer outputs, **_You Win!!_** Then dispenses 50 dollars.]
```
