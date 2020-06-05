# Overview

{{cookiecutter.project_short_description}}

This project was generated with [cookiecutter](https://github.com/audreyr/cookiecutter) using [wefoxgroup/template-python](https://github.com/JavierMartinezAlc/template-python).

[![Unix Build Status](https://img.shields.io/travis/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}/{{cookiecutter.default_branch}}.svg?label=unix)](https://travis-ci.org/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}})
[![Windows Build Status](https://img.shields.io/appveyor/ci/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}/{{cookiecutter.default_branch}}.svg?label=windows)](https://ci.appveyor.com/project/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}})
[![Coverage Status](https://img.shields.io/coveralls/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}/{{cookiecutter.default_branch}}.svg)](https://coveralls.io/r/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}})
[![PyPI Version](https://img.shields.io/pypi/v/{{cookiecutter.project_name}}.svg)](https://pypi.org/project/{{cookiecutter.project_name}})
[![PyPI License](https://img.shields.io/pypi/l/{{cookiecutter.project_name}}.svg)](https://pypi.org/project/{{cookiecutter.project_name}})

# Setup

## Requirements

* Python {{cookiecutter.python_major_version}}.{{cookiecutter.python_minor_version}}+

## Installation

Install it directly into an activated virtual environment:

```text
$ pip install {{cookiecutter.project_name}}
```

or add it to your [Poetry](https://poetry.eustace.io/) project:

```text
$ poetry add {{cookiecutter.project_name}}
```

# Usage

After installation, the package can imported:

```text
$ python
>>> import {{cookiecutter.package_name}}
>>> {{cookiecutter.package_name}}.__version__
```
