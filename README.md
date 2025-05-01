![GitHub](https://img.shields.io/github/license/front-matter/invenio-crossref?logo=MIT)

# invenio-crossref

# About

Python API wrapper for the Crossref REST and Content Registration APIs, including Crossref XML generation.

## Installation

The invenio-crossref package is on PyPI so all you need is:

    pip install invenio-crossref


## Documentation

Documentation is readable at http://crossref.readthedocs.io/ or can be
built using Sphinx: ::

    pip install crossref[docs]
    python setup.py build_sphinx


## Testing

Running the test suite is as simple as: ::

    pip install -e .[all]
    ./run-tests.sh

If you're using zsh, use this pip command instead:

    pip install -e .'[all]'
