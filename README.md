# IS218 Python Workflow

This project is for IS218: Introduction to Professional Programming. It is used to practice Python programming, testing with pytest, and a repeatable Git and GitHub workflow.

## Repository

GitHub repository: https://github.com/mp2395/is218-python-workflow

## Files

* `README.md` — project documentation and setup instructions.
* `.gitignore` — prevents the virtual environment and generated files from being tracked.
* `requirements.txt` — contains the required pytest version.
* `app.py` — contains the `add()` function.
* `tests/test_app.py` — contains tests for the `add()` function.

## Python Environment

This project uses Python 3.12.14.

To create the virtual environment:

```text
python3 -m venv .venv
```

To activate it:

```text
source .venv/bin/activate
```

To install the required packages:

```text
python -m pip install -r requirements.txt
```

If the virtual environment already exists, do not create it again. From the project directory, reactivate it with:

```text
source .venv/bin/activate
```

## Running the Tests

With the virtual environment active, run:

```text
python -m pytest
```

The project currently has two passing tests.

## Ignored Files

The `.gitignore` file excludes the following environment and generated files:

```text
.venv/
__pycache__/
*.py[cod]
.pytest_cache/
```
