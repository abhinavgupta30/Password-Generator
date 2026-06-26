# 🔐 Password Generator

A responsive and interactive Password Generator built using **HTML, CSS, and Vanilla JavaScript**. The application allows users to generate secure and customizable passwords based on selected criteria such as uppercase letters, lowercase letters, numbers, symbols, and password length.

---

## 📸 Preview

> Add a screenshot of your project here after uploading it to GitHub.

Example:

```
assets/screenshot.png
```

---

## 🚀 Features

- ✅ Generate strong random passwords
- ✅ Adjustable password length using a slider
- ✅ Include:
  - Uppercase Letters
  - Lowercase Letters
  - Numbers
  - Special Symbols
- ✅ Password strength indicator
- ✅ One-click copy to clipboard
- ✅ Responsive and modern UI
- ✅ Fisher-Yates shuffle algorithm for better randomness

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)

---

## 📂 Project Structure

```
Password-Generator/
│
├── index.html
├── styles.css
├── script.js
│
├── assets/
│   ├── copy.svg
│   └── favicon.ico
│
└── README.md
```

---

## ⚙️ How It Works

1. Select the desired password length.
2. Choose the character types you want:
   - Uppercase
   - Lowercase
   - Numbers
   - Symbols
3. Click **Generate Password**.
4. Copy the generated password using the copy button.

The application ensures that at least one character from every selected category is included in the generated password.

---

## 🔒 Password Generation Logic

The project follows these steps:

- Collects all selected character categories.
- Adds one mandatory character from each selected category.
- Fills the remaining characters randomly.
- Uses the **Fisher-Yates Shuffle Algorithm** to randomize the final password.
- Calculates password strength based on:
  - Password length
  - Variety of selected character types

---

## 📋 Future Improvements

- Dark/Light Mode
- Password History
- Password Expiry Timer
- Exclude Similar Characters (O, 0, l, I)
- Exclude Ambiguous Symbols
- Password Entropy Calculator
- Save Password Preferences
- Mobile-first animations
- Keyboard shortcuts
- Generate memorable passphrases

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/your-username/password-generator.git
```

Navigate into the project folder

```bash
cd password-generator
```

Open `index.html` in your browser.

No additional dependencies or installations are required.

---

## 🎯 Learning Outcomes

Through this project, I learned:

- DOM Manipulation
- Event Handling
- Clipboard API
- Random Number Generation
- Fisher-Yates Shuffle Algorithm
- JavaScript Functions
- Responsive UI Design
- Password Strength Validation
- Modern CSS Styling

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Abhinav Gupta**

- GitHub: https://github.com/your-github-username
- LinkedIn: https://linkedin.com/in/your-linkedin-profile

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub.