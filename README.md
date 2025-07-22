# 🪷 Sanscript: A Sanskrit-Based Programming Language

**Sanscript** is a modern programming language that brings the elegance of Sanskrit into software development. It allows developers to write code using Sanskrit-based syntax and translates it into executable Python code. This project is built with love and precision, combining linguistic heritage with the power of Pyodide.

---

## 🔗 Live Website

👉 [Sanscript Playground](https://sanscript.netlify.app/)

Write, test, and execute Sanskrit code directly in your browser.

---

## 🌟 Features

- 🔤 **Sanskrit Syntax**: Variables, loops, functions, and conditions in Sanskrit.
- 🧠 **Modular Language Engine**:
  - `tokenizer.py`: Converts Sanskrit code into tokens
  - `parser.py`: Builds the Abstract Syntax Tree (AST)
  - `validator.py`: Validates the AST
  - `codegenerator.py`: Generates Python code from AST
  - `executor.py`: Executes the generated Python
- 🧪 **In-Browser Execution**: Powered by [Pyodide](https://pyodide.org/)
- 🎮 **Interactive Playground**: Try the language in real-time
- 📜 **Beautiful UI**: Old paper-style theme with syntax highlighting
- 📘 **Full Documentation**: Available in [`documentation.md`](documentation.md)

---

## 🖥️ Project Structure

```bash
Sanscript/
├── index.html               # Web UI playground
├── modules/
│   ├── tokenizer.py         # Token processor
│   ├── parser.py            # AST generator
│   ├── validator.py         # AST validator
│   ├── codegenerator.py     # Converts AST to Python
│   ├── executor.py          # Executes code
│   └── design.bnf           # BNF grammar rules
├── documentation.md         # Language documentation
├── styles/                  # CSS files
├── scripts/                 # JS logic
├── fonts/                   # Fonts used in UI
├── .gitignore               # Git ignore file
├── LICENSE                  # MIT License
└── README.md                # This file
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/RishiDalvi/Sanscript.git
cd Sanscript
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

> You must have Python installed to run backend modules locally.

---

## 🌐 Running the Playground

You can:
- Use the live editor at [sanscript.netlify.app](https://sanscript.netlify.app/)
- Or open `index.html` locally in a browser
- All code execution happens **client-side** using Pyodide (no server needed)

---

## 📜 Syntax Highlights

```sanskrit
कार्य मुख्यः() {
    चरः संख्या = 10;
    यदि (संख्या > 5) {
        मुद्रणम्("संख्या बड़ी है");
    } अन्यथा {
        मुद्रणम्("संख्या छोटी है");
    }
}
```

> See [`documentation.md`](documentation.md) for all supported keywords, AST formats, and examples.

---

## 👨‍💻 Contributing

We welcome contributions from the open-source community.

### How to Contribute

1. **Fork** this repository
2. Create a **feature branch** (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "feat: describe your change"`)
4. Push to your fork (`git push origin feature-name`)
5. Create a **Pull Request**

> Please ensure your code follows existing styles and include test cases if needed.

---

## 🛡 License

This project is dual-licensed under:

- [MIT License](LICENSE-MIT)
- [Apache License 2.0](LICENSE-APACHE)

You may choose either license to use this project under.

---

## 📞 Support

Have questions, suggestions, or issues?

- 📬 Email: [rishi_master@proton.me](mailto:rishi_master@proton.me)
- 🐞 Report Bugs: [GitHub Issues](https://github.com/RishiDalvi/Sanscript/issues)
- 📢 Feedback and PRs are welcome anytime!

---

## 🙏 Credits

Created with 💖 by [Rushikesh Dalavi](https://www.linkedin.com/in/rushikesh-dalavi/)  
Maintained by [TechMate Labs](https://www.techmatelabs.in/)

---

## 📌 Related Links

- 🔗 [Documentation](https://sanscript.netlify.app/#documentation)
- 🧠 [Pyodide](https://pyodide.org/)
- 🐙 [GitHub Repository](https://github.com/RishiDalvi/Sanscript)
- 🚀 [Live Playground](https://sanscript.netlify.app/)
