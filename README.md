# Python project starter 

Python 3.7 based project. Uses pre-commit hooks to lint (flake8) and autoformat (black) the code. 
Requires docstrings for everything.

Fork this project and start developing.

## Install

- clone repository
- move to project dir: `cd ./<project_folder>`
- depending on OS make sure you're using the Python 3.7 
- install or upgrade `pip` to latest version

`python3 -m pip install --user --upgrade pip`

- install virtual environment

`python3 -m pip install --user virtualenv`

- create virtual environment for project

`python3 -m venv .env`

- activate the virtual environment

`source .env/bin/activate`

- install [Poetry packet manager](https://python-poetry.org/)

`pip install poetry` 

## Lint
Activate virtual environment `source .env/bin/activate`.

Uses `mypy` to check type hints and `flake8` to check code style and existence of docstrings. 

```
make lint
```
## Test

Activate virtual environment `source .env/bin/activate`.

Run with: 

```
make test
```
## Run

Run in development mode:

```
make run
```

ADD MORE INFO AS NECESSARY
