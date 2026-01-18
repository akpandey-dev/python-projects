# Password Strength Analyzer

A Python command-line tool that evaluates password strength using **practical security rules** instead of pure mathematics.  
It scores a password based on common best practices and explains **why** a password is weak or strong — with optional improvement suggestions.

Simple rules. Clear feedback. No illusions.

---

## 🧠 How This Tool Works

Instead of entropy formulas, this tool checks whether a password follows widely accepted security rules:

- Minimum length
- Digits included
- Lowercase letters
- Uppercase letters
- Special characters

Each rule contributes to a **strength score (0–5)**.

---

## 📊 Strength Scoring System

| Score | Strength Level |
|------|----------------|
| < 3  | Weak |
| 3    | Moderate |
| 4    | Strong |
| 5    | Very Strong |

This approach mirrors what many real-world signup forms and systems enforce.

---

## ⚙️ Requirements

- Python 3.7+
- `colorama` library

Install dependency:
```bash
pip install colorama
