# count_in_list

Install the package
```
pip install count_in_list
```

From Python or IPython
```
from count_in_list import count_in_list
l = ["gfg", "dsa", "gfg"]
count = count_in_list(l, "gfg")
print(count)
```

---

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