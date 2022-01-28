# MyWordl Planning

## Functionalities

### Have a word dictionary and pick a random word from it at the beginning of each game
- keep the word secret and break each letter into a separate field/variable together with its index number
- words should be classified by level according to their number of characters

### Create a board with X number of columns and Y columns of rows
- X is equal to the number of letters in the word (by level)
- Y is equal to the number of tries to play the game

### Create a player keyboard or letter indicator to enter and/or highlight which letters have been entered, which are gray, yellow or green.

### Let the player enter a word each available turn and submit it once ready
- check if the word exists in the dictionary. If not, do not let the submission through.
- check which letters of the player's word are in the secret word:
     - if the letter is in the word but not with the same index, change background to yellow
     - if the letter is in the word with the same index, change background to green
     - if the letter is not in the word at all, change background to gray
- if all turns have been used, show a 'game over' message and give the option to try again.
- optional (with some special credits, give the option to view the secret word).
- if the player finds the word, show 'winner' message, show the number of turns used (z/y), and give the option to share the results.
- Give the option to continue playing a new level

### Share results
- include level number
- include number of tries used
- include visual map of solution

### Scoring and level unlocking
- on top of the summary of tries, it may be good idea to provide a star and/or coin system that allows to accumulate the required number of "points" to unlock the next level.


## Classes

### Secret word letter box class

#### Properties
- value: a letter from a selected word
- rightIndex: the correct index of the letter in the selected word
- visibility: hidden by default

#### Methods
- setLetter(): add a letter value from the selected word to the box

- setLetterIndex(): add the index of the letter in the selected word

- clearLetter()

- clearIndex()

### Input box class

#### Properties


#### Methods


### Keyboard button class

#### Properties


#### Methods


Test text from VSCODE web

addition from mobile browser

