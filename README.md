How It Works:
Input:

The user inputs the message they want to encrypt or decrypt.
They also input a shift value (how many positions each letter should be shifted).
The user specifies the mode (encrypt or decrypt).

Processing:

The program loops through each character in the message.
It checks if the character is uppercase or lowercase.
The character is shifted based on the ASCII value and wrapped around using modular arithmetic.
Non-alphabet characters (e.g., spaces, punctuation) remain unchanged.

Output:

The program outputs the encrypted or decrypted message based on the selected mode.

Example Usage:

Encrypt:
Input: "HELLO WORLD", Shift: 3
Output: "KHOOR ZRUOG"

Decrypt:
Input: "KHOOR ZRUOG", Shift: 3
Output: "HELLO WORLD"

You can run this program in a Python environment to perform Caesar Cipher encryption and decryption.
