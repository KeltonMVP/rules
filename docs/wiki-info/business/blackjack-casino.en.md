# Blackjack Casino

<figure markdown="span">
  ![Blackjack Casino](/images/wiki/general/blackjack_casino.png){ width="450" }
  <figcaption>Blackjack Casino</figcaption>
</figure>

<figure markdown="span">
  ![Blackjack table](/images/wiki/general/blackjack_table.png){ width="450" }
  <figcaption>Blackjack table</figcaption>
</figure>

For players addicted to gambling games, B-Zone servers provide a Blackjack system in the Caligulas Casino business in Las Venturas.

The blackjack tables are located at the end of the interior, numbering 12.

## Characteristics

- You can play blackjack if you have a minimum level 3.
- There can be at most 7 players simultaneously at a single table.
- The game will start only when there are at least 2 players at a table.
- To be able to join a table you need a minimum level 3 and the minimum entry amount, which is displayed at each table.
- There are a total of 12 tables, each with its minimum entry amount.
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

Will be used when the player no longer wants to receive cards; the player will no longer be able to request cards in that round if they pressed STAND.

To give STAND you must have a card score of at least 12.

If a player does not press any option for 30 seconds, STAND will be given automatically. Exception when the score is below 12, if it is below 12, the server will automatically give HIT, and after that will give STAND, provided that the score has not exceeded 21.

## Determining the Winner

The winner will be calculated when there are no more players eligible to receive cards (all have either gone BUST, or have given STAND, or only one player remains who has not gone BUST among all players).

## Specific Commands

### /blackjack

Through this command you will be able to join or leave the blackjack table.

The command is executed successfully only if you are inside the Caligulas Casino business, near one of the blackjack tables.

*Syntax: /blackjack*
