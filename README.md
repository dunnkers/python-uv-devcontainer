# python-uv-devcontainer

Python project setup using a [Devcontainer](https://containers.dev) and [uv](https://github.com/astral-sh/uv).

## Features

- [x] [Devcontainer](https://github.com/devcontainers/images/tree/main/src/python) running Python 3.13
- [x] [uv](https://github.com/astral-sh/uv) for dependency management and virtual environment management
- [x] [pytest](https://docs.pytest.org/en/stable/) for testing
- [x] [ruff](https://github.com/astral-sh/ruff) for formatting and linting
- [x] [GitHub Actions](https://github.com/dunnkers/python-uv-devcontainer/actions) for CI/CD
- [x] [Dockerfile](https://github.com/dunnkers/python-uv-devcontainer/blob/main/Dockerfile) for easy deployment


## Setup

1. **Clone this repo**

    <img src="docs/Screenshot 2025-04-23 at 17.19.10.png" alt="Clone repository" width="350"/>

    Open the repo in VSCode.

2. **Reopen in Container**

    Click the button in the popup upon opening the repo:
    
    <img src="docs/Screenshot 2025-04-24 at 11.59.28.png" alt="Dev Containers: Reopen in Container" width="500"/>

    Alternatively, enter <kbd>Ctrl+Shift+P</kbd> and select **Dev Containers: Reopen in Container**.

3. **Wait for setup to finish**

    Upon opening the Devcontainer, setup will start. Wait for the setup to finish before continuing.

    <img src="docs/Screenshot 2025-04-23 at 18.00.10.png" alt="Wait for postCreateCommand to finish" width="500"/>

4. **Select Python interpreter**

    Enter <kbd>Ctrl+Shift+P</kbd> and select **Python: Select Interpreter**. 

    <img src="docs/Screenshot 2025-04-23 at 17.53.28.png" alt="VSCode: Python Select Interpreter" width="500"/>

    Select the **venv** (`./.venv/bin/python`).

5. **Enjoy 🫶**

    You now have a fully configured Python development environment!

    ![alt text](<docs/Screenshot 2025-04-23 at 18.28.17.png>)

    with `uv`:

    <img src="docs/Screenshot 2025-04-23 at 18.24.49.png" width="600"/>

    and `pytest`:

    | UI | Terminal |
    |:--:|:--:|
    | ![alt text](<docs/Screenshot 2025-04-23 at 18.10.07.png>) | ![alt text](<docs/Screenshot 2025-04-23 at 18.11.34.png>) |

    ... and `ruff`:

    <img src="docs/Screenshot 2025-04-23 at 18.03.49.png" width="600"/>

    all readily available 🎉

## Extras

- **CI/CD with GitHub Actions**

    [A workflow](https://github.com/dunnkers/python-uv-devcontainer/blob/main/.github/workflows/python_app.yaml) is already set up for you.

    ![alt text](<docs/Screenshot 2025-04-23 at 18.06.47.png>)

    This workflow runs tests using `pytest` and formatting + linting using `ruff`. Dependencies are set up with `uv`. 

- **Dockerfile**

    A [Dockerfile](https://github.com/dunnkers/python-uv-devcontainer/blob/main/Dockerfile) is provided for easy deployment. This Dockerfile uses the same base image as the Devcontainer, so you can be sure it will work in production.


## About

Provided to you with ♡ by [Jeroen Overschie](https://jeroenoverschie.nl/).