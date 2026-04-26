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
<img width="1086" height="296" alt="Screenshot 2026-04-26 at 11 26 19 AM" src="https://github.com/user-attachments/assets/6f0763e6-662c-4e03-9cf3-1fecc999f18a" />
<img width="998" height="264" alt="Screenshot 2026-04-26 at 11 19 41 AM" src="https://github.com/user-attachments/assets/455df7d0-7157-4f3a-973e-861bb441ac77" />



## Author
Salma Aldhoayan
