# Character Creation 
---


## Objective
---

Must create the function for the game mechanic which will allow users to create their characters. Users will have a choice of name, class, age, and a catchphrase. Let's assume users give valid answers for all input statements. The code is responsible for making sure all inputed answers are reformatted to a standard output.


## Features
---

Prompt the user for a name 
-	The name should be saved with the first letter capitalized, and every other letter lower case in the name (E.G. Christina torres)

Prompt the user for an age
-	Cast the age to an integer
-	Calculate the character's birth year

Prompt the user for a character class
-	Save the class in a string with all uppercase characters (E.G. KNIGHT)

Prompt the user for a character catch phrase


Print the results to the terminal
-	In a single line output, show the saved characters name, year of birth, and class
-	In another line print the character catchphrase reversed (e.g. “Ahoy Matey!” -> “!yetaM yohA”)

## **Example Output:**
---

**Input**
```What is your full name?: arthur

What is your age?: 22

What is your class? Knight, Warrior, Healer?: knight

What is your catchphrase?: Let's go
```
**Output**
```
Arthur, 2001, KNIGHT

og s'teL!
```