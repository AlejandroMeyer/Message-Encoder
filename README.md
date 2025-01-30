# Message Encryption and Decryption with Static Key

This project provides two Python scripts for message encryption and decryption. The encryption process uses a randomly generated key, and the decryption process uses a static key stored in a file (`key.txt`). The scripts ensure that the same key is used for all operations until a new key is generated.

## Features

- **Generate Key**: Generate and store a random key for encrypting messages.
- **Encrypt Message**: Encrypt a message using the generated key and a predefined alphabet.
- **Decrypt Message**: Decrypt an encrypted message using the stored key from the file.

## How It Works

1. **Key Generation**: The `generate_key()` function generates a random key based on the length of the input message and stores it in a file (`key.txt`).
2. **Encryption**: The `encrypt_message()` function encrypts a message by combining each character of the message with the corresponding character in the key using modular arithmetic.
3. **Decryption**: The `decrypt_message()` function decrypts an encrypted message using the key stored in `key.txt`.

## Installation

1. Clone the repository or download the files:
   ```bash
   [git clone https://github.com/AlejandroMeyer/Message-Encoder.git]
