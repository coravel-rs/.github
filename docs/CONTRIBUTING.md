# Contribution Guide

We appreciate your interest in contributing to this project! This document outlines the process for submitting code, documentation, or other types of contributions. Please read and follow these guidelines to ensure a smooth collaboration with the project maintainers.

Before participating in the project, please read our [Code of Conduct](https://github.com/coravel-rs/.github/blob/main/docs/CODE_OF_CONDUCT.md). By engaging with this repository and its respective community, you agree to abide by its terms.

## 💻 Setting up your development environment

1. [Fork](https://github.com/coravel-rs/coravel/fork) the project on _GitHub_ to your own account.
    - If you are new to forking repositories, you can find a detailed guide on forking [here](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
2. Clone your fork to your local development environment:
    ```
    git clone git@github.com:coravel-rs/coravel.git
    cd coravel
    ```
3. Make sure you have the necessary tools installed, such as _Rustup_ toolchain and any dependencies required by the project.

**NOTE:** If you'd like to contribute to our documentation, please use [MyRepos](https://myrepos.branchable.com) tool to clone the project's _Wiki_. You can initiate the clone by running `mr checkout` as configured in the `.mrconfig` file. This will create the sub-repository under the `docs/wiki/` directory, separate from the main repository. To interact with this sub-repository, it's important to familiarize yourself with other `mr` commands.

## 📐 Coding conventions and best practices

When contributing to this project, please adhere to the following guidelines:

1. **Coding Conventions:** Follow established coding conventions. This will ensure that the code is consistent, readable, and maintainable. Before submitting your code, run it through [Rustfmt](https://github.com/rust-lang/rustfmt) for code formatting and [Clippy](https://github.com/rust-lang/rust-clippy) for linting. These tools enforce coding standards, catch common mistakes, and can suggest more idiomatic ways of writing _Rust_. Address any issues or warnings that these tools report before submitting your contribution. Below, you can find comprehensive guides on coding conventions:
    - [Rust Style Guide](https://enso.org/docs/developer/enso/style-guide/rust.html)
    - [Rust API Guidelines](https://rust-lang.github.io/api-guidelines/)
    - [Idiomatic Rust](https://github.com/mre/idiomatic-rust)
2. **Code Refactoring:** Consider using refactoring techniques to improve the structure of existing code without changing its behavior. Familiarize yourself with various design patterns that can make your code more efficient, scalable, and maintainable. You can find comprehensive guides and examples at [Refactoring Guru](https://refactoring.guru/).
3. **Cross-Platform Compatibility:** When writing your _Rust_ code, ensure it is cross-platform compatible. _Rust_ supports a wide range of systems, and it's essential to avoid assumptions or dependencies that tie your code to a specific operating system or environment.
4. **Performance Optimization:** Write efficient and performant code. _Rust_ is well known for its performance, but that doesn't exempt us from good practices. Avoid unnecessary computation, prefer efficient data structures, and leverage _Rust_'s powerful concurrency features when appropriate. Use benchmarking tools like [Criterion.rs](https://github.com/bheisler/criterion.rs) to measure performance objectively.
5. **Testing:** For each functionality you add or change, make sure to create corresponding tests. Tests ensure that your code works as expected and prevents future changes from breaking your functionality. _Rust_’s built-in test framework makes it easy to write unit tests for your code. Run these tests before submitting your changes to ensure they pass.

## 📤 Submitting your contribution

1. Create a new branch for your contribution:
    ```
    git checkout -b feature/your-feature
    ```
2. Make your changes and commit them with a descriptive message:
    ```
    git add .
    git commit -m "Add a brief description of your changes"
    ```
    - Writing clear and concise commit messages is important. For tips on how to write good commit messages, you can refer to [this guide](https://chris.beams.io/posts/git-commit/) tailored for projects following the _Gitflow_ approach.
3. Push your changes to your fork on _GitHub_:
    ```
    git push origin feature/your-feature
    ```
4. Create a pull request on the project's _GitHub_ repository, comparing the project's `develop` branch with your feature branch.
5. Fill out the pull request template with a description of your changes, and reference any relevant issues or discussions.

## 🧐 Review process

After submitting your pull request, the project maintainers will review your contribution. They may request changes or provide feedback before merging your changes into the development branch. Please be patient and address any comments or concerns raised by the maintainers.

<br>

💖 Thank you for your contribution! Your collaboration helps improve the project for everyone.
