greetings from command line, select who to greet and how.

This is only an example (hundreds of them must exist already) on how to install
a package that is not on pypi.

# Requirements

Python3.4 or superior. It will have `venv` and `pip` preinstalled.

# Installation

Be sure to be in a virtual environment or add the `--user` flag to commands.

## Classic installation

To install the greetings package as any other package, run the command:

```
pip install .
```

And you're good to go! No harder than a classical `pip` installation!

## Editable installation

To install an editable version of the greetings package, run the command:

```
pip install --editable .
```

Editable installations allow you to modify the source code and see changes immediately, without needing to reinstall the package.

Related: [monkey patch](https://en.wikipedia.org/wiki/Monkey_patch).

# Uninstallation

In `setup.cfg`, you can see the name of the package is `greetings`. You can uninstall the package (classic or editable) with the following command:

```
pip uninstall greetings
```
