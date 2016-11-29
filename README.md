# scrabble_cheater
Step 1:construct a word list
Write the code to open and read the sowpods word file.
Create a list where each element is a word in the sowpods word file.
Note that each line in the file ends in a newline, which you'll need to remove from the word.

Step 2:get the rack
Write the code to get the Scrabble rack (the letters available to make words) from the command line argument passed to your script.
For example if your script were called `scrabble_cheater.py`, if you ran python scrabble_cheater.py RSTLNEI, RSTLNEI would be the rack.
Handle the case where a a user forgets to supply a rack.
In this case, print an error message saying they need to supply some letters, and then exit the program using the exit() function.
Make sure you are consistent about capitalization.

Step 3:find valid words
Write the code to find all words from the word list that are made of letters that are a subset of the rack letters.
There are many ways to do this, but here's one way that is easy to reason about and is fast enough for our purposes: go through every word in the word lishe word in a valid_words list.
Make sure you handle repeat letters: once a letter from the rack has been used, it can't be used again.

Step 4:scoring
Write the code to determine the Scrabble scores for each valid word, using the scores dictionary.
