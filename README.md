# 📧 Python Email Validator
This project is a **Python-based Email Validator** that checks the validity of an email address by verifying its structure, allowed characters, and format. It was built during my **Python learning journey**, with inspiration and guidance taken from online tutorials and a helpful YouTube channel.  

## 🚀 Features
•	Validates:
1.	Email length (≥ 6 characters)
2.	First character as an alphabet
3.	Presence of exactly one `@`
4.	Correct placement of `.`
5.	No spaces allowed
6.	Only valid characters: alphabets, digits, `_`, `.`, `@`
•	Detects common mistakes and provides meaningful error messages.
•	Includes **exception handling** for robust execution.

## 📂 Project Structure
email-validator-py/
│-- email_validator.py # main program
│-- README.md # documentation


## 🛠️ Technologies Used
•	**Python 3.x**
•	Basic Python concepts:
•	String handling
•	Conditional statements
•	Exception handling
•	Loops


## 📌 Use Cases
•	**Form Validation**: Can be extended to validate user emails in registration/login systems.
•	**Learning Resource**: Great for beginners to understand how validation logic works.
•	**Data Cleaning**: Useful in scripts where invalid emails need to be filtered out.

## 💡 Importance & Practicality
Email validation is an essential part of almost every **real-world application** — from sign-ups and feedback forms to authentication systems.  
This project demonstrates how such a validation system can be built from scratch using only **core Python**, without relying on external libraries.  


## 🎓 Learning Journey
This project is a milestone in my **Python learning path**, helping me apply:
•	Conditions (`if-else`)
•	Loops
•	String methods
•	Exception handling  

It also reflects how **small projects can build a strong foundation** for bigger applications in the future.  

## ▶️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/TAIMOURMUSHTAQ/smart-email-validator-py.git
   cd smart-email-validator-py
Run the script:

bash
python email_validator.py

Enter an email and check the result 🎉

✅ Example
Enter your email address: test.email@gmail.com
✅ Valid Email!
Enter your email address: user@@domain.com
❌ Wrong email at 3

🔮 Future Improvements
•	GUI-based validation tool
•	Web-based email validation API
•	Integration with regex for advanced checking

🙌 Acknowledgment
This project was developed as part of my Python journey, with helpful insights gained from an educational YouTube channel that inspired the implementation approach.
