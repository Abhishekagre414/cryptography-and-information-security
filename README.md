# Cryptography and Information Security

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Programming Languages](https://img.shields.io/badge/Languages-Python%20%7C%20C%20%7C%20C%2B%2B-blue.svg)](#programming-languages)
[![Course Level](https://img.shields.io/badge/Course-B.Tech%20CSE/IT-red.svg)](#)

A comprehensive, industry-aligned repository for the undergraduate-level (B.Tech) course **"Cryptography and Information Security"**. This repository serves as a centralized hub for learning materials, practical implementations, assessments, and reference resources designed to build a strong foundation in modern cybersecurity paradigms.

---

## 📖 Table of Contents
- [Project Description](#-project-description)
- [Features](#-features)
- [Repository Structure](#-repository-structure)
- [Topics Covered](#-topics-covered)
- [Prerequisites](#-prerequisites)
- [Programming Languages](#-programming-languages)
- [How to Use](#-how-to-use)
- [Contribution Guidelines](#-contribution-guidelines)
- [License](#-license)

---

## 📝 Project Description

In an increasingly digitized world, securing information systems is of paramount importance. This course covers the fundamental mathematical theories, algorithms, and security protocols that form the bedrock of data security.

This repository is curated to assist both students and educators. It details:
* **Theoretical Foundations:** Lecture notes, research papers, and slide presentations covering basic and advanced topics.
* **Hands-on Labs:** Implementations of classical ciphers, symmetric key standards, asymmetric key cryptosystems, hash algorithms, and digital signature schemes.
* **Assessments:** Assignments and lab tasks to reinforce academic concepts through programming.

---

## ✨ Features

* **Multi-Language Implementations:** Algorithms are implemented in **Python**, **C**, and **C++** to highlight the differences in memory-safe scripting vs. high-performance systems-level implementations.
* **Standardized Directory Structure:** Organised following industry-standard layout guidelines for clean navigation.
* **Clean Code Practices:** Implementations focus on readability, input validation, and clear documentation.
* **Academic Resources:** Integrated lectures, presentations, and bibliography of key research papers.

---

## 🗂️ Repository Structure

The repository is structured as follows to ensure easy discovery of coursework, theory, and code:

```text
cryptography-and-information-security/
│
├── .gitignore                      # Git ignore rules for Python, C/C++, and VS Code
├── LICENSE                         # MIT License file
├── README.md                       # Main repository documentation
│
├── lectures/                       # Classroom lecture notes and summaries
├── assignments/                    # Academic assignments and project briefs
├── labs/                           # Lab manuals, task sheets, and experimental logs
├── presentations/                  # PowerPoint/PDF slides for presentations
├── research-papers/                # Classical and modern research papers for reading
├── resources/                      # External links, reference books, and websites
│
├── assets/
│   └── images/                     # Diagrams, flowcharts, and visual aids
│
└── programs/                       # Source code implementations of cryptographic algorithms
    ├── caesar-cipher/              # Caesar Cipher (Substitution Technique)
    ├── monoalphabetic-cipher/      # Monoalphabetic Cipher
    ├── playfair-cipher/            # Playfair Cipher (Polyalphabetic)
    ├── hill-cipher/                # Hill Cipher (Matrix-based Substitution)
    ├── vigenere-cipher/            # Vigenere Cipher (Polyalphabetic)
    ├── rail-fence-cipher/          # Rail Fence Cipher (Transposition Technique)
    ├── des/                        # Data Encryption Standard (DES) block cipher
    ├── aes/                        # Advanced Encryption Standard (AES) block cipher
    ├── rsa/                        # Rivest-Shamir-Adleman (RSA) asymmetric algorithm
    ├── diffie-hellman/             # Diffie-Hellman Key Exchange protocol
    ├── elgamal/                    # ElGamal Cryptosystem
    ├── ecc/                        # Elliptic Curve Cryptography (ECC)
    ├── sha/                        # Secure Hash Algorithm (SHA-1, SHA-256)
    ├── md5/                        # Message Digest 5 (MD5) Hash Function
    ├── digital-signature/          # Digital Signature Standard (DSS) & verification
    └── pki/                        # Public Key Infrastructure simulators/tools
```

---

## 📚 Topics Covered

The course curriculum is divided into core modules, matching the codebase structure:

1. **Introduction to Cryptography:** Security services, mechanisms, and classical encryption techniques (substitution and transposition ciphers).
2. **Symmetric-Key Cryptography:** Block cipher principles, Feistel networks, DES, Triple DES, and the Advanced Encryption Standard (AES).
3. **Asymmetric-Key Cryptography:** Number Theory foundations (modular arithmetic, Euler's totient function, prime factorization), RSA, ElGamal, and Elliptic Curve Cryptography (ECC).
4. **Key Management & Distribution:** Symmetric key distribution, Diffie-Hellman key exchange, and Public Key Infrastructure (PKI).
5. **Hash Functions & Message Digests:** Cryptographic hash properties, MD5, and Secure Hash Algorithm (SHA) families.
6. **Digital Signatures & Authentication:** Digital signature algorithms, message authentication codes (MAC/HMAC), and user authentication protocols.

---

## 🛠️ Prerequisites

To successfully engage with this course repository, you should have a baseline understanding of:

* **Mathematics:**
  * Modular arithmetic (e.g., modulo operation, modular multiplicative inverse).
  * Fundamental number theory (Euclidean Algorithm, Fermat's Little Theorem, Euler's Theorem).
  * Linear Algebra (Matrix addition, multiplication, determinants, and matrix inversion for Hill Cipher).
* **Programming:**
  * Basic knowledge of control flow, functions, and command-line arguments in **Python**, **C**, or **C++**.
  * File I/O and byte-level manipulation (especially for DES/AES/SHA block processing).

---

## 💻 Programming Languages

The code implementations are split across three primary languages, choosing the best tool for the concept:

| Language | Primary Focus / Applications | Compile/Run Tools |
| :--- | :--- | :--- |
| **Python** 🐍 | RSA, ECC, Diffie-Hellman (great library support for big integers and fast prototyping) | Python 3.8+ |
| **C** ⚙️ | Caesar, Playfair, DES, MD5 (close to metal, highlighting bitwise operations) | GCC |
| **C++** 🚀 | AES, Vigenere, SHA, Digital Signatures (uses OOP features and STL containers) | G++ |

---

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/cryptography-and-information-security.git
cd cryptography-and-information-security
```

### 2. Compilation and Execution

#### Running Python Programs (e.g., RSA)
```bash
cd programs/rsa
python rsa_demo.py
```

#### Compiling and Running C Programs (e.g., Caesar Cipher)
```bash
cd programs/caesar-cipher
gcc caesar.c -o caesar
./caesar
```

#### Compiling and Running C++ Programs (e.g., Vigenere Cipher)
```bash
cd programs/vigenere-cipher
g++ vigenere.cpp -o vigenere
./vigenere
```

---

## 🤝 Contribution Guidelines

Contributions are welcome! If you are a student, teaching assistant, or instructor, please follow these steps to contribute new material, correct errors, or optimize algorithms:

1. **Fork the repository** to your personal GitHub account.
2. **Create a feature branch** representing your changes:
   ```bash
   git checkout -b feature/add-new-program
   ```
3. **Commit your changes** with clear and concise commit messages:
   ```bash
   git commit -m "Add implementation of Hill Cipher in Python"
   ```
4. **Push the changes** to your fork:
   ```bash
   git push origin feature/add-new-program
   ```
5. **Open a Pull Request (PR)** against the `main` branch of this repository. Please describe the problem solved or the algorithm implemented in the PR description.

---

## 📄 License

This repository is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more information.
