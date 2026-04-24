# 🔐 Password Generator (Python)

A simple and secure command-line password generator built using Python.  
This project allows users to generate strong passwords based on selected character types like uppercase letters, lowercase letters, numbers, and symbols.

---

## 🚀 Features

- Generate random secure passwords
- Choose character types:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special symbols
- Custom password length
- Uses Python's `secrets` module for cryptographically secure randomness
- Simple and interactive command-line interface

---

## 🛠️ Built With

- Python 3
- `string` module (for character sets)
- `secrets` module (for secure random generation)

---

## 📌 How It Works

1. User selects which character types to include
2. User enters desired password length
3. Program builds a pool of selected characters
4. A secure password is generated using `secrets.choice()`
5. User can choose to generate another password or exit

---

## ▶️ How to Run

1. Make sure Python 3 is installed
2. Clone this repository:
```bash
git clone https://github.com/your-username/password-generator.git

---

##   Sample Output
PASSWORD GENERATOR
Do you want Uppercase letters? yes
Do you want Lowercase letters? yes
Do you want Numbers? yes
Do you want Symbols? no
Enter password length: 12

Your new Generated password is: A8kLp2xZ91mQ
