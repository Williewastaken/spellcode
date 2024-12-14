# SpellCode

![SpellCode Logo](images/spellcode_logo.png)

*Welcome to SpellCode, the magical programming language inspired by the wizarding world of Harry Potter!*

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
   - [Installation](#installation)
   - [Running SpellCode Scripts](#running-spellcode-scripts)
3. [Language Overview](#language-overview)
   - [Basic Syntax](#basic-syntax)
   - [Variable Declarations](#variable-declarations)
   - [Data Types](#data-types)
   - [Operators](#operators)
4. [Control Structures](#control-structures)
   - [Conditional Statements](#conditional-statements)
   - [Loops](#loops)
5. [Functions (Incantations)](#functions-incantations)
   - [Defining Incantations](#defining-incantations)
   - [Calling Incantations](#calling-incantations)
6. [Modules and Imports](#modules-and-imports)
   - [Importing Modules](#importing-modules)
   - [Built-in Libraries](#built-in-libraries)
7. [Built-in Libraries](#built-in-libraries-1)
   - [Defense Library](#defense-library)
   - [Transfiguration Library](#transfiguration-library)
   - [Alchemy Library](#alchemy-library)
8. [Error Handling](#error-handling)
9. [Examples](#examples)
   - [Hello, Wizard!](#hello-wizard)
   - [Sorting Spells](#sorting-spells)
   - [Brewing a Potion](#brewing-a-potion)
10. [Creating External Modules](#creating-external-modules)
11. [Extending SpellCode](#extending-spellcode)
12. [Glossary](#glossary)
13. [FAQ](#faq)
14. [Contributing](#contributing)
15. [License](#license)

---

## Introduction

**SpellCode** is a high-level, Harry Potter-themed programming language designed to make coding an enchanting experience for fans of the magical world. By leveraging familiar terminology from the wizarding universe, SpellCode aims to engage users and make the learning process both fun and immersive.

![SpellCode Workflow](images/spellcode_workflow.png)

*Diagram: Overview of SpellCode's Workflow (Lexer → Parser → AST → Interpreter)*

**Key Features:**

- **Magical Syntax:** Commands and structures inspired by spells and magical artifacts.
- **Incantations:** Function definitions called "Incantations."
- **Wand Variables:** Variables referred to as "Wands."
- **Built-in Libraries:** Access to magical libraries like Defense, Transfiguration, and Alchemy.
- **Control Structures:** Familiar programming constructs with a magical twist.

---

## Getting Started

### Installation

1. **Prerequisites:**
   - Ensure you have **Python 3** installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).

2. **Download SpellCode Interpreter:**
   - Clone the SpellCode repository from GitHub:
     ```bash
     git clone https://github.com/yourusername/spellcode.git
     ```
   - Navigate to the project directory:
     ```bash
     cd spellcode
     ```

3. **External Modules (Optional):**
   - To utilize external modules, create `.spell` files in the same directory as `spellcode.py`. For example, create `Charms.spell` for additional incantations.

### Running SpellCode Scripts

1. **Create a SpellCode Script:**
   - Write your SpellCode code in a `.spell` file or directly within the `main` function in `spellcode.py`.

2. **Execute the Script:**
   - Open your terminal or command prompt.
   - Navigate to the directory containing `spellcode.py`.
   - Run the interpreter using:
     ```bash
     python3 spellcode.py
     ```

3. **Using External Modules:**
   - Ensure your external `.spell` modules are in the same directory.
   - Use the `Import` statement within your SpellCode script to include them.

---

## Language Overview

### Basic Syntax

SpellCode combines elements from traditional programming languages with magical terminology. Here's an overview of its basic syntax:

- **Comments:** Use `//` for single-line comments.
  ```spellcode
  // This is a comment
