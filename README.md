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

b. **IF** "ATTEMPT" is not an integer
    - Display "Pick a whole number between 1 and 10"
        CONTINUE to next iteration of the loop
     
c. **IF** "ATTEMPT" is < SECRET 
    - Display "Wrong! Number too low. Guess again"
    **Elif** "ATTEMPT" is > SECRET,
        - Display "Wrong! Number too high. Guess again"
        **ELSE** "ATTEMPT" = SECRET
            Display "Correct! You guessed it"
      **EXIT** REPEAT loop
      
4. **END**

## Peer Review Notes
**Reviewer:** Blessing Adeyemi

**Feedback:**
- Improve formatting of IF statements
- Show hints only after wrong guesses
- End loop only on correct guess

**Action taken:** cleaned algorithm and removed duplicate SECRET definition.
