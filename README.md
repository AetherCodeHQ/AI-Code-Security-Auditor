# AI Code Security Auditor

AI-based security auditor that scans codebases for vulnerabilities and generates comprehensive security reports.

[![Go Version](https://img.shields.io/badge/Go-1.23%2B-00ADD8?style=flat&logo=go)](https://go.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![CI](https://github.com/Qyroxen/ai-code-security-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/Qyroxen/ai-code-security-auditor/actions/workflows/ci.yml)

> AI-based security auditor that scans codebases for vulnerabilities and generates comprehensive security reports.

## What is it?

AI Code Security Auditor is a command-line tool built with Go that helps developers ai-based security auditor that scans codebases for vulnerabilities and generates comprehensive security reports. It's designed to be fast, reliable, and easy to use.

## Why?

Every developer needs ai code security auditor — but existing tools are either too complex, too slow, or require cloud dependencies. We built AI Code Security Auditor to be:
- **Fast** — Written in Go for maximum performance
- **Offline** — No cloud dependencies, your data stays on your machine
- **Simple** — Clean CLI interface with sensible defaults
- **Extensible** — Easy to customize and integrate into your workflow

## Features

- **AI-driven vulnerability detection** — AI-driven vulnerability detection
- **OWASP Top 10 coverage** — OWASP Top 10 coverage
- **Risk scoring with severity levels** — Risk scoring with severity levels
- **Remediation suggestions powered by LLMs** — Remediation suggestions powered by LLMs
- **CI/CD integration support** — CI/CD integration support
- **Zero cloud dependency** — Zero cloud dependency

## Quick Start

### Prerequisites

- Go 1.23 or later

### Install

```bash
# Install with go install
go install github.com/Qyroxen/ai-code-security-auditor@latest

# Or build from source
git clone https://github.com/Qyroxen/ai-code-security-auditor.git
cd ai-code-security-auditor
go build -o ai-code-security-auditor .
```

### Usage

```bash
# Basic usage
.ai-code-security-auditor --help

# Example
./ai-code-security-auditor audit --path ./app --format json
```

## Output

```
AI Code Security Auditor v1.0.0

Scanning...

✓ Analysis complete
✓ Results ready

{
  "status": "success",
  "results": [...]
}
```

## Configuration

Create a `.config.yaml` file in your project root:

```yaml
# Configuration options
verbose: true
output: json
timeout: 30s
```

## CLI Flags

```
ai code security auditor [command]

Flags:
  --path string      Target path (default ".")
  --format string    Output format: json, text (default "text")
  --verbose          Enable verbose output
  --config string    Config file path
  --output string    Output file path
```

## Examples

### Basic Example

```bash
.ai-code-security-auditor --path ./src
```

### Advanced Example

```bash
.ai-code-security-auditor --path ./src --format json --output report.json --verbose
```

### CI/CD Integration

```yaml
# .github/workflows/ci.yml
- name: Run AI Code Security Auditor
  run: |
    go install github.com/Qyroxen/ai-code-security-auditor@latest
    ai-code-security-auditor --path . --format json --output report.json
```

## Documentation

- [Getting Started](docs/getting-started.md)
- [Configuration](docs/configuration.md)
- [API Reference](docs/api-reference.md)
- [Examples](examples/)
- [Contributing](CONTRIBUTING.md)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Qyroxen** - [GitHub](https://github.com/Qyroxen)

---

**Found this useful?** Give it a ⭐ on GitHub!
