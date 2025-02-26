# SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY

## Overview

The project focuses on embedding sensitive information, such as text or binary data, into digital images in an imperceptible manner using OpenCV's steganography capabilities. The goal is to provide a secure means of transmitting sensitive data without raising suspicions.

Ensure these packages are installed in your environment before proceeding.

## Installation

You can install the required packages using pip:

```sh
pip install opencv-python
```

## Usage
## 1. Encrypting a Message
To hide a secret message in an image:
```sh
python encrypt.py
```

The script will ask for the image file (mypic.jpg).
Enter the secret message you want to hide.
Provide a password for security.
The encrypted image is saved as encryptedImage.jpg.
The password is stored in key.txt.

## 2. Decrypting a Message
To retrieve the hidden message from the encrypted image:
```sh
python decrypt.py
```

Steps:
The script reads encryptedImage.png.
You must enter the correct password.
If the password matches, the hidden message is displayed.
If the password is incorrect, access is denied.

## File Descriptions
1. encrypt.py - Script to embed a secret message into an image.
2. decrypt.py - Script to extract the secret message from the image.
3. mypic.jpg - Original image used for encryption.
4. key.txt - Stores the password required for decryption.
5. encryptedImage.png - Image containing the hidden message.

## Features
1. Multi-Layer Encryption: Combines multiple encryption layers to enhance data security.
2. User-Friendly Interface: Built with a GUI for easy interaction between users and embedded data.
3. Advanced Error Detection: Implements mechanisms to ensure accurate retrieval of hidden information even after multiple iterations.

## Conclusion
This project represents a significant step forward in secure data transmission by leveraging steganographic methods with OpenCV. While current implementations address basic security concerns, ongoing research and development will ensure continued advancements to protect sensitive information effectively.
