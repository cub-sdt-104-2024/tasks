# Travel Expense Accounting is now in Telegram!

Imagine a group of people A, B, C, D who are going on a long hike. Suppose that A is a group leader and it booked a transfer for the whole group and paid $100. 
Suppose that A and B prefer ready-to-eat food and B bought food for them and paid $50. 
Suppose that C and D prefer cooking their dishes from the raw ingredients, and C bought some for $20, while D bought other ingredients for $50. 

The application is a Telegram bot that allows for recording the expenses and finally displaying who needs to pay whom. 

## High-level scenarios

The following high-level scenarios of interaction with the bot must be supported:

1. One of the friends asks the bot to generate the event code and other friends supply the code to the bot to join the event.
2. One of the event participants records their expenses and specifies the friends with whom the expenses are split.
3. The owner finalizes the event and bot sends out messages to the participants with the amount to pay and the payment recipient. 
