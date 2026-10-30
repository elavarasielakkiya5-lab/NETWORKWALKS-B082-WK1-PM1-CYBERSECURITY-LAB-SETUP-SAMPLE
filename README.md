📌 Project Overview

This project provides a secure way to transfer and store files using encryption. It helps protect sensitive files from unauthorized access and verifies file integrity during transfer.

❗ Problem Statement

Transferring files over a network can expose sensitive information to unauthorized users. Files may also be modified or accessed without permission. This project aims to improve file security through encryption and integrity verification.

💡 Solution

This project encrypts files before storing or transferring them. It uses AES encryption to protect file contents and HMAC verification to help detect unauthorized modifications.

✨ Key Features

- Secure file encryption and decryption.
- File upload and download functionality.
- AES-based file protection.
- HMAC-based file integrity verification.
- Flask-based web interface.
- Secure storage of encrypted files.

🛠️ Technologies Used

- Python
- Flask
- AES Encryption
- HMAC
- HTML

⚙️ How It Works

1. The user selects a file for upload.
2. The file is encrypted before secure storage.
3. The encrypted file is stored on the server.
4. The user can download the encrypted file.
5. The file can be decrypted using the appropriate key.
6. HMAC verification helps check whether the file has been modified.

🚀 How to Run the Project

1. Clone or download this repository.

2. Install Python on your system.

3. Install the required dependencies:
   
   pip install -r requirements.txt

4. Generate or configure the required encryption key.

5. Start the Flask application:
   
   python app.py

6. Open your browser and visit:
   
   http://127.0.0.1:5000

7. Use the web interface to upload and download files.

🎯 Project Objective

The main objective is to improve file confidentiality, protect stored data, and detect unauthorized file modifications using encryption and integrity verification.

🔮 Future Enhancements

- User authentication and access control.
- Secure key management.
- Large-file chunking.
- Resumable file transfers.
- Secure network communication.
