# ![logo](/examples/assets/LINE-sm.png) LINE Python

*LINE Messaging's private API*

----

## Installation

Installation is simple. It can be installed from pip using the following command:
```sh
$ python -m pip install -r requirements.txt
```
Or from the code:
```sh
$ python setup.py install
```

## Usage

```python
>>> from LineAPI.linepy import *
>>> client = LINE("")
>>> client.log("Auth Token : " + str(line.authToken))
```
