# Module 1: Getting Started with Shell & Bash

## Concepts:

### What is a Shell? What is Bash?

#### What is a Shell?
A shell is a command-line interpreter that provides a user interface for the operating system’s kernel.  
It allows users to interact with the OS by typing commands.

In simple terms:
- The shell takes your commands and tells the operating system what to do.  
- You type commands → shell interprets them → OS performs actions.  

### 🧩 Common Unix/Linux Shells

| Shell | Description |
|-------|--------------|
| sh | Original Bourne Shell – the standard Unix shell |
| bash | “Bourne Again Shell” – enhanced and backward-compatible version of sh |
| zsh | Modern shell with advanced features like auto-suggestions and plugins |
| fish | Friendly Interactive Shell – known for its user-friendly design and syntax highlighting |
| dash | Debian Almquist Shell – lightweight and fast, used in some Linux systems (e.g., Debian/Ubuntu for scripting) |

### 🐚 What is Bash?
- Bash stands for Bourne-Again SHell. It is a widely used shell on Linux and macOS systems.  
  Bash is both an interactive command interpreter and a scripting language.

✅ Features of Bash:
- Command history  
- Tab completion  
- Scripting capabilities  
- Customizable environment  
- Supports variables, loops, conditionals, functions  
- Portable across many Unix-like systems  

💡 Example Bash Command:

bash
echo "Hello from Bash!"


📝 Example Bash Script (hello.sh):

bash
#!/bin/bash

echo "This script is running in Bash!"


---

### 🔍 How to Check Which Shell You're Using
Run this in your terminal:

bash
echo $SHELL
