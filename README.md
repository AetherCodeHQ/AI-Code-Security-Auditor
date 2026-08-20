# AI Code Security Auditor

![CI](https://github.com/Qyroxen/AI-Code-Security-Auditor/actions/workflows/ci.yml/badge.svg) ![Go](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go) ![License](https://img.shields.io/badge/License-MIT-yellow.svg) ![Stars](https://img.shields.io/github/stars/Qyroxen/AI-Code-Security-Auditor?style=social)

> Security audit your codebase with AI - find vulnerabilities before hackers do

[![Star Badge](https://img.shields.io/github/stars/Qyroxen/AI-Code-Security-Auditor?style=social)](https://github.com/Qyroxen/AI-Code-Security-Auditor/stargazers)

## What is it?

AI Code Security Auditor performs deep security analysis using local LLM. Identifies vulnerabilities, misconfigurations, and security anti-patterns.

## Why should you care?

Security vulnerabilities cost companies millions. This tool finds them before they're exploited.

## Demo

```bash
./ai-code-security-audit audit --path ./my-project
```

**Output:**
```
Security Audit Report:
  CRITICAL: SQL Injection in auth.go:67
  HIGH: Hardcoded API key in config.go:12
  MEDIUM: Weak password validation in user.go:34
```

## Features

- Comprehensive security analysis
- OWASP Top 10 detection
- Custom security rules
- PDF/HTML report generation
- CI/CD integration ready

## Quick Start

```bash
# Install
git clone https://github.com/Qyroxen/AI-Code-Security-Auditor.git
cd AI-Code-Security-Auditor
go build -o ai-code-security-audit .

# Run
./ai-code-security-audit --path ./my-project
```

## CLI Flags

| Flag | Description | Default |
|------|-------------|---------|
| `--path` | Target directory | `.` |
| `--rules` | Custom rules file | `default` |
| `--output` | Report format (pdf, html, json) | `json` |
| `--compliance` | Check against standards (OWASP, NIST) | `owasp` |

## Examples

# Basic audit
./ai-code-security-audit audit --path ./src

# OWASP compliance check
./ai-code-security-audit audit --path ./src --compliance owasp

# Generate PDF report
./ai-code-security-audit audit --path ./src --output pdf

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/Qyroxen/AI-Code-Security-Auditor/stargazers">
    <img src="https://img.shields.io/github/stars/Qyroxen/AI-Code-Security-Auditor?style=social" alt="Star this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Code-Security-Auditor/network/members">
    <img src="https://img.shields.io/github/forks/Qyroxen/AI-Code-Security-Auditor?style=social" alt="Fork this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Code-Security-Auditor/issues">
    <img src="https://img.shields.io/github/issues/Qyroxen/AI-Code-Security-Auditor" alt="Issues">
  </a>
</p>
