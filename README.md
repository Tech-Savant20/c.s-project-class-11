# Banking System Simulation: Class 11 Computer Science Project

My Class 11 Computer Science project (CBSE): a menu-driven, text-based banking system written in Python.

## What it does

- **Log in** with an account number, a password and a displayed verification code (a simple CAPTCHA), checked against a built-in list of sample customers.
- **Open a new account** by entering your name, address, job address, date of birth and opening balance, then receive an account number.
- **Deposit and withdraw** money.
- **Loans:** personal, car and mobile loans, with simple- or compound-interest calculation and EMI options based on the loan amount, tenure and your monthly income.
- **Insurance** as an optional add-on.

All data lives in Python lists while the program runs; nothing is saved to disk.

## Files

| File | Contents |
|------|----------|
| `bank.txt` | The program source (Python, saved as a text file) |
| `bankingnote.txt` | A copy of the same program |
| `intro.docx`, `index.docx`, `Acknowledgment.docx`, `CERTIFCATE.docx`, `BIBLIOGRAPHY.docx` | Sections of the written project report |
| `DPS logo.jpg` | School logo used in the report |
| `cs.txt` | Rough marking notes |

## Running it

```bash
cp bank.txt bank.py      # Windows: copy bank.txt bank.py
python bank.py
```

Follow the prompts in the terminal (for example, type `login` or `new` at the first prompt).

## Concepts used

Python basics: `input`/`print`, conditionals, `while` and `for` loops, nested lists, the `random` module and arithmetic for interest and EMI.
