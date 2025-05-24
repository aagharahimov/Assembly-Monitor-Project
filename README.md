# Assembly Monitor Program

This project demonstrates basic system-level programming in Assembly language by interacting with a monitor (screen output). Developed as part of the **Computer Architecture** course in the BSc Computer Science curriculum.

## 🧠 Purpose

To gain hands-on experience with low-level programming concepts, including:

- Direct output to monitor (text mode)
- Register-level operations
- System calls or interrupts (depending on the environment)

## 🧰 Tools Used

- x86 Assembly (NASM or TASM syntax)
- DOSBox or a compatible emulator for execution
- Any text editor or IDE supporting `.asm` files

## 📁 Files

- `X.asm` – Assembly source file for monitor interaction.
- `Report-Working with monitor.pdf` – Project documentation with explanation of instructions and execution flow.

## 🚀 How to Run

1. Assemble the code using NASM/TASM:
   ```bash
   nasm -f bin X.asm -o X.com
2. Launch in DOSBox:
  ```bash
  dosbox X.com
