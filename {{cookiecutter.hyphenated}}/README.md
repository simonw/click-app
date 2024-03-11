# {{ cookiecutter.hyphenated }}

[![PyPI](https://img.shields.io/pypi/v/{{ cookiecutter.hyphenated }}.svg)](https://pypi.org/project/{{ cookiecutter.hyphenated }}/){% if cookiecutter.github_username %}
[![Changelog](https://img.shields.io/github/v/release/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}?include_prereleases&label=changelog)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/releases)
[![Tests](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/actions/workflows/test.yml/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/blob/master/LICENSE){% endif %}

{{ cookiecutter.description }}

## Installation

Install this tool using `pip`:
```bash
pip install {{ cookiecutter.hyphenated }}
```
## Usage

For help, run:
```bash
{{ cookiecutter.hyphenated }} --help
```
You can also use:
```bash
python -m {{ cookiecutter.underscored }} --help
```
## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:
```bash
cd {{ cookiecutter.hyphenated }}
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
pytest
```
