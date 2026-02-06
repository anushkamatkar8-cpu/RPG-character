# RPG Character Generator 

This is a simple Python program that creates a character sheet for a role-playing game (RPG).
Users can enter a character name and assign three stats: **Strength, Intelligence, and Charisma**.
The program validates the input and generates a visual character sheet using filled and empty dots.

---

## Features

* Validates character name:

  * Must be a string
  * Cannot be empty
  * Must not contain spaces
  * Maximum 10 characters
* Validates stats:

  * Must be integers
  * Each stat must be between **1 and 4**
  * Total stat points must equal **7**
* Displays a formatted character sheet with visual stat bars

---

## How to Run

1. Make sure Python is installed.
2. Download or clone the repository.
3. Run the script:

```bash
python character_generator.py
```

4. Enter the requested inputs:

   * Character name
   * Strength
   * Intelligence
   * Charisma

---

## Example Output

```
Enter character name: ren
Enter strength (1-4): 4
Enter intelligence (1-4): 2
Enter charisma (1-4): 1

Character Sheet:

ren
STR ●●●●○○○○○○
INT ●●○○○○○○○○
CHA ●○○○○○○○○○
```

---

## Purpose

This project was created as a beginner Python exercise to practice:

* Functions
* Input validation
* String formatting
* Lists and loops

---

## Author

Anushka

---

