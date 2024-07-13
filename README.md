# Vigenère Cipher and Substitution Cipher Analysis

This Python script implements functions to encrypt and decrypt text using the Vigenère cipher, perform frequency analysis, and cryptanalyze substitution ciphers. It includes methods to predict encryption mappings, find password lengths for Vigenère ciphers, and decrypt encrypted text.

## Substitution Cipher Functions

### `process_file_content(filename)`
- Reads a text file and removes all non-lowercase alphabetic characters.
  
### `letter_distribution(s)`
- Counts the occurrences of each lowercase letter in string `s`.

### `sort_list_of_tuples(tuples_list)`
- Sorts a list of tuples by the second element in descending order.

### `substitution_encrypt(s, d)`
- Encrypts string `s` using substitution cipher mappings from dictionary `d`.

### `substitution_decrypt(s, d)`
- Decrypts string `s` using the reverse mappings of dictionary `d`.

### `cryptanalyse_substitution(s)`
- Predicts the substitution dictionary used to encrypt string `s`.

### `check(encryption_mapping, generated_mapping)`
- Compares two mappings (`encryption_mapping` and `generated_mapping`) to validate the accuracy of decryption.

## Vigenère Cipher Functions

### `vigenere_encrypt(s, password)`
- Encrypts string `s` using the Vigenère cipher with the given `password`.

### `vigenere_decrypt(s, password)`
- Decrypts string `s` using the Vigenère cipher with the given `password`.

### `collision_freq(s1, s2)`
- Calculates the collision frequency between two strings `s1` and `s2`.

### `rotate_compare(s, r)`
- Compares the collision frequency between `s` and its rotated version by `r` positions to determine the length of the Vigenère cipher password.

### `cryptanalyse_vigenere_findlength(s)`
- Determines the length of the Vigenère cipher password used to encrypt string `s`.

### `divide(encrypted_text, r)`
- Divides the encrypted text into `r` substrings for Vigenère cipher analysis.

### `cryptanalyse_vigenere_afterlength(s, k)`
- Given encrypted string `s` and password length `k`, finds the Vigenère cipher password.

### `cryptanalyse_vigenere(s)`
- Cryptanalyzes the Vigenère cipher used to encrypt string `s` and outputs the decrypted plaintext along with the password.

## Usage

1. **Clone the Repository**: Clone this repository to your local machine.
   

