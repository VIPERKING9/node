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

Installation

Step 1. Clone the repository:
https://github.com/VIPERKING9/node.git
Step 2. open the encryption directory on the code editor terminal using
 cd encryption-app
 Step 3. Install dependencies:
  npm install
  step 4. Run the application:
   npm start
   Step 5. Open in browser:
   Navigate to the browser:http://127.0.0.1:5500/Index.html

   Usage

   Encrypting a Message:

. Enter your message in the text area.

. Click the "Encrypt" button.

The encrypted message will be displayed in the output field.


Decrypting a Message:
. Enter the encrypted message and AES key.

. Click the "Decrypt" button.

The decrypted message will be displayed in the output field.

Contributing:
Contributions are open Please open an issue or submit a new pull request for any improvements or suggestions.


   Steps to Contribute
Step 1. Fork the repository.

Step 2. Create a new branch (git checkout -b feature-branch).

step 3. Make your changes and commit them (git commit -m 'Add new feature').

step 4. Push to the branch (git push origin feature-branch).

Step 5. Open a pull request.
