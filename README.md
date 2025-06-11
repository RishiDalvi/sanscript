<<<<<<< HEAD
# Sansript: A Sanskrit-Based Programming Language  

**Sansript** is a programming language inspired by the rich heritage of Sanskrit. It allows users to write code in Sanskrit, adhering to a modern programming paradigm, and supports execution by translating Sanskrit code into Python.  

## 🔗 Website  
Explore the language and try it online at: [Sansript Playground](https://sanscript.netlify.app/)

## 🌟 Features  
- **Write Code in Sanskrit**: Use Sanskrit-based syntax for writing programs.  
- **Modules for Language Processing**:
  - **Tokenizer**: Processes the code into tokens.  
  - **Parser**: Generates the Abstract Syntax Tree (AST).  
  - **Validator**: Validates the AST for correctness.  
  - **Code Generator**: Converts the AST into Python code.  
  - **Executor**: Executes the generated Python code.  
- **Playground**: A web-based code editor for writing and testing Sansript programs.  
- **Client-Side Execution**: Powered by [Pyodide](https://pyodide.org/), Python code runs directly in the browser.  
- **Documentation**: Detailed features and syntax are available in `documentation.md`.  

---

## 🖥️ Project Structure  

```plaintext
Sansript/
├── modules/
│   ├── tokenizer.py         # Tokenizes the Sanskrit code  
│   ├── parser.py            # Generates the AST  
│   ├── validator.py         # Validates the AST  
│   ├── codegenerator.py     # Converts AST to Python  
│   ├── executor.py          # Executes the generated Python code  
|   └── design.bnf           # Syntax specification in BNF format  
├── documentation.md         # Detailed language documentation  
├── fonts                    # custom fonts
├── index.html               # Frontend for the playground  
├── styles/                  # CSS for the website design  
├── scripts/                 # JS for the frontend logic  
├── LICENSE                  # License information  
├── .gitignore
└── README.md                # Project overview and guide  
```

---

## 🚀 Getting Started  

### Clone the Repository  
```bash
git clone https://github.com/RishiDalvi/Sansript.git
cd Sansript
```

### Running Locally  
1. **Install Python dependencies**:  
   Ensure you have Python installed.  
   ```bash
   pip install -r requirements.txt
   ```  

2. **Run locally**:  
   Execute the modules manually for testing and experimentation.  

### Online Playground  
Visit the official [Sansript Playground](https://sanscript.netlify.app/) to write and execute Sansript programs directly in your browser.

---

## 📜 Syntax and Documentation  
For a comprehensive guide to Sansript's syntax, keywords, and examples, refer to [`documentation.md`](documentation.md)

---

## 🌐 Website Features  
- **Code Editor**: Write Sansript programs in a syntax-highlighted editor.  
- **Execution Engine**: Run programs directly in the browser using Pyodide.  
- **Thematic Design**: An old-paper style vintage theme for aesthetics.  

---

## 📂 Contributing  

We welcome contributions! Here’s how you can help:  
1. Fork the repository.  
2. Create a new branch for your feature/bugfix.  
3. Submit a pull request with detailed descriptions.  

Please ensure that your code adheres to the coding standards and includes necessary tests where applicable.  

---

## 🛡️ License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---

## 📞 Support  

If you have any questions, suggestions, or issues, feel free to create an issue in the repository or contact us at[rishi_master@proton.me].  
