# Number Guessing Game - Pseudocode

## Project Author - Ireti George

## Peer Reviewer - Blessing Adeyemi

## Description - A simple number guessing game where the program selects a number from 1-10 and player plays till the secret number is guessed.

1. **Start**

2. Generate a random number and store it in SECRET
   Define SECRET as INTEGER
   SECRET = 1-10

3. REPEAT:

a. Display "Guess a number between 1 and 10"
Input field should read as "ATTEMPT"

b. IF "ATTEMPT" is not an integer:

    - Display "Pick a whole number between 1 and 10"
    - CONTINUE to next iteration of the loop
     
c.

    - IF ATTEMPT is less than SECRET:
      - Display "Wrong! Number too low. Guess again"
    - ELSE IF ATTEMPT is greater than SECRET:
      - Display "Wrong! Number too high. Guess again"
    - ELSE (ATTEMPT = SECRET):
      -Display "Correct! You guessed it"
      
   EXIT REPEAT loop


      
4. **END**





**Blessing's Feedback:**
- Improve readability/formatting for all IF-statements
- Whats the execution order of your IF statements?
- The hints to be given according to the task details is only if guess is too low or too high.
- The only thing that should trigger the end of loop is if guess is correct


**Action taken:** cleaned algorithm and removed duplicate SECRET definition.

