Try Sphinx
==========
trying out sphinx to document python code

just install sphinx and tell it where to find your code
```pip install sphinx```

in docs/conf.py, set path to something like:
```sys.path.insert(0, os.path.abspath('/home/micaela/Projects/try-sphinx/src'))```

to autogenerate the docs from your code
```sphinx-apidoc -F -o docs src/``

```cd docs```

```make html```
