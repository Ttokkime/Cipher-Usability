# Cipher Usability
This program will either encrypt or decrypt a message depending on the mode, key, and message inputted by the user. The modes being encrypt or decrypt and the key, which is used in the Ceasar cipher, being a number that represents the how much the letters' positions shifts in a message. 

### Project
My project:
- Imports the string library to access more characters.
- Shares an opening message with the user that describes what the program will do.
- Gets the user input (capital letters, lowercase letters, numbers, and keyboard symbols), the key, and the mode (encrypt or decrypt).
- Include a for loop that cycles through each character in the initialMessage.
- Include a conditional statement that allows for multiple word messages.
- Define and call a function called encryptOrDecrypt() that stores a conditional statement to encrypt or decrypt the initialMessage based on user input.
- Define and call a function called wraparound() that stores a conditional statement to adjust the position of any wraparound characters.
- Share the shiftedMessage with the user.

## File Overview

### ← README.md

README.md file provides an introduction on the program and an overview of what the program is capable of doing. 

### ← main.py
The code used for the Cipher Usability program.
