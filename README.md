# Custom Python Linter 🐍

A simple Python linter tool that checks your Python files for best practices and anti-patterns using static analysis.

## 🔍 Features

- Detects bad practices like:
  - Use of `print()` instead of `logging`
  - Bare `except` clauses
  - Mutable default arguments
  - Unused imports
  - Global variable usage
  - Incorrect None comparison using `==` or `!=`
- Scans both single files and entire directories
- Easy to extend with more rules!

## 📦 Usage

```bash
python linter.py <file_or_directory>
