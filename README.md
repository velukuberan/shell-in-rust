# 🦀 Simple Shell in Rust

A simple shell implementation written in **Rust**, inspired by the Linux shell.
This project is mainly for learning purposes — exploring command parsing, REPL design, and implementing basic shell features.

## ✨ Features

* **REPL (Read-Eval-Print Loop)**
* **Command parsing** → split user input into command + arguments
* **Built-in commands** → e.g., `cd`, `exit`, `help`
* **Execute external commands** → run system programs like `ls`, `echo`, `pwd`
* **Error handling** → basic handling of invalid commands

## 🚀 Planned Features

* Command pipelines (`ls | grep foo`)
* Input/output redirection (`>`, `<`)
* Environment variables (`$PATH`, `$HOME`)
* Basic scripting support

## 📦 Installation

Clone the repository and build with Cargo:

```bash
git clone https://github.com/velukuberan/shell-in-rust.git
cd shell-in-rust 
cargo build --release
```

Run the shell:

```bash
./target/release/shell-in-rust
```

## 💻 Usage

Once running, you can type commands just like in a Linux shell:

```bash
$ exit
```

## 🛠 Development

Build and run in debug mode:

```bash
cargo run
```

Run tests:

```bash
cargo test
```

## 📚 Learning Goals

* Practice Rust system programming
* Learn about **parsing**, **process management**, and **I/O** in Rust
* Build a foundation for exploring OS-level concepts

## ⚠️ Disclaimer

This is a **learning project**, not a production-ready shell.
Use it for fun, exploration, and learning Rust internals.
