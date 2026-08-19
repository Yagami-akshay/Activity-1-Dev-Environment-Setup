### Activity 1: Development Environment Setup Note

1. Configured a local C/C++ development environment on macOS using Visual Studio Code and the Apple Clang compiler.
2. Verified the compiler toolchain using Xcode Command Line Tools via `xcode-select --install` and confirmed the `gcc --version` output in the zsh terminal.
3. Installed the Microsoft C/C++ extension pack within VS Code to enable IntelliSense, syntax highlighting, and debugging features.
4. Created the project directory structure under `Documents/PortfolioBuilding/Activity1` and authored the initial `hello.c` source file.
5. Encountered an initial issue where `.exe` binary formats from Windows guides are not executable on macOS.
6. Resolved this by adapting the compilation command to `gcc hello.c -o hello` and executing the binary with `./hello`.
7. Successfully compiled and verified the program execution with the standard "Hello, World!" terminal output.
