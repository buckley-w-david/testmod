# testmod
Module to demonstrate the use of setuptools

# Installation Instructions

```
$ git clone https://github.com/buckley-w-david/testmod.git
$ cd testmod
$ python -m venv env # Create a virtual environment (not technically necessary but good practice)
$ source env/bin/activate
$ pip install -e .
```

The `-e` option in the install command is optional, it installs the package in editable mode, meaning if you make a change to the source it will be reflected in the package without needing to re-install it.

You can provide `pip install` with any path to a valid python package, this examle simply uses one in the current directory.
