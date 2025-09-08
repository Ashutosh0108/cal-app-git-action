## GitHub Actions CI Pipeline

This repository uses GitHub Actions to automatically build and test code on every push to `main`.

Workflow file: `.github/workflows/main.yml`

Steps:
1. Pull latest code
2. Set up Python 3.13
3. Install dependencies from `requirements.txt`
4. Run all unit tests
