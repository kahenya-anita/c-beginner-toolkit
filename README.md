# 🧠 Moringa AI Capstone: C Beginner Toolkit  
## "Hello, World!" in C – Setup, Compile, and Run

Welcome to your first C program! This project helps you **write, compile, and run** a simple C program using free, beginner-friendly tools. It’s part of the **Moringa AI Capstone: Prompt-Powered Kickstart**, where I used **generative AI** to learn C from scratch — no prior experience needed.

🎯 **Goal**: Get `hello.c` running on your machine, whether you're on **Windows, macOS, or Linux**.

---

## 🚀 What’s Inside

- A simple, well-commented `hello.c` file.
- Step-by-step setup for all major operating systems.
- Beginner-friendly guide to compiling and running C code.
- Tips for troubleshooting and learning more.

---

## 📦 Requirements

- A computer running Windows, macOS, or Linux.
- No prior programming experience necessary!
- Internet connection to download tools (if not already installed).

---

## 🛠️ Installation & Setup

### 1. Install a C Compiler

**Windows:**
- Download and install [Code::Blocks](http://www.codeblocks.org/downloads/26) (includes the GCC compiler).
- Alternatively, install [TDM-GCC](https://jmeubank.github.io/tdm-gcc/).

**macOS:**
- Open Terminal and run:  
  ```sh
  xcode-select --install
  ```
  This installs the Apple developer tools, including `gcc`.

**Linux (Ubuntu/Debian):**
- Open Terminal and run:  
  ```sh
  sudo apt update
  sudo apt install build-essential
  ```

### 2. Get the Code

- Download or clone this repository:
  ```sh
  git clone https://github.com/your-username/your-repo.git
  cd your-repo
  ```
  Or just copy the contents of `hello.c` into a new file.

---

## 👋 Write Your First C Program

Check out `hello.c` in this repo:

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

---

## ⚡ Compile & Run

Open your Terminal (or Command Prompt) and run:

```sh
gcc hello.c -o hello
./hello      # On Windows, use: hello.exe
```

You should see:
```
Hello, World!
```

---

## 🧩 Troubleshooting

- **Command not found?**  
  Make sure `gcc` is installed. Close and reopen your terminal after installation.
- **Permission denied (macOS/Linux)?**  
  Try: `chmod +x hello`
- **Still stuck?**  
  [Open an issue](https://github.com/your-username/your-repo/issues) or ask your instructor for help!

---

## 🤝 Contributing

Pull requests are welcome!  
If you have suggestions for making this toolkit even more accessible to beginners, feel free to fork and submit a PR.

---


---

## 🌱 Next Steps

- Try changing the message in `hello.c`!

Happy coding! 🚀
