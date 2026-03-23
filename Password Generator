# ASK USER FOR PASSWORD LENGTH
# CREATE LETTER LIST USER CAN USE
# ALSO ADD IN A NUMBER'S LIST AND A SYMBOLS LIST
# THEN COMBINE THE LIST AND HAVE SCRIPT RANDOMLY CHOOSE CHARACTERS
# LASTLY BUILD THE PASSWORD AND PRINT THE PASSWORD

# IMPORT RANDOM GIVES THE OPTION TO RANDOMIZE CHARACTERS
# IMPORT STRING RANDOMIZES LETTERS, NUMBERS OR SYMBOLS
import random
import string

# VALIDATION LOOP
while True:
    length = int(input("Length of password:"))
    # CHARACTER LIST
    if length < 12:
        print("Your password is too short. Try again!")
    else:
        break
characters = string.ascii_letters + string.digits + string.punctuation
password = ""
# LOOP
for i in range(length):
    password += random.choice(characters)
print(f"Final password: {password}")

# IN THIS MINI PROJECT, I CREATED A SIMPLE PASSWORD GENERATOR SCRIPT
# USING IMPORTS, STRINGS, AND LOOPS. THE USER TYPES HOW LONG THEY WANT THEIR PASSWORD
# TO BE AND THE SCRIPT GENERATES THAT PASSWORD USING LETTERS, SYMBOLS AND NUMBERS.