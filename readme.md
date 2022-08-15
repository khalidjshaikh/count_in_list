# test_package

Packages required to generate packages.
```
pip install setuptools wheel
```

Generate build, dist, and test_package.egg-info.
```
python setup.py sdist bdist_wheel
```

Package required to deploy.
```
pip install twine
```

Upload the package
```
twine upload --repository pypi dist/*
```