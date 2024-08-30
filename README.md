AES and RSA Encryption/Decryption Tool

Overview

This project provides a web-based tool for performing AES (Advanced Encryption Standard) and RSA (Rivest-Shamir-Adleman) encryption and decryption. It includes functionalities for both symmetric and asymmetric encryption, allowing users to secure their data using two of the most widely recognized cryptographic algorithms.


Features
AES Encryption/Decryption
Encrypt with AES: Users can input plaintext and encrypt it using AES with a predefined secret key.
Decrypt with AES: Users can decrypt ciphertext back into plaintext using the same secret key.
AES is a symmetric encryption algorithm, meaning the same key is used for both encryption and decryption. This tool uses a fixed key ('secretkey123') for simplicity, but in a real-world application, you would typically use a more secure key management strategy.


RSA Key Pair Generation
Generate RSA Key Pair: Users can generate a new RSA key pair with a choice of key lengths (1024 or 2048 bits).
Display Keys: The generated public and private keys are displayed in separate text areas.
RSA is an asymmetric encryption algorithm, which uses a pair of keys: a public key for encryption and a private key for decryption. This tool facilitates the creation of RSA key pairs for securing data or verifying identities.


How to Use

AES Encryption/Decryption:

Enter your plaintext in the "Input Text" area.
Click "Encrypt with AES" to obtain the encrypted output.
To decrypt, paste the encrypted text into the "AES Output" area and click "Decrypt with AES".
RSA Key Generation:

Select the desired key length from the dropdown menu.
Click "Generate key pair" to produce and display a new RSA public and private key.
Technical Details
AES Encryption/Decryption: Utilizes the CryptoJS library for performing AES operations. The AES key used is a simple static key for demonstration purposes.
RSA Key Generation: Utilizes the JSEncrypt library to generate RSA key pairs and perform encryption/decryption.

PUBLIC URL: http://127.0.0.1:5500/Index.html
