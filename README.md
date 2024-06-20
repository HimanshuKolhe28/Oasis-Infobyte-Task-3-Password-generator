# Oasis-Infobyte-Task-3-Password-generator
This Python script generates a random password of a specified length using a combination of uppercase letters, lowercase letters, digits, and special characters.

Features:
generate_password(length):
Generates a random password of the specified length.
Uses string.ascii_letters (uppercase and lowercase letters), string.digits (digits 0-9), and string.punctuation (special characters) to create the character set.
Utilizes random.choice() to randomly select characters from the character set and concatenate them into a password string.
main():
Entry point of the script.
Prompts the user to input the desired length of the password.
Validates that the input is a positive integer.
Calls generate_password() to generate and display the password.
Handles exceptions for invalid input (e.g., non-integer or negative length).
Usage:
Run the script.
Enter a positive integer as the desired length for the password.
The script generates a random password containing a mix of letters, digits, and special characters.
Displays the generated password to the user.
GitHub:
The script is structured with clear functions and error handling for robustness.
Designed for generating secure passwords with a variety of characters.
Feel free to modify or integrate into applications requiring password generation functionality.
