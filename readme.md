# Rust Command-Line Tools

![Rust Logo](https://www.rust-lang.org/static/images/rust-logo-blk.svg)

Welcome to the Rust Command-Line Tools project! This project is inspired by the book ["Command-Line Rust"](https://www.oreilly.com/library/view/command-line-rust/9781098109424/) by Ken Youens-Clark, published by O'Reilly. Here, we build various Unix terminal commands using Rust.

## Project Structure

Each command is contained in its own folder within the project directory. The structure of each command's folder is as follows:

- `src/`: Contains the main executable file(s) for the command.
- `tests/`: Contains test functions to ensure the command works as expected.

## Commands

Below is a list of the commands and their corresponding folders:

- `/echor`: An echo command implementation.
- `/catr`: A catr command implementation.
- `/headr`: A head command implementation.

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/fabiogrillo/command_line_rust.git
   cd command_line_rust
   cd echor
   cargo run echor -- [arguments]
   cargo test