# buyrandom6

[![PyPI](https://img.shields.io/pypi/v/buyrandom6.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/buyrandom6.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/buyrandom6)][pypi status]
[![License](https://img.shields.io/pypi/l/buyrandom6)][license]

[![Read the documentation at https://buyrandom6.readthedocs.io/](https://img.shields.io/readthedocs/buyrandom6/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/tngTUDOR/buyrandom6/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/tngTUDOR/buyrandom6/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/buyrandom6/
[read the docs]: https://buyrandom6.readthedocs.io/
[tests]: https://github.com/tngTUDOR/buyrandom6/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/tngTUDOR/buyrandom6
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _buyrandom6_ via [pip] from [PyPI]:

```console
$ pip install buyrandom6
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [MIT license][License],
_buyrandom6_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://buyrandom6.readthedocs.io/en/latest/usage.html
[License]: https://github.com/tngTUDOR/buyrandom6/blob/main/LICENSE
[Contributor Guide]: https://github.com/tngTUDOR/buyrandom6/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/tngTUDOR/buyrandom6/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_buyrandom6
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=html --jobs=auto --write-all; open _build/html/index.html
```