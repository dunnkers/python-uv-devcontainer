# python-uv-devcontainer

Python project setup using a [Devcontainer](https://containers.dev) and [uv](https://github.com/astral-sh/uv).

## Features

- [x] [Devcontainer](https://github.com/devcontainers/images/tree/main/src/python) running Python 3.13
- [x] [uv](https://github.com/astral-sh/uv) for dependency management and virtual environment management
- [x] [pytest](https://docs.pytest.org/en/stable/) for testing
- [x] [ruff](https://github.com/astral-sh/ruff) for formatting and linting
- [x] [GitHub Actions](https://github.com/dunnkers/python-uv-devcontainer/actions) for CI/CD
- [x] [Dockerfile](https://github.com/dunnkers/python-uv-devcontainer/blob/main/Dockerfile) for easy deployment
<img width="222" alt="Screenshot 2025-04-25 at 10 57 33" src="https://github.com/user-attachments/assets/45df28b9-9210-4cd4-a6c5-25ad3c8edb55" />
<img width="577" alt="Screenshot 2025-04-24 at 11 59 28" src="https://github.com/user-attachments/assets/c89c6643-768b-427d-b10f-a51ddbe76282" />
<img width="1484" alt="Screenshot 2025-04-23 at 18 28 17" src="https://github.com/user-attachments/assets/a903022c-e53f-401c-bb8d-8a7c01bfdaad" />
<img width="856" alt="Screenshot 2025-04-23 at 18 24 49" src="https://github.com/user-attachments/assets/52130b2d-5c1d-43c6-9862-b7bdbd6fe5fe" />
<img width="800" alt="Screenshot 2025-04-23 at 18 11 34" src="https://github.com/user-attachments/assets/2394a9b6-0cb0-494b-b580-31d5cbfc8a3f" />
<img width="484" alt="Screenshot 2025-04-23 at 18 10 07" src="https://github.com/user-attachments/assets/61bd1aa5-9154-4c42-b192-8b674c7e3d80" />
<img width="1331" alt="Screenshot 2025-04-23 at 18 06 47" src="https://github.com/uaser-attachments/assets/e869e370-87cd-4788-8ae9-a049e15af02f" />
<img width="848" alt="Screenshot 2025-04-23 at 18 03 49" src="https://github.com/user-attachments/assets/21761957-ae2f-4e99-9378-d8920f5c6a19" />
<img width="846" alt="Screenshot 2025-04-23 at 18 00 10" src="https://github.com/user-attachments/assets/28dceed1-abb2-4be5-aa25-ff1c8ad38455" />
<img width="744" alt="Screenshot 2025-04-23 at 17 53 28" src="https://github.com/user-attachments/assets/3efa1de7-5bd3-4b1e-aaa8-455773396c81" />
<img width="425" alt="Screenshot 2025-04-23 at 17 19 10" src="https://github.com/user-attachments/assets/3aa1891b-d19b-4c8e-acad-b5e46eb18250" />

## Setup

1. **Use this template**

    <a href="https://github.com/new?template_name=python-uv-devcontainer&template_owner=dunnkers"><img src="https://github.com/user-attachments/assets/45df28b9-9210-4cd4-a6c5-25ad3c8edb55" alt="Use this template and create new repository" width="250"/></a>
    
    [Create a new repository](https://github.com/new?template_name=python-uv-devcontainer&template_owner=dunnkers) based on this template.

2. **Clone repo**

    <img src="https://github.com/user-attachments/assets/3aa1891b-d19b-4c8e-acad-b5e46eb18250" alt="Clone repository" width="375"/>

    Open the repo in VSCode.

    > [!TIP]
    > This Devcontainer can also be directly used with a GitHub Codespace.
    >
    > [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/dunnkers/python-uv-devcontainer?quickstart=1)

3. **Reopen in Container**

    Click the button in the popup upon opening the repo:
    
    <img src="https://github.com/user-attachments/assets/c89c6643-768b-427d-b10f-a51ddbe76282" alt="Dev Containers: Reopen in Container" width="475"/>

    Alternatively, enter <kbd>Ctrl+Shift+P</kbd> and select **Dev Containers: Reopen in Container**.

4. **Wait for setup to finish**

    Upon opening the Devcontainer, setup will start. Wait for the setup to finish before continuing.

    <img src="https://github.com/user-attachments/assets/28dceed1-abb2-4be5-aa25-ff1c8ad38455" alt="Wait for postCreateCommand to finish" width="600"/>

5. **Select Python interpreter**

    Enter <kbd>Ctrl+Shift+P</kbd> and select **Python: Select Interpreter**. 

    <img src="https://github.com/user-attachments/assets/3efa1de7-5bd3-4b1e-aaa8-455773396c81" alt="VSCode: Python Select Interpreter" width="500"/>

    Select the **venv** (`./.venv/bin/python`).

6. **Enjoy 🫶**

    You now have a fully configured Python development environment!

    ![alt text](https://github.com/user-attachments/assets/a903022c-e53f-401c-bb8d-8a7c01bfdaad)

    with `uv`:

    <img src="https://github.com/user-attachments/assets/52130b2d-5c1d-43c6-9862-b7bdbd6fe5fe" width="700"/>

    and `pytest`:

    | UI | Terminal |
    |:--:|:--:|
    | ![alt text](https://github.com/user-attachments/assets/61bd1aa5-9154-4c42-b192-8b674c7e3d80) | ![alt text](https://github.com/user-attachments/assets/2394a9b6-0cb0-494b-b580-31d5cbfc8a3f) |

    ... and `ruff`:

    <img src="https://github.com/user-attachments/assets/21761957-ae2f-4e99-9378-d8920f5c6a19" width="700"/>

    all readily available 🎉

## Extras

- **CI/CD with GitHub Actions**

    [A workflow](https://github.com/dunnkers/python-uv-devcontainer/blob/main/.github/workflows/python_app.yaml) is already set up for you.

    <img width="1331" alt="GitHub Actions workflow for testing, formatting and linting a Python app with uv" src="https://github.com/user-attachments/assets/e869e370-87cd-4788-8ae9-a049e15af02f" />

    This workflow runs tests using `pytest` and formatting + linting using `ruff`. Dependencies are set up with `uv`. 

- **Dockerfile**

    A [Dockerfile](https://github.com/dunnkers/python-uv-devcontainer/blob/main/Dockerfile) is provided for easy deployment. This Dockerfile uses the same base image as the Devcontainer, so you can be sure it will work in production.


## About

Provided to you with ♡ by [Jeroen Overschie](https://jeroenoverschie.nl/).
