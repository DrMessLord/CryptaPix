# CryptaPix 🖼️🔒

CryptaPix is a secure image steganography tool developed using Python, enabling users to conceal confidential text messages within image files using advanced cryptographic techniques.

## Overview
CryptaPix offers a seamless solution for covert communication, allowing users to embed encrypted messages into image files without altering their visual appearance. Leveraging advanced LSB steganography and AES encryption, CryptaPix ensures robust protection against unauthorized access and data tampering.

## Features
- **Advanced Steganography:** Utilizes sophisticated LSB steganography techniques to embed encrypted messages within image files, ensuring stealthy communication.
- **AES Encryption:** Encrypts embedded messages using AES encryption with a key length of 256 bits, providing strong data security and confidentiality.
- **MD5Sum Verification:** Implements MD5Sum checksum for file integrity verification, enabling users to validate the authenticity of embedded messages.
- **Cross-Platform Compatibility:** Built using Python, CryptaPix is compatible with Windows, macOS, and Linux operating systems, offering flexibility and accessibility.
- **User-Friendly Interface:** Provides an intuitive and user-friendly interface for easy operation, making it suitable for users of all skill levels.

## Usage
1. Clone or download the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the CryptaPix script using Python: `python cryptapix.py`.
4. Follow the on-screen instructions to select an image file and embed your confidential message securely.

## Demo
![CryptaPix Demo](demo.gif)

## Credits
This project was inspired by the [Image-Steganography-Cyber-Security-Project](https://github.com/bennetbvarghese/Image-Steganography-Cyber-Security-Project) by Bennet B Varghese.

## Dependencies
- **Python:** Programming language used for development.
- **Pillow:** Python Imaging Library (PIL) fork for image processing.
- **pycryptodome:** Python cryptographic library for AES encryption.
- **pytest:** Testing framework for unit testing.

## Contribution
Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## Disclaimer
CryptaPix is intended for educational and research purposes only. It is the responsibility of the user to comply with all applicable laws and regulations regarding the use of steganography and encryption software.

🔐 Secure your data with CryptaPix! 🖼️
