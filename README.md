# QSA
Questionable Script Agent - Keeping you safe while vibe coding all night.  Sort of.  No guarantees, much like the real TSA.

What it does
QSA automatically reviews your code for:

Security vulnerabilities (SQL injection, XSS, etc.)
Hardcoded secrets or credentials
Input validation issues
Error handling improvements
Code quality and best practices
CI/CD Integration

Add the included GitHub Actions workflow to automatically scan and fix issues on every push:

Copy .github/workflows/quantic-spark-agent.yml to your repo
Add CURSOR_API_KEY to your repository secrets
Push to main or develop — fixes are auto-submitted as PRs

Usage

qs-agent --task "Fix security vulnerabilities in this codebase"

Aliases: agent, cursor-agent

License
MIT
