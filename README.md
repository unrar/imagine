# imagine
`imagine` is a Python 3 package which aims to supply a simple library that eases Google Image searching.

## Library
The `Imagine` class wraps the whole behavior of the library. After initializing it, providing the search query and the
number of elements to be taken in the constructor arguments, simply call its `.execute()` method and the query
will execute.

For an example of use, check the source code of `imagine_iface.py`.

## Interface
Provided with this package is a binary (`imagine`) which links to the `imagine_iface.py` file. This uses the Imagine
Library to create a simple command line interface to allow the user to perform a Google Image search.

Usage:

    $ imagine


