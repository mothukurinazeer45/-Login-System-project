# -Login-System-project
A simple Python Tkinter-based login system featuring user registration, secure SHA-256 password hashing, security questions for recovery, and password reset functionality. Stores user data in a local file and provides an easy GUI for beginners to learn authentication concepts.
🔐 Enhanced Python Login System (Tkinter)

A simple and secure GUI-based Login System built using Python Tkinter.
This project demonstrates user authentication, password hashing, security questions, and password reset functionality.
Perfect for beginners learning GUI development and authentication concepts.

🚀 Features

✅ User Registration
✅ Secure SHA-256 password hashing
✅ Login Authentication
✅ Security Question Setup
✅ Forgot Password System
✅ Password Reset Using Security Answer
✅ Data stored safely in a local file (users.txt)
✅ Clean and easy-to-use GUI built with Tkinter

📁 Project Structure
project/
├── users.txt          # Stores user credentials securely
└── login_system.py    # Main application script

🛠️ Technologies Used

Python 3

Tkinter (GUI)

hashlib (Password hashing)

os module (File handling)

📌 How It Works
🔸 Registration

Users create an account by providing:

Username

Password

Security Question

Security Answer

All sensitive information is stored as secure hashes.

🔸 Login

The system hashes the entered password and compares it with stored hashed passwords.

🔸 Forgot Password

Users answer their security question and can reset the password if the answer is correct.

▶️ How to Run

Install Python 3

Save the script as login_system.py

Run the program:

python login_system.py


A GUI window will appear to handle login, registration, and password reset.

📸 Screenshots (Optional)

You can add screenshots here after capturing your GUI windows.

💡 Future Improvements

Add email-based OTP verification

Add password strength meter

Store data using SQLite instead of text file

Modernize UI using ttk or customtkinter

🤝 Contributing

Pull requests are welcome!
Feel free to open an issue for suggestions or improvements.

📄 License

This project is open-source and free to use.
