# Use a Python module while you develop it in prallel

First, best practise for dealing with Python modules and packages is `virtualenv(wrapper)`.
Second, (change to the virtualenv with `workon whatever`) install the module via

    pip install -e /path/to/source/which/you/are/constantly/editing

The module/package is now linked to your site-packages and you can use it and develop on it at the same time.
