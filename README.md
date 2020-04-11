# Machine Learning Nanodegree

[![Python 3.7](https://img.shields.io/badge/Python-3.7-green.svg)](https://shields.io/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

This repository contains the assignments for the **Machine Learning Engineer** Nanodegree course developed by Udacity 

## Development environment setup

You need to install the following software:

* Python ≥ 3.7 (older versions are not supported)
* [poetry](https://python-poetry.org/) ≥ 1.0

### Poetry installation
To install and configure `poetry` run 
```shell script
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python3
poetry config virtualenvs.in-project true
```

To install all the dependencies simply run
```shell script
poetry install
```

### AWS Authentication

In order to use AWS Services from a local machine start by install the [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

Then [configure the CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html#cli-quick-configuration) by following the instructions shown after running
```bash
aws configure
```
