# svk-packager

[![PyPI](https://img.shields.io/pypi/v/svk-packager.svg)](https://pypi.org/project/svk-packager/)
[![Changelog](https://img.shields.io/github/v/release/svkau/svk-packager?include_prereleases&label=changelog)](https://github.com/svkau/svk-packager/releases)
[![Tests](https://github.com/svkau/svk-packager/actions/workflows/test.yml/badge.svg)](https://github.com/svkau/svk-packager/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/svkau/svk-packager/blob/master/LICENSE)

A tool för for packaging delivery to e-archives

## Installation

Install this tool using `pip`:
```bash
pip install svk-packager
```
## Usage

For help, run:
```bash
svk-packager --help
```
You can also use:
```bash
python -m svk_packager --help
```
## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:
```bash
cd svk-packager
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
