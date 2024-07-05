# WindowsLinuxSSH
This project involves setting up a secure SSH connection between a Windows host and a Linux virtual machine (VM), and implementing data encryption and decryption using Python with the help of cryptography library.
## Project Overview
This project focuses on setting up a secure SSH connection between a Windows host and a Linux virtual machine (VM), and implementing data encryption and decryption using Python with the `cryptography` library.

## Features
- **SSH Connection Setup:** Securely connect between a Windows host and a Linux VM using SSH.
- **Data Encryption:** Encrypt sensitive data using the `cryptography` library's `Fernet` encryption.
- **Data Decryption:** Decrypt encrypted data to retrieve original information securely.

## Requirements
- Windows host machine with SSH client capabilities.
- Linux virtual machine with SSH server enabled.
- Python 3.x installed on both systems.
- `cryptography` library installed (`pip install cryptography`).

## Usage
1. **SSH Setup:**
   - Ensure SSH server is running on the Linux VM.
   - Use SSH client on Windows to establish a connection to the VM.

2. **Encryption and Decryption:**
   - Use the provided Python scripts (`encrypt.py` and `decrypt.py`) to encrypt and decrypt files.
   - Store the encryption key securely (`thekey.key`) for decryption.

## File Structure
- `encrypt.py`: Python script for encrypting files using `Fernet` encryption.
- `decrypt.py`: Python script for decrypting files encrypted with `Fernet`.
- `thekey.key`: Encryption key file used by both encryption and decryption scripts.
- `voldemort.py`: Sample file (replace with actual files to encrypt/decrypt).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Execution

![image](https://github.com/Shankhosuvro-G/WindowsLinuxSSL/assets/98182979/7609298d-e144-4713-b3bd-91fa6131b38d)

Successfully connected to the LInux VM using ssh from Windows host.

![image](https://github.com/Shankhosuvro-G/WindowsLinuxSSL/assets/98182979/3aee7151-91d6-463b-abf8-4469b4e2367d)

Executed the encrypting algorithm and all the contents of the files present in the directory are encrypted.

![image](https://github.com/Shankhosuvro-G/WindowsLinuxSSL/assets/98182979/02b54c2a-d5ad-4b6f-91cf-da72efb316b7)

Executed the decrypting algorithm to decrypt the file contents present in the directory.






