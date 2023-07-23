# Password Manager

This repository contains a comprehensive password management system that enables users to securely store and access their usernames and passwords. The program offers two key functionalities: the ability to add new username-password pairs to a file and read the stored passwords from the file.

The implementation incorporates encryption techniques using the Fernet library from the cryptography module, ensuring that passwords are stored in a secure and encrypted format.

## Future Objectives

- Implement a robust feature that requires users to input a master key for decryption purposes, enhancing the overall security of the password manager.
- Enhance the encryption mechanism to effectively deny access to passwords in case of an incorrect master key, thereby ensuring maximum protection against unauthorized access.
