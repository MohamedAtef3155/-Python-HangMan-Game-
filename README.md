# HangMan game in python

## Game instructions
1. Player one we call it (Main player) write a word that other player doesn't see it.

2. words are replaced by dashes and space between them (- - - - - -).

3. other player (player2) try to guess the word letter by letter.

4. if he guesses correct letter it replaces dashes space weather its one or more dash.

5. if he guesses wrong letter he kill one part of the Hangman's 6 Parts which are (Head,Hand2,Hand1,Body,Leg2,Leg1)
    so basically he Has 6 Trials to gues the word.

6. if player2 get the word he wins otherwise the main play wins.


# Notes 
1. Main Code in Main code block file.

2. I created two functions in Creating functions files:
   First Function takes word input from the main player and validate on it and it has two parameters or args the (max_word_length,trials) and their default values are (10,6)
   Second Function validate on player2 guess and run the game till main player or player2 wins.
   
3. Running the functions file is sample for playing the code using functions only.

4. the code is a bit long because there are different print statements i could make it one print statement but I didn't to make the game more fun 

# output sample 

![hangman output sample](https://github.com/MohamedAtef3155/-Python-HangMan-Game-/assets/126327548/7d0389a8-6af8-414d-9007-93ba6b43a118)
