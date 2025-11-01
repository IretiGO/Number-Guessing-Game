# Number Guessing Game - Pseudocode

## Project Author - Ireti George

## Peer Reviewer - Blessing Adeyemi

## Description - A simple number guessing game where the program selects a number from 1-10 and player plays till the secret number is guessed.

1. Start
2. Generate a random number and store it in SECRET
   Define SECRET as INTEGER
   SECRET = 1-10

3. REPEAT loop:

a. Display "Guess a number between 1 and 10"
Input field should read as "attempt"

b. IF "attempt" is not an integer:

    - Display "Pick a whole number between 1 and 10"
    - CONTINUE to next attempt

e. Else:

    IF "attempt" is < SECRET:
        - Display "Wrong! Number too low. Guess again"
    Elif "attempt" is > SECRET:
        - Display "Wrong! Number too high. Guess again"
    ELSE
        - "attempt" = "Correct! You guessed it"
        EXIT REPEAT loop

4. END

#Suggestions

1. Improve readability/formatting for all IF-statements
2. Whats the execution order of your IF statements?
3. The hints to be given according to the task details is only if guess is too low or too high.
4. The only thing that should trigger the end of loop is if guess is correct
