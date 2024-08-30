# App 1: Hanabi game now in Telegram!

Hanabi is a cooperative board game. A brief description:

> Hanabi is a cooperative game in which players have to place the cards on the table in the right order.
> The card deck consists of five different colors of cards, numbered 1–5 in each color.
> For each color, the players try to place a row in the correct order from 1–5.
> Sounds easy, right?
> Well, not quite, as in this game you hold your cards so that they're visible only to other players and not to you.
> To assist other players in playing a card, you must give them hints regarding the numbers or the colors of their cards.
> Players must act as a team to avoid errors and to finish the fireworks display before they run out of cards.
>
> https://boardgamegeek.com/boardgame/98778/hanabi

This application is a Telegram bot that allows for playing Hanabi with your friends in Telegram.

# High-level requirements

Suppose that a group of N friends want to play Hanabi over Telegram. The following high-level scenarios of their interaction with the bot must be supported:

1. One of the friends asks the bot to generate the invitation code and other friends pass the code to the bot to join the game.
2. Every user must be able to:
   - see the played card decks on the table and optionally see the discarded cards
   - see the cards in the "hands" of other users
   - see the backs of the cards in their own "hand" with the received hints about them
   - see whose turn it is now and how many hints are available
   - decide on the action in their turn: play/discard/give hint
   - choose the card to play/discard or the card to give hint about
4. The bot must be able to validate the actions from the users, update the played and discarded cards, draw cards for the players.
   
