# Poetry Template
A template for my Python shenanigans.

## Development
1. Install python-poetry
2. `poetry install --all-extras` to download dependencies
3. `poetry run task pre-commit` to install pre-commit hooks (for linting)
4. You should be good to go! `pre-commit` will automatically check your project for problems before committing.
5. [OPTIONAL] Run `poetry run task lint` to lint manually.

### To create a program:
1. Add a `__main__.py` file to `poetry_template`
2. You should be able to run your program with `poetry run python -m poetry_template`

### To create a library:
1. You're all set! Just add source files to `poetry_template`
