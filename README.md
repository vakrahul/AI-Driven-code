# AI-Driven Code Reviewer

An automated assistant for code analysis, error detection, and optimization suggestions, developed during the **Infosys Springboard Virtual Internship**.

---


##  About the Project

The **AI-Driven Code Reviewer** is a web-based application designed to help developers improve Python code quality efficiently.  
It leverages **Large Language Models (LLMs)** and **static code analysis techniques** to detect errors, enforce best practices, and provide intelligent optimization suggestions.

The application analyzes Python code using:
- **Abstract Syntax Tree (AST)** for structural understanding
- **PEP 8 style rules** for readability and maintainability
- **Qwen 2.5 Large Language Model** for AI-powered insights and refactoring advice

This tool aims to simulate an intelligent code reviewer that assists developers during development and learning.

---

##  Key Features

- **Automated Code Analysis**
  - Parses Python code to understand logic and structure

- **Error Detection**
  - Identifies syntax errors
  - Detects potential runtime and logical issues

- **Style Checking**
  - Validates Python code against **PEP 8 coding standards**

- **AI-Powered Insights**
  - Suggests refactoring and optimization using  
    **Qwen-2.5-7B-Instruct LLM**

- **Interactive Interface**
  - User-friendly Streamlit UI
  - Built-in chat for asking questions about specific code snippets

---

## 🛠 Tech Stack

- **Programming Language:** Python 3.11  
- **Framework:** Streamlit  
- **AI Model:** Qwen/Qwen2.5-7B-Instruct (via Hugging Face)  
- **Static Analysis:** AST (Abstract Syntax Tree)  
- **API Provider:** Hugging Face Inference API  

---
##  Project Structure

Here is an overview of the key files in the repository:

```text
 AI-Driven-Code-Reviewer
├── 📄 app.py                  # Main entry point for the Streamlit application
├── 📄 ai_suggester.py         # Interface with Hugging Face API for suggestions
├── 📄 code_parser.py          # Handles parsing of Python code (AST)
├── 📄 error_detector.py       # Identifies syntax and logical errors
├── 📄 style_checker.py        # Checks code for style and PEP-8 compliance
├── 📄 requirements.txt        # List of Python dependencies

```
---
## ⚙️ Installation

### 1️⃣ Clone the Repository
git clone https://github.com/vakrahul/AI-Driven-code.git
cd AI-Driven-Code

### 2️⃣ Set Up Virtual Environment
python -m venv venv  
source venv/bin/activate      # Linux / macOS  
venv\Scripts\activate         # Windows  
```
```
### 4️⃣ Configure Hugging Face API Key
Create either:
Option 1: .env file  
HUGGINGFACE_ACCESS_TOKEN=your_token_here  
Option 2: .streamlit/secrets.toml  
HUGGINGFACE_ACCESS_TOKEN = "your_token_here"
```
```
### ▶️ Run the Application
streamlit run app.py  

The app will open in your browser automatically.

### 📘 Usage Guide

Input Code  
Paste Python code into the provided text area  

Analyze  
Click Analyze Code to start processing  

Review Results  
Bugs & Errors: Syntax and logical issues  
Style Fixes: PEP 8 improvements  
AI Advice: Intelligent refactoring suggestions  

Ask Questions  
Use the chat interface for code-specific doubts  
```
```
### 👨‍💻 Author

Rahul Vakiti  
Role: Intern at Infosys Springboard  

