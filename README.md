## GitHub Actions CI Pipeline
## 📄 Overview

This project demonstrates the use of GitHub Actions to set up a Continuous Integration (CI) pipeline for a simple Python application.

GitHub Actions is an automation service provided by GitHub that allows you to build, test, and deploy code directly from your repository.
A CI pipeline automatically checks your code whenever changes are pushed, ensuring that the codebase remains clean, functional, and error-free.

## ⚙️ Project Description

I created a basic Python project that includes two simple mathematical functions — addition and subtraction — along with corresponding test cases written using pytest.
The workflow automatically installs dependencies, performs linting with flake8, and runs tests whenever code is pushed or a pull request is made to the main branch.

## 🚀 Steps I Followed

Created a new GitHub repository and cloned it to my system.

Built a small Python project with add and sub functions.

Wrote test cases using pytest to verify the functions.

Listed all dependencies in a requirements.txt file.

Created a workflow file at .github/workflows/main.yml to:

Trigger on pushes and pull requests to main.

Set up Python 3.10 on an Ubuntu runner.

Install dependencies.

Run linting and testing automatically.

Committed and pushed all files to GitHub.

Verified the pipeline execution from the Actions tab — confirming all steps ran successfully.

## ✅ Outcome

The CI pipeline ensures that every new change is automatically tested and linted before merging, maintaining code quality and reliability.
This setup demonstrates how GitHub Actions can automate routine development tasks and streamline the testing process for any Python-based project.
