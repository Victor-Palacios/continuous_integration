# CI Application

A simple CI/CD project demonstrating GitHub Actions for continuous integration.

## Setup

1. Create a virtual environment:
tell agent, "create a venv called mlops that I can activate by just typing "activate" into the terminal - don't use bash"

2. Activate the virtual environment:
```bash
activate  # On macOS/Linux
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## CI/CD

This project uses GitHub Actions for continuous integration. The CI workflow:
- Runs on push and pull requests to main branches
- Tests against Python 3.10, and 3.11
- Installs dependencies and verifies imports

## Pushing to GitHub

1. Create a new repository on GitHub (don't initialize with README, .gitignore, or license)

After pushing, check the Actions tab in your GitHub repository to see the CI workflow running.