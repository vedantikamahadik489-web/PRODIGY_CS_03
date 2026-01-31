# PRODIGY_CS_03
Internship Task 3 - Password complexity Checker 
  
# Password Strength Checker

This project is a Python-based Password Strength Checker that evaluates the security level of a password using multiple validation rules. It helps users understand whether their password is weak, medium, or strong.

## Features

- Checks minimum password length
- Validates presence of uppercase letters
- Validates presence of lowercase letters
- Checks for numeric characters
- Checks for special characters
- Displays password strength as Weak, Medium, or Strong

## Technologies Used

- Python
- Regular Expressions (re module)

## Working Logic

Each condition adds one point to the password score:

- Length ≥ 8 characters
- Uppercase letter present
- Lowercase letter present
- Number present
- Special character present

### Strength Evaluation:

- 0 – 2 points → Weak Password  
- 3 – 4 points → Medium Password  
- 5 points → Strong Password  

## How to Run

1. Open VS Code or terminal  
2. Navigate to the project folder  
3. Run:

```bash
python password_checker.py
 

