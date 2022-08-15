# test_package

Needed to generate packages.
```
pip3 install setuptools wheel
```

Generate build, dist, and test_package.egg-info.
```
python setup.py sdist bdist_wheel
```

Needed to deploy.
```
pip install twine
```