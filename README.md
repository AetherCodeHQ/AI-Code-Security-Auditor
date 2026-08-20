# AI Code Security Auditor

![CI](https://github.com/Qyroxen/AI-Code-Security-Auditor/actions/workflows/ci.yml/badge.svg)
![CodeQL](https://github.com/Qyroxen/AI-Code-Security-Auditor/actions/workflows/codeql.yml/badge.svg)
![Go](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Stars](https://img.shields.io/github/stars/Qyroxen/AI-Code-Security-Auditor?style=social)
![Issues](https://img.shields.io/github/issues/Qyroxen/AI-Code-Security-Auditor)
![PRs](https://img.shields.io/github/issues-pr/Qyroxen/AI-Code-Security-Auditor)

> A production-ready CLI tool built with Go

[![Star Badge](https://img.shields.io/github/stars/Qyroxen/AI-Code-Security-Auditor?style=social)](https://github.com/Qyroxen/AI-Code-Security-Auditor/stargazers)

## What is it?

AI Code Security Auditor is a production-ready CLI tool built with Go. It provides powerful functionality with a beautiful terminal interface.

## Features

- Fast and efficient (written in Go)
- Beautiful CLI with colored output
- Comprehensive documentation
- GitHub Actions CI/CD
- CodeQL security analysis
- Dependabot for dependency updates
- MIT Licensed
- Fully offline - zero cloud dependency

## Quick Start

```bash
# Install
git clone https://github.com/Qyroxen/AI-Code-Security-Auditor.git
cd AI-Code-Security-Auditor
go build -o aicodesecurityauditor .

# Run
./aicodesecurityauditor --help
```

## CLI Usage

```bash
# Basic usage
./aicodesecurityauditor

# With flags
./aicodesecurityauditor --verbose --output json

# Get help
./aicodesecurityauditor --help
```

## Examples

```bash
# Example 1
./aicodesecurityauditor example1

# Example 2
./aicodesecurityauditor example2 --flag value
```

## Development

```bash
# Run tests
go test ./...

# Build
go build -o aicodesecurityauditor .

# Lint
golangci-lint run

# Security scan
codeql analyze
```

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Security

For security vulnerabilities, please see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/Qyroxen/AI-Code-Security-Auditor/stargazers">
    <img src="https://img.shields.io/github/stars/Qyroxen/AI-Code-Security-Auditor?style=social" alt="Star this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Code-Security-Auditor/forks">
    <img src="https://img.shields.io/github/forks/Qyroxen/AI-Code-Security-Auditor?style=social" alt="Fork this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Code-Security-Auditor/issues">
    <img src="https://img.shields.io/github/issues/Qyroxen/AI-Code-Security-Auditor" alt="Issues">
  </a>
  <a href="https://github.com/Qyroxen/AI-Code-Security-Auditor/pulls">
    <img src="https://img.shields.io/github/issues-pr/Qyroxen/AI-Code-Security-Auditor" alt="Pull Requests">
  </a>
</p>
