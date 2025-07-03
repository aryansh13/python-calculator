# 🧮 Python Calculator

![License](https://img.shields.io/badge/license-MIT-green)

A simple command-line calculator implemented in Python.  
This project demonstrates basic Python programming, unit testing, and CI/CD integration using Jenkins.

---

## ✨ Features

- ✅ **Basic arithmetic operations:** addition, subtraction, multiplication, division.
- ✅ **Simple command-line interface.**
- ✅ **Unit tests** with Python’s built-in `unittest` module.
- ✅ **Ready for CI/CD integration** with Jenkins.

---

## 📂 Project Structure

\`\`\`plaintext
python-calculator/
│
├── calculator.py          # Main calculator functions
├── test_calculator.py     # Unit tests for calculator functions
├── Jenkinsfile            # Jenkins pipeline configuration
└── README.md              # Project documentation
\`\`\`

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository

\`\`\`bash
git clone https://github.com/aryansh13/python-calculator.git
cd python-calculator
\`\`\`

### 2️⃣ Run the Calculator

\`\`\`bash
python calculator.py
\`\`\`

### 3️⃣ Run Unit Tests

\`\`\`bash
python -m unittest test_calculator.py
\`\`\`

---

## 🧪 Running Tests with Jenkins

This project includes a \`Jenkinsfile\` to automate:

- ✅ Cloning the repository
- ✅ Running unit tests automatically

Example Jenkins pipeline stages:

- **Checkout:** Clone the Git repository.
- **Test:** Run the test suite using \`unittest\`.

---

## 📜 Requirements

- Python 3.x
- No external packages needed (uses Python standard library).

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repository, create a new branch, and submit a pull request.

---

## 📫 Author

**Created by:** [Aryansh13](https://github.com/aryansh13)  
If you find this project helpful, feel free to ⭐ star the repo!
