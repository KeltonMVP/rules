---
icon: material/cards-playing
---

<figure markdown="span">
  ![Blackjack Casino](/images/wiki/general/Blackjack_casino.png){ width="450" }
  <figcaption>Blackjack Casino</figcaption>
</figure>

The famous Caligulas Las Venturas casino hosts two major gambling games preferred by players on B-Zone servers, namely **Blackjack** and **Poker Dice**



# Blackjack

<figure markdown="span">
  ![Blackjack table](/images/wiki/general/Blackjack_table.png){ width="450" }
  <figcaption>Blackjack table</figcaption>
</figure>

For players addicted to gambling games, B-Zone servers provide a Blackjack system in the Caligulas Casino business in Las Venturas.<br>
The blackjack tables are located at the end of the interior, numbering 12.

## GEneral Characteristics
- You can play blackjack if you have a minimum level 3.
- There can be at most 7 players simultaneously at a single table.
- The game will start only when there are at least 2 players at a table.
- To be able to join a table you need a minimum level 3 and the minimum entry amount, which is displayed at each table.
- There are a total of 12 tables, each with its minimum entry amount.
    - Table 1: **$10,000** buy-in.
    - Table 2: **$50,000** buy-in.
    - Table 3: **$100,000** buy-in.
    - Table 4: **$200,000** buy-in.
    - Table 5: **$400,000** buy-in.
    - Table 6: **$800,000** buy-in.
    - Table 7: **$1,000,000** buy-in.
    - Table 8: **$2,000,000** buy-in.
    - Table 9: **$3,000,000** buy-in.
    - Table 10: **$4,000,000** buy-in.
    - Table 11: **$5,000,000** buy-in.
    - Table 12: **$6,000,000** buy-in.
- From the pot won at the end of a round, 95% of the money will be received by the winning player or players, 4.9% of the money will be deleted from the server and 0.1% of the money will go into the business safe.
- Real played hours will accumulate during the blackjack game.
- Players who do not choose any option for 60 seconds will be removed from the table for AFK.
- This business has an interior.
- Leaving the table can also be done through the LEAVE button.


## General Blackjack Rules
- Players will not have to beat the dealer as is usual, but must beat all players at that table to take the prize.
- Reach a score as close to 21 as possible with the cards you have in your hand WITHOUT exceeding 21.
- When exceeding the score of 21, you have gone BUST and will lose the game round.
- Cards are shuffled randomly.
- Cards 2, 3, 4, ..., 10 offer the score written on the card.
- Cards J, Q, K offer a score of 10.
- The Ace card will offer either a score of 1 or a score of 11 automatically depending on what is more beneficial for the player.
- At the start of the game, it is checked if there is a player who does not have enough money to continue playing; if there is, they will be removed. If after their removal there are not at least two players who can continue the game, it will not start.
- The game will start with the first player at the table; players are ordered from left to right at the table; a red arrow will appear above the name of the player whose turn it is.
- Players cannot see each other's cards and scores, except when a player goes BUST (exceeds the score of 21). Then their cards will be shown to all players, including their score.
- To simplify the game there is no SPLIT mechanic, as exists in a classic blackjack game.


## Game Decisions
The game will consist of 2 simple decisions that the player must make:

### HIT
Will be used when the player wants to receive another card from the deck.

### STAND
Will be used when the player no longer wants to receive cards; the player will no longer be able to request cards in that round if they pressed STAND.<br>
To give STAND you must have a card score of at least 12.<br>
If a player does not press any option for 30 seconds, STAND will be given automatically. Exception when the score is below 12, if it is below 12, the server will automatically give HIT, and after that will give STAND, provided that the score has not exceeded 21.


## Determining the Winner
The winner will be calculated when there are no more players eligible to receive cards (all have either gone BUST, or have given STAND, or only one player remains who has not gone BUST among all players).

## Specific Commands
### /blackjack
Through this command you will be able to join or leave the blackjack table.<br>
The command is executed successfully only if you are inside the Caligulas Casino business, near one of the blackjack tables.<br>
*Syntax: /blackjack*



# Poker Dice

## General Characteristics
* The overall idea of ​​this system is to provide a more interactive and competitive gaming experience than a normal dice game based solely on luck.
* Instead of rolling once and hoping for the best, Poker Dice is built around multiple stages, improving your hand, making betting decisions, and properly resolving the showdown between all players seated at the table.
* This system is designed to feel closer to a real table game, where players not only have to rely on luck, but also know when to bet, when to stay in the game, when to fold, and when to go all-in.
* Poker Dice can be played at **Caligulas (Business ID 114)**, which now hosts both Blackjack and Poker Dice.
* A total of 4 Poker Dice tables have been added, each with its own stake level:
* Table 1 - Minimum Buy-In: **$1,000** / Ante: **$100**.
* Table 2 - Minimum Buy-In: **$10,000** / Ante: **$1,000**.
* Table 3 - Minimum Buy-In: **$100,000** / Ante: **$10,000**.
* Table 4 - Minimum Buy-In: **$1,000,000** / Ante: **$100,000**.
* These 4 tables are designed for different stake levels, allowing both low and high stakes players to participate according to their bankroll.
* A full round of Poker Dice is played in several stages:
* **First Roll:** During the first roll, players shake hands and decide which dice they want to keep, with the option to keep up to 2 dice before moving on.
* **Betting Round:** A full round of betting takes place where players can choose to check, call, raise, fold or go all-in.
* **Second Roll:** Players are given a second roll to improve their hand.
* **Showdown:** The final showdown decides the winner, with all remaining hands only revealed at the end of the round.
* **Winning Hand Hierarchy:** Five of a Kind > Four of a Kind > Full House > Straight > Three of a Kind > Two Pair > One Pair > Bust / High Card / Nothing
* The ante is deducted instantly at the start of the round, meaning that every player participating in the hand contributes to the pot from the start.
* Hands remain hidden until showdown, meaning that players must make betting decisions without seeing the complete hands of others at the table.
* Players who fold are immediately out of the hand, while players who go all-in can still compete for the portion of the pot they are eligible for.
* Any additional money that has not been matched is automatically returned as needed, while side pots and split pots are resolved correctly at showdown.
* The Poker Dice system also supports the correct handling of side pots, split pots and all-in situations, following the rules of No-Limit Poker.
* Players will be able to clearly track whose turn it is, what actions are available, what stage the round is in and the result at showdown.
* Winning payouts are subject to standard casino tax rules, meaning that a small percentage of each pot won is deducted before the final payout is awarded, while unmatched money returned is not taxed.
<p style="color: rgb(231, 76, 60); font-weight: bold; font-style: italic;">Players are strongly encouraged to understand the Poker Dice system before playing. Because the game uses your own money and follows full table game mechanics, not understanding the hand hierarchy or betting flow can quickly lead to losing your money.</p>
