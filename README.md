# Secure Chat Simulation

## Project Description
This project implements a secure chat simulation using Diffie-Hellman for key exchange, AES for encryption, and HMAC for message integrity and authentication.

## Features
- Secure shared key generation using Diffie-Hellman
- Message encryption using AES
- Message integrity verification using HMAC
- Tampering detection (modified messages are rejected)

## Technologies Used
- Python
- cryptography library

## How It Works
1. Alice and Bob generate a shared key using Diffie-Hellman.
2. Alice encrypts a message using AES.
3. An HMAC is created for integrity verification.
4. Bob verifies the HMAC.
5. If valid, Bob decrypts the message.

## How to Run
1. Install the required library:
   pip install cryptography

2. Run the program:
   python secure_chat.py

3. Enter a message when prompted.

## Example Output
- Encrypted message is displayed
- HMAC is shown
- Decrypted message is printed if verification succeeds

## Security Concepts
- Diffie-Hellman: Secure key exchange
- AES: Symmetric encryption
- HMAC: Ensures message integrity and authenticity

## Screenshots
(Add your screenshots here)

## Author
Salma Aldhoayan
