# Weld Python API

This directory contains the Weld Python API and the Grizzly implementation.

### Prerequisites

Build and run tests for Weld (the instructions for this are in the main `README.md`).

### Setup

If you want to install Weld's Python API and Grizzly in 'development' mode, run:
```bash
$ python setup.py develop
```

Otherwise, run:
```bash
$ python setup.py install
```

Also, make sure that `libweld` and `libweldrt` are on  the `LD_LIBRARY_PATH`.
