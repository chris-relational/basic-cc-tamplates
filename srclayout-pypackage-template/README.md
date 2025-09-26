# Python cookiecutter template project

## About

This is a [Cookiecutter](https://github.com/cookiecutter/cookiecutter) ([docs](https://cookiecutter.readthedocs.io/en/stable/)) template for creating Python projects with a predefined structure and (opinionated) best practices.

The instance project produced by this template is based on [Poetry](https://python-poetry.org/) as a build system. It is structured as a main app Python package, including a sub-package that can be built and installed standalone. The project instance includes the following features:

- Project and developer `README` files
- Pre-configured `pyproject.toml` for building the project with Poetry
- Pre-configured `<sub-package>/pyproject.toml` for building the project sub-package with Poetry
- Unit tests for everything, using `pytest`
- Pre-configured `.env.template` file for environment variables
- Pre-configured `.gitignore` file, covering common Python cases
- Pre-configured `Dockerfile` for containerization
- Pre-configured `LICENSE` file

Furthermore, code quality and style is enforced with:

- `black` for code formatting
- `isort` for import sorting
- `flake8` for linting
- `mypy` for static type checking
- `pre-commit` for running all the above as git pre-commit hooks

Finally, template UML class and sequence diagrams are included in the `docs/` folder, to be further augmented as needed.

## Installation

### Cookiecutter

```bash
# pipx is strongly recommended.
pipx install cookiecutter
```

### Create project with cookiecutter

```bash
cookiecutter https://github.com/yourusername/yourcookiecutterrepo.git
```
