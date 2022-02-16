# Rust Learning

Reference: [The Rust Programming Language](https://doc.rust-lang.org/book/#the-rust-programming-language)

## Introduction

> **Rust developer tools**
> 
> - **Cargo**: dependency manager and build tool
> - **Rustfmt**: ensures a consistent coding style across developers
> - **Rust Language Server**: powers Integrated Development Environment (IDE) integration for code completion and inline error messages.

### Installation

#### Install

Download and install [rustup](https://static.rust-lang.org/rustup/dist/x86_64-pc-windows-msvc/rustup-init.exe). `rustup` installs `rustc`, `cargo`, `rustup` and other standard tools to Cargo's `bin` directory. On Unix it is located at `$HOME/.cargo/bin` and on Windows at `%USERPROFILE%\.cargo\bin`. This is the same directory that `cargo install` will install Rust programs and Cargo plugins.

> **rustup**: a command line tool for managing Rust versions and associated tools

> On windows, you also need the [C++ build tools](https://visualstudio.microsoft.com/zh-hans/visual-cpp-build-tools/), and don't need to install visual studio.

#### Updating and Uninstalling

```console
$ rustup update
```

```console
$ rustup self uninstall
```
