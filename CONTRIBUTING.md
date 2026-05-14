# Contributing to MemeMF

Thank you for your interest in contributing to MemeMF! This document provides guidelines for reporting bugs, suggesting features, and submitting pull requests.

## 🐛 Reporting Bugs

Found a bug? Help us improve by reporting it!

### Before Submitting a Bug Report

- Check if the bug has already been reported in [Issues](https://github.com/S0HAM03/MemeMF/issues).
- Check the [README](README.md) and documentation for any relevant setup notes.
- Ensure you're using **Unreal Engine 5.7** or later with **Git LFS** properly installed.

### How to Submit a Bug Report

Open an issue and include:

- **Clear title**: Describe the bug in one sentence.
- **Steps to reproduce**: Detailed steps to reproduce the issue.
- **Expected behavior**: What should happen.
- **Actual behavior**: What actually happens.
- **System info**: UE version, OS, GPU (if applicable).
- **Screenshots/logs**: Attach error logs or screenshots if helpful.

**Example:**
```
Title: Game crashes when interacting with hospital bed

Steps to Reproduce:
1. Start a new game
2. Navigate to hospital wing
3. Click on the bed

Expected: Interaction animation plays
Actual: Game crashes with error log

System: UE 5.7, Windows 11, RTX 4090
```

## ✨ Suggesting Features

Have an idea to make MemeMF more chaotic and entertaining?

### Before Submitting a Feature Request

- Check if it's already been suggested in [Issues](https://github.com/S0HAM03/MemeMF/issues).
- Make sure it aligns with the project's chaotic, comedy-parody vibe.

### How to Submit a Feature Request

Open an issue with:

- **Clear title**: Short description of the feature.
- **Motivation**: Why this feature would be cool/important.
- **Proposed solution**: How you'd implement it (if you have ideas).
- **Alternative approaches**: Other ways to achieve the same goal.

**Example:**
```
Title: Add randomized jump scares to hospital encounters

Motivation: Would enhance the unpredictable "fever dream" feel

Proposed solution: Add a StateTree branch that randomly triggers jump scare events
```

## 🔧 Submitting Pull Requests

Want to contribute code? Great!

### Before You Start

1. **Fork** the repository.
2. **Create a branch**: `git checkout -b feature/your-feature-name`
3. **Make your changes**: Follow UE5 coding best practices.
4. **Test thoroughly**: Ensure your changes don't break existing functionality.

### Creating a Pull Request

1. Push your branch to your fork.
2. Open a **Pull Request** with:
   - **Clear title**: What does this PR do?
   - **Description**: Why these changes? What problems do they solve?
   - **Related issues**: Link to any related issues (e.g., `Fixes #123`).
   - **Testing notes**: How to test your changes.

### PR Guidelines

- **Small PRs are preferred**: Easier to review and merge.
- **Follow UE5 conventions**: Use existing code style as reference.
- **Comment complex logic**: Explain non-obvious decisions.
- **No breaking changes** without discussion in an issue first.
- **Update documentation** if your changes affect README or setup.

### Review Process

- Maintainer will review your PR within a reasonable timeframe.
- Feedback may be requested—please address it.
- Once approved, your PR will be merged!

## 📋 Development Workflow

If you want to work on this project:

1. **Clone**: `git clone https://github.com/S0HAM03/MemeMF.git`
2. **Initialize LFS**: `git lfs install && git lfs pull`
3. **Open in UE5**: Double-click `MemeMF.uproject`
4. **Make changes** in your local branch
5. **Test** in the editor before committing
6. **Commit** with clear, descriptive messages
7. **Push** and create a PR

## 📄 Code of Conduct

- Be respectful and constructive in all interactions.
- Assume good intent from others.
- Help foster a welcoming community.

## ❓ Questions?

Feel free to:
- Open an issue with the `question` label.
- Check existing issues and discussions for answers.
- Reach out to [S0HAM03](https://github.com/S0HAM03).

---

**Thanks for helping make MemeMF even more chaotic!** 🎭
