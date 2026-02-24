# {{ cookiecutter.project_name }}

{{ cookiecutter.project_short_description | wordwrap(90) }}

## How to run tests

**Prerequisites**: [Python 3.13](https://www.python.org/downloads/)
and [Poetry](https://python-poetry.org/docs/#installing-with-pipx) must be installed.

Set up the environment:

```sh
poetry install
```

Run the tests:

```sh
poetry run pytest
```

That's all, folks!

## How to write tests

**Prerequisites**: [Python 3.13](https://www.python.org/downloads/)
and [Poetry](https://python-poetry.org/docs/#installing-with-pipx) must be installed.

Set up the environment:

```sh
poetry install --with=dev
```

When working with Git, set up git hooks:

```sh
poetry run pre-commit install
```

Place your tests in the tests directory using the `test_*.yaml` naming format.

## DSL Reference

Detailed DSL usage and syntax can be found here:
[pytest-loco](https://pytest-loco.readthedocs.io).
