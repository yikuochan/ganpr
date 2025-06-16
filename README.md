# GANPR - GitHub Actions and OpenAI PR Review

This repository demonstrates the use of GitHub Actions with OpenAI's GPT models to automatically review pull requests.

## Features

- Automated code review using OpenAI's GPT models
- Python unit testing with pytest
- Code coverage reporting

## Setup

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run tests: `pytest`

## GitHub Actions Workflow

This repository includes a GitHub Actions workflow that:

1. Runs on pull requests to the main branch
2. Sets up Python and installs dependencies
3. Runs tests with code coverage
4. Uses OpenAI's API to review code changes
5. Comments on the PR with the AI review and test results

## Usage

To test the workflow:
1. Create a new branch
2. Make changes to the code
3. Create a pull request to the main branch
4. Wait for the GitHub Action to run and provide feedback