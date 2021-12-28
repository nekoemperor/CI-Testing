# Continuous Integration
Continuous Integration (CI) with GitHub Actions and Python - Part 2: Testing
- Continuous Integration (CI) with GitHub Actions and Python - Part 1: Linting. [Link](https://github.com/nekoemperor/CI-Linting)
- Continuous Integration (CI) with GitHub Actions and Python - Part 3: Code Coverage with Pytest. [Link](https://github.com/nekoemperor/CI-Code-Coverage-Pytest)

## Description
This repo serves as a reference for the following [YouTube video](https://www.youtube.com/watch?v=rY-igT2N8zU&list=PL0dOL8Z7pG3J6t1pqRQiNarBGY-ZnIJcq&index=2).

Demonstration of how to incorporate continuous integration (CI) into a Python project using:

1. linting
2. testing

The linting is handled by a custom GitHub Action [`pylinter`](https://github.com/marketplace/actions/pylinter). The testing is handled by pytest.

## Contents
* `.py` simplistic files to lint with the GitHub Action `pylinter` and test with `pytest`
* `tests/` directory which contains the various `pytest` tests to run
* `requirements.txt` which contains the necessary packages to run the CI
