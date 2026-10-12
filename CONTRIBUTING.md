# Contributing to MLTradeBot

Thank you for your interest in contributing to **MLTradeBot**! We welcome quantitative researchers, ML engineers, developers, and trading enthusiasts to collaborate.

---

## 🧭 Code of Conduct
We are committed to providing a welcoming, inclusive, and harassment-free environment for everyone. Please be respectful and constructive in all discussions, pull requests, and code reviews.

---

## 🛠️ How to Contribute

### 1. Reporting Issues & Proposing Features
- Search existing issues to ensure your topic hasn't already been discussed.
- If reporting a bug, provide:
  - Clear steps to reproduce.
  - Expected vs. actual behavior.
  - Relevant logs, exchange responses, and system information.
- If proposing an alpha factor, strategy, or infrastructure improvement, describe the mathematical/engineering rationale and trade-offs.

### 2. Developing Code
1. Fork the target repository (e.g., `mltrade-core`, `ml-pipelines`, `model-serving`).
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Follow the project's formatting and linting conventions:
   ```bash
   uv run ruff check .
   uv run ruff format .
   ```
4. Write tests for new functionality using `pytest`:
   ```bash
   uv run pytest
   ```

### 3. Submitting Pull Requests
- Keep PRs focused on a single logical change.
- Reference related issues in your PR description.
- Ensure all CI tests and lint checks pass before requesting review.

---

## ⚠️ Important Note on Financial Strategies
We do not accept hardcoded API keys, private trading secrets, or unregulated automated execution exploits. All strategy contributions should be designed around clean abstractions, backtested metrics, and configurable risk boundaries.
