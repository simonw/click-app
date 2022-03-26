# {{ cookiecutter.hyphenated }}

[![PyPI](https://img.shields.io/pypi/v/{{ cookiecutter.hyphenated }}.svg)](https://pypi.org/project/{{ cookiecutter.hyphenated }}/){% if cookiecutter.github_username %}
[![Changelog](https://img.shields.io/github/v/release/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}?include_prereleases&label=changelog)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/releases)
[![Tests](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/workflows/Test/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.hyphenated }}/blob/master/LICENSE){% endif %}

{{ cookiecutter.description }}

## Installation

Install this tool using `pip`:

    $ pip install {{ cookiecutter.hyphenated }}

## Usage

Usage instructions go here.

## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:

    cd {{ cookiecutter.hyphenated }}
    python -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
