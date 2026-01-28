# 🔐 Caesar Cipher - Encryption Tool

[![Language: C](https://img.shields.io/badge/Language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Overview
A robust implementation of the classic **Caesar Cipher**, a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down the alphabet. This project showcases fundamental concepts of cryptography, command-line argument parsing, and ASCII manipulation in C.

## 🚀 Features
- **Dynamic Key Support**: Accepts any non-negative integer as a rotation key via command-line arguments.
- **Case Preservation**: Correctly encrypts both uppercase and lowercase letters while maintaining their original case.
- **Non-Alphabetic Integrity**: Leaves numbers, spaces, and punctuation marks unchanged.
- **Input Validation**: Includes comprehensive checks for correct command-line usage and key format.

## 🛠️ Technical Skills Demonstrated
- **Command-Line Interface (CLI)**: Handling `argc` and `argv` for user input.
- **Data Type Conversion**: Safely converting strings to integers using `atoi`.
- **Modular Arithmetic**: Using the modulo operator (`%`) to handle alphabet wrapping (A-Z).
- **Character Encoding**: Direct manipulation of ASCII values.

## 💻 Getting Started

### Prerequisites
- A C compiler (e.g., `gcc`)

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/njfw50/cs50-caesar.git
   cd cs50-caesar
   ```
2. Compile the program:
   ```bash
   gcc caesar.c -o caesar
   ```
3. Run the tool with a key (e.g., 13):
   ```bash
   ./caesar 13
   ```

## 📖 Example
```bash
$ ./caesar 1
plaintext:  HELLO
ciphertext: IFMMP
```

---
*Developed as part of Harvard's CS50x.*
