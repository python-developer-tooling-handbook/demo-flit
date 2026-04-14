# Flit 

This is a companion example for the [Flit](https://pydevtools.com/handbook/reference/flit/) reference page on the [Python Developer Tooling Handbook](https://pydevtools.com).

This package is an example project for building a Python package (i.e., wheel or sdist).
It relies on [Flit](https://flit.readthedocs.io/en/latest/) as a build backend with pyproject.toml
for configuration.

## Commands:

> [!Note]
> flit (like setuptools) does not manage your virtual environment. You will need to create and activate one yourself (e.g. with [venv](https://docs.python.org/3/library/venv.html)).

* Editable install:
```shell
flit install --symlink --deps=all
```
* Run code:
```shell
python -c "import flit_demo_package"
```
* Build:
```shell
flit build
```
* Upload to PyPI:
```shell
flit publish
```