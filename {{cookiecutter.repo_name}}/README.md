# {{cookiecutter.project_name}}

**Table of Contents**

- [Installation](#installation)
- [Development](#development)
- [Testing](#testing)

## Installation

```sh
pip install {{cookiecutter.repo_name}}
```

## Development

```sh
# Setup pre-commit and pre-push hooks
hatch run pre-commit install -t pre-commit
hatch run pre-commit install -t pre-push
```

### Testing

```sh
hatch run cov
```
