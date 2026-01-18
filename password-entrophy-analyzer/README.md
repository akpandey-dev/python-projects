# Password Entropy Analyzer

A Python-based terminal tool that analyzes passwords using **entropy calculations** to estimate their **strength, predictability, and estimated crack time**.  
Designed to educate users on why *length + character diversity* matters more than clever-looking passwords.

This is not magic. It’s math.

---

## 🧠 What This Tool Does

- Calculates **password entropy (in bits)** using information theory
- Classifies password strength from **Very Weak** to **Uncrackable**
- Estimates **brute-force crack time** assuming 10 billion guesses/second
- Detects character sets used:
  - Lowercase letters
  - Uppercase letters
  - Digits
  - Symbols
  - Whitespace
- Displays results in a **colorized terminal UI**
- Compares multiple passwords side-by-side

---

## 📌 What Is Entropy?

In password security, **entropy** measures how unpredictable a password is.

> Higher entropy = more possible combinations = harder to crack.

Entropy is calculated as:

entropy = password_length × log₂(character_set_size)


This tool makes that concept tangible instead of abstract.

---

## ⚙️ Requirements

- Python 3.7+
- `colorama` library

Install dependencies:

```bash
pip install colorama
