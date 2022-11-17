# Y.Digital Code Quality Standards

## Pre-commit

In all our repositories, we install pre-commit to ensure a minimal level of code quality. Pre-commit applies automatic formatting using `Black`, and applies linting with `Flake8` and some extensions. 

To set things up, install the packages in `.requirements-dev.txt`, and run `pre-commit install`. 

Files:

- `.requirements-dev.txt`: Python packages required to run pre-commit
- `.flake8`: Flake8 linting settings
- `.pre-commit-config.yaml`: Configuration of pre-commit