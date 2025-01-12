# Security Scanning Workflows Repository

This repository, curated by Folarin, houses centralized GitHub Actions workflows for security scanning and vulnerability management.

## Available Security Scanners

### Gitleaks
- Purpose: Scans repositories for sensitive information and secrets
- Workflow: Automatically detects hardcoded credentials, API keys, and tokens in code

### Semgrep
- Purpose: Static Application Security Testing (SAST) tool
- Workflow: Analyzes source code for security vulnerabilities, bugs, and code patterns

### Dependabot
- Purpose: Dependency vulnerability scanner
- Workflow: Monitors dependencies for known security vulnerabilities and creates automated PRs for updates

## Automated Response

The repository includes a workflow that automatically pushes images to Amazon ECR when any of the above scanning tools detects vulnerabilities in the target codebase, ensuring proper tracking and management of affected artifacts.

## Usage

Each workflow can be referenced and reused across different projects to maintain consistent security scanning practices.
