# FrogLang 🐸

## Overview

**FrogLang** is a lighthearted, frog-themed programming language designed to make learning programming enjoyable and accessible. With a focus on fun and creativity, FrogLang combines the simplicity of Lua and the powerful features of Haxe, providing a unique environment for beginners and seasoned developers alike to explore programming concepts.

### Key Features

- **Intuitive Syntax**: Easy-to-understand commands that allow you to focus on programming without getting overwhelmed.
- **Rich Functionality**: Built-in functions such as jumping variables, calculating max/min values, generating random lucky numbers, and more whimsical features:
  - `jump`: Assign a value to a variable, reminiscent of a frog leaping.
  - `ribbit`: Generate multiple "ribbit" strings for playful outputs.
  - `frogLuck`: Simulate random lucky number generation.
  - `frogScream`: Shout messages in an exaggerated uppercase style!
  - `frogDoubleJump`: A fun way to double the value of a variable.
  - `max` and `min`: Easily find the maximum or minimum of two variables.
- **Dynamic Modding Support**: Create your own mods to extend FrogLang functionality, encouraging community contributions and creativity.
- **Interactive Features**: Integrated with JavaScript for dynamic animations, such as visual frog jumps.

## Getting Started

To get started with FrogLang, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/c00lplaza/FrogLang.git
    cd FrogLang
    ```

2. **Run the Installer**:
   - For Unix-based systems:
     ```bash
     chmod +x install.sh  # Make the script executable
     ./install.sh          # Run the installer
     ```
   - For Windows:
     ```bash
     install.bat
     ```

3. **Ensure Dependencies**:
   - Make sure you have [Haxe](https://haxe.org/download/) and [Lua](https://www.lua.org/download.html) installed on your system.

## Usage

After installation, navigate to the `FrogLang/bin` directory and run your FrogLang scripts using Haxe:

```bash
haxe -cp . -main Main -js FrogLang.js

This group project is licensed under the MIT License :D
