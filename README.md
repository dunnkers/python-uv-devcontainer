# python-uv-devcontainer

Python project setup using a [Devcontainer](https://containers.dev) and [uv](https://github.com/astral-sh/uv).

## Features

- [x] [Devcontainer](https://github.com/devcontainers/images/tree/main/src/python) running Python 3.13
- [x] [uv](https://github.com/astral-sh/uv) for dependency management and virtual environment management
- [x] [ruff](https://github.com/astral-sh/ruff) for formatting and linting
- [x] [pytest](https://docs.pytest.org/en/stable/) for testing
- [x] [Dockerfile](https://github.com/dunnkers/python-uv-devcontainer/blob/main/Dockerfile) for easy deployment
- [x] [GitHub Actions](https://github.com/dunnkers/python-uv-devcontainer/actions) for CI/CD


## Setup

1. **Clone this repo**

    <img src="docs/Screenshot 2025-04-23 at 17.19.10.png" alt="Clone repository" width="400"/>
2. **Reopen in Container**

    Click the button in the popup upon opening the repo:

    ![alt text](<docs/Screenshot 2025-04-23 at 17.20.22.png>)

    Alternatively, enter <kbd>Ctrl+Shift+P</kbd> and select **Dev Containers: Reopen in Container**.

    Upon opening the Devcontainer, setup will start. Wait for the setup to finish.

    ![alt text](<docs/Screenshot 2025-04-23 at 18.00.10.png>)

3. **Select Python interpreter**

    Enter <kbd>Ctrl+Shift+P</kbd> and select **Python: Select Interpreter**. 

    <img src="docs/Screenshot 2025-04-23 at 17.53.28.png" alt="VSCode: Python Select Interpreter" width="500"/>

    Select the **venv** (`./.venv/bin/python`).

4. **Enjoy 🫶**

    You now have a fully configured Python development environment with uv!

    ![alt text](<docs/Screenshot 2025-04-23 at 17.29.45.png>)

    ... with pytest:

    ![alt text](<docs/Screenshot 2025-04-23 at 17.58.16.png>)

    ... and tooling like `ruff` and `uv` readily available:

    <img src="docs/Screenshot 2025-04-23 at 18.03.49.png" width="500"/>

    ... and CI/CD set up with GitHub Actions:

    ![alt text](<docs/Screenshot 2025-04-23 at 18.06.47.png>)

    Good luck developing! 🍀

    🎉

## About

Provided to you with ♡ by [Jeroen Overschie](https://jeroenoverschie.nl/).