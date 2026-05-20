# Contributing to xgov-qe-principles

We welcome contributions from everyone! This document provides guidance on how to contribute to this project.

## How to Raise a Pull Request

### Step 1: Fork the Repository

1. Go to the [xgov-qe-principles repository](https://github.com/Testing-AI-Standards/xgov-qe-principles)
2. Click the **Fork** button in the top-right corner
3. This creates a copy of the repository under your GitHub account

### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/xgov-qe-principles.git
cd xgov-qe-principles
```

### Step 3: Create a New Branch

Always create a branch for your work:

```bash
git checkout -b descriptive-branch-name
```

Use clear branch names, e.g.: `fix-typo-principles`, `add-examples`, `update-rationale`

### Step 4: Make Your Changes

Edit the markdown files with your improvements. Our standards check includes:

- **Markdown linting** — proper formatting and structure
- **Spell checking** — correct spelling and grammar
- **Broken link checking** — no dead links

Ensure your changes align with these standards.

### Step 5: Commit Your Changes

```bash
git add .
git commit -m "Descriptive commit message"
```

Use clear, concise commit messages (e.g., "Fix typo in principle 3", "Add rationale examples").

### Step 6: Push to Your Fork

```bash
git push origin descriptive-branch-name
```

### Step 7: Open a Pull Request

1. Go to your fork on GitHub
2. You'll see a **"Compare & pull request"** button
3. Click it and fill in:
   - **Title**: Brief description of your changes
   - **Description**: Explain what you changed and why
4. Click **"Create pull request"**

## Pull Request Guidelines

- **One feature per PR** — keep changes focused and easy to review
- **Reference issues** — if fixing a specific issue, mention it (e.g., "Fixes #123")
- **Clear description** — explain the problem and your solution
- **Pass all checks** — your PR must pass markdown lint, spell check, and link validation
- **Be patient** — maintainers will review and provide feedback

## What Happens After You Submit

1. Our automated checks run (markdown lint, spell check, broken link check)
2. A maintainer reviews your PR
3. They may request changes or approve it
4. Once approved, your changes are merged into `main`

## Questions?

Feel free to:

- Open an [Issue](https://github.com/Testing-AI-Standards/xgov-qe-principles/issues) to discuss ideas
- Ask questions in your PR
- Check existing discussions for answers

Thank you for contributing! 🙌
