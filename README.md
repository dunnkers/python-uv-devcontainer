# python-uv-devcontainer

Python project setup using a [Devcontainer](https://containers.dev) and [uv](https://github.com/astral-sh/uv).

## Setup

1. **Clone this repo**

    <img src="docs/Screenshot 2025-04-23 at 17.19.10.png" alt="Clone repository" width="300"/>
2. **Reopen in Container**

    <small>Click the button in the popup upon opening the repo:</small>

    ![alt text](<docs/Screenshot 2025-04-23 at 17.20.22.png>)

    Alternatively, enter <kbd>Ctrl+Shift+P</kbd> and select **Dev Containers: Reopen in Container**.

3. **Enjoy 🫶**

    Enjoy a fully configured Python development environment with uv!

    ![alt text](<docs/Screenshot 2025-04-23 at 17.29.45.png>)

    🎉

## Features

- **pytest**

    Run tests with pytest.

    ```
    pytest tests
    ```

- **uv**

    Dependency management and virtual environment management with uv.

    ```
    uv add pandas
    ```

- **ruff**

    Linting and formatting with ruff.

    Linting:

    ```
    ruff check .
    ```

    Formatting:

    ```
    ruff format .
    ```

- **CI/CD**

    CI/CD with GitHub Actions.

    - **Linting**: Linting with ruff.
    - **Formatting**: Formatting with ruff.
    - **Testing**: Testing with pytest.
    - **Dependency management**: Dependency management with uv.

- **Docker**

    Build and run your Python project in a Docker container.

    ```
    docker build -t my-python-app .
    ```

## About

Provided to you with ♡ by [Jeroen Overschie](https://jeroenoverschie.nl/).