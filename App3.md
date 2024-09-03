# App 3. Match Madness now in Telegram!

One of the tasks in the popular language learning app Duolingo is to match words. The app shows two columns of words, where words in the left columns are in one language, and words from the right columns are in another language. 
The task is to choose a word from the left column and its translation from the right column. There are two kinds of this task:

- a "regular" one, where the learner is not restricted in time, and the sets of words are fixed;
- "match madness" kind, where the task is to maximize the number of correct pairs, and properly matched words are replaced with the new ones.

The application is a telegram bot that allows for adding pairs of words and practicing in word matching in both modes.

## High-level usage scenarios

The following high-level scenarios of interaction with the bot must be supported:

1. A user adds a pair of words, or edits/removes one of the added previously. An option to search the words would be nice.
2. A user starts a regular word match task. The application will show 1-3 screens with 4-5 word pairs. Once the user completes matching one set of pairs, he is shown a new one.
   The application must choose the appropriate words to show and to group. The decision shall be based on some word ranking, e.g. it should choose those words that have not been shown recently,
 or those where the user made a mistake earlier. It would be nice to show similar words on the same page to make it more challenging (e.g. show "sheep" and "ship" with their tanslations on the same page).
3. A user starts a "match madness" task. In this mode, every matched pair is immediately replaced by a new pair, and the time is limited.

