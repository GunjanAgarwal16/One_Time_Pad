# One_Time_Pad
One-Time Pad (OTP) encryption is a powerful cryptographic method that ensures full secrecy of sensitive information. This project implements a Python program that enables users to encrypt and decrypt plaintext messages using the OTP algorithm. By generating random keys for each encryption, the program offers absolute secrecy and prevents unauthorized access to the encrypted messages.

## Table of Contents
* Introduction
* Features
* Installation
* Usage
* Contributing


## Introduction
In today's connected world, protecting sensitive data is crucial, and encryption plays a vital role in ensuring confidentiality. The OTP encryption algorithm, despite being over a century old, offers perfect secrecy when used correctly. It is still employed in secure communication systems, including military and diplomatic channels.

This project aims to demonstrate the importance of secure communication and the significance of encryption in safeguarding private data. By implementing OTP encryption and decryption, users can learn the fundamentals of secure communication and understand the role of robust encryption methods.

## Features
* User-friendly interface for inputting plaintext messages
* Random key generation for each encryption
* Encryption of plaintext using the OTP algorithm
* Decryption of ciphertext using the same key
* Absolute secrecy and prevention of unauthorized access

## Installation
To use the One-Time Pad encryption and decryption program, follow these steps:

1. Clone the repository:
    git clone https://github.com/your-username/one-time-pad.git
2. Navigate to the project directory:
   cd one-time-pad
3. Ensure you have Python 3 installed on your system. If not, you can download it from the official Python website.

4. Install the required dependencies:
   pip install -r requirements.txt
   
## Usage
1. Run the program:
python otp.py

2. The program will display a menu with options for encryption, decryption, and exiting.

3. To encrypt a message:
* Choose option 1 from the menu.
* Enter the plaintext message when prompted.
* The program will generate a random key and encrypt the message using the OTP algorithm.
* The encrypted message and the key will be displayed.
4. To decrypt a message:

* Choose option 2 from the menu.
* Enter the encrypted message when prompted.
* Enter the key used for encryption.
* The program will decrypt the message and display the plaintext.
5. You can repeat the encryption and decryption process with different messages or exit the program by choosing the corresponding option from the menu.


## Contributing
Contributions to this project are welcome. If you have suggestions for improvements or would like to add new features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contribution: git checkout -b feature/your-feature.
3. Make your changes and commit them: git commit -m 'Add feature'.
4. Push the changes to your branch: git push origin feature/your-feature.
5. Submit a pull request explaining your changes.    
    
