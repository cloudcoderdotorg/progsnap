# Progsnap Python library

This is a Python library for reading [Progsnap](https://cloudcoderdotorg.github.io/progsnap-spec) data.

All of the code is distributed under the [MIT license](https://opensource.org/licenses/MIT).

Currently, it only works with Python 3.  Patches to support Python 2 would be gratefully accepted.

Documentation is minimal at this point.  However, there are example programs in the [Progsnap examples](https://github.com/cloudcoderdotorg/progsnap-examples) repository.

## Using the library

The library is a Python package that can work with `pip`.  Here's one recommended approach:

Create a Python virtual environment:

```
virtualenv -p $(which python3) venv
source venv/bin/activate
```

Import the Progsnap library using `pip` (replace `somewhere` with the directory containing `progsnap`):

```
cd somewhere/progsnap
pip install -e .
```

Now you should be ready to run programs that `import progsnap`.

## Contact

Email questions/comments to <david.hovemeyer@gmail.com>
