
## Install the package on your local machine

```
pip3 install -e ./
```

## Build the package

```
python3 setup.py sdist bdist_wheel
```

## upload package

```
python3 -m twine upload dist/* --verbose
```

## run unittests 

```
python3 -m pytest tests/test.py
```