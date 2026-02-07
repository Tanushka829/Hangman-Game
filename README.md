# Hangman-Game

## Description
This is a basic Hangman game built in Python as part of my early learning journey.

The program selects a random word from a list of animals.
The user guesses one letter at a time.
The game tracks correct guesses and remaining lives.
The game ends when either all unique letters are guessed or lives reach zero.

---

## Features

- Random word selection
- Life tracking system
- Correct and incorrect guess detection
- Win condition based on unique letter matching
- Lose condition when lives reach zero

---

## Game Logic

1. A random word is selected.
2. The user enters one letter at a time.
3. If the letter exists in the word, it is stored in a correct letters list.
4. If the letter does not exist, a life is reduced.
5. The game checks after each input:
   - If all unique letters are guessed → User Wins
   - If lives reach zero → User Loses

---

## What I Learned

- Understanding problem better and breaking it in smaller logical steps
- Writing code step by step according to requirements
- Using multiple if-else conditions to control program flow
- Wrting every code block according to steps                                       
- I learned patience through multiples try and errors to make things work
  
  
---

## Future Improvements

- Improve duplicate guess handling
- Write more efficient code for win and lose detection
- Focus on full word rather than just corrected letters
- Replacing underscore with actual correct guessed letters
 
