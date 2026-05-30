# Contributing to ForgeX

Thank you for your interest in contributing to ForgeX!

ForgeX is a modern Blender toolkit focused on GTA V and FiveM asset creation, optimization, validation, and resource generation. Every contribution helps improve the experience for creators around the world.

If you have questions about development or would like to discuss new features, improvements, or project ideas, please join the ForgeX community.

---

# Table of Contents

* Code of Conduct
* Ways to Contribute

  * Reporting Bugs
  * Feature Requests
  * Documentation
  * Pull Requests
* Getting Started

  * Development Setup
  * Testing
  * Debugging
* Coding Standards
* Commit Guidelines
* License

---

# Code of Conduct

All contributors are expected to follow the ForgeX Community Code of Conduct.

We strive to maintain a welcoming, respectful, and collaborative environment for everyone.

---

# Ways to Contribute

## Reporting Bugs

Found a bug?

Please create a detailed issue report including:

* Steps to reproduce
* Blender version
* ForgeX version
* Screenshots
* Error logs
* Example assets when possible

The more information provided, the easier it will be to diagnose and resolve the issue.

---

## Feature Requests

Have an idea that could improve ForgeX?

Feature requests are encouraged.

Examples include:

* New FiveM workflows
* Vehicle tools
* Clothing tools
* Weapon workflows
* Performance improvements
* UI enhancements
* Automation systems

Please create a feature request issue and describe your idea in as much detail as possible.

---

## Documentation

Documentation improvements are always welcome.

You can contribute by:

* Fixing documentation errors
* Writing tutorials
* Creating workflow guides
* Expanding API documentation
* Producing beginner-friendly learning resources

---

## Pull Requests

We welcome pull requests from contributors of all experience levels.

### Workflow

1. Fork the repository.
2. Create a new branch from `main`.
3. Make your changes.
4. Test your changes.
5. Write clear commit messages.
6. Submit a pull request.

The ForgeX team will review submissions and provide feedback when necessary.

---

# Getting Started

## Clone the Repository

```bash
git clone https://github.com/ForgeX/ForgeX.git
cd ForgeX
```

## Blender Development Setup

Install ForgeX as a Blender addon.

Creating a symbolic link is recommended during development so updates are automatically available when Blender restarts.

```powershell
# Example Addons Directory
C:\Users\<user>\AppData\Roaming\Blender Foundation\Blender\4.0\scripts\addons
```

Create a symbolic link to your ForgeX development folder.

Restart Blender and enable ForgeX from the Add-ons menu.

---

# Testing

ForgeX uses automated testing where practical.

While tests are not required for every contribution, they are highly encouraged.

To run tests:

```powershell
python -m pytest
```

Additional testing tools may be added as ForgeX evolves.

---

# Debugging

ForgeX supports remote debugging for development builds.

Recommended tools:

* debugpy
* Visual Studio Code
* PyCharm

Example:

```powershell
pip install debugpy
```

Debugging configuration options may be found within the developer documentation.

---

# Coding Standards

ForgeX follows:

* PEP 8
* Maximum line length of 120 characters
* Clear naming conventions
* Readable and maintainable code

Please avoid reformatting unrelated code when submitting changes.

Focus only on the files relevant to your contribution.

---

# Commit Guidelines

ForgeX follows Conventional Commits.

Examples:

```text
feat: add automatic vehicle collision generator

fix: resolve texture export issue

refactor: improve drawable validation system

docs: update clothing workflow guide
```

Meaningful commit messages help maintain project history and generate release notes.

---

# Vision

ForgeX aims to become the complete Blender-to-FiveM creation suite.

Our goal is to eliminate unnecessary external tools by providing:

* Asset Creation
* Validation
* Optimization
* Resource Packaging
* Direct FiveM Export

All within a single workflow.

---

# Maintainers

ForgeX Development Team

Lead Developers:

* Kai
* Bobby

---

# License

By contributing to ForgeX, you agree that your contributions will be licensed under the project's license and distributed according to the terms of that license.

Thank you for helping build the future of FiveM asset creation.
