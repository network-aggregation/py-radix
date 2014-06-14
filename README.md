#py-radix

Radix tree data structure for network lookups (forked from https://code.google.com/p/py-radix/)

With respect to the original implementation, this code also supports node operations like 'parent()' and 'children()', which are used internally for DRAGON (seee https://github.com/network-aggregation/dragon_simulator).

##Installation
```
python setup.py build
sudo python setup.py install
```

##Test

Open up a Python shell and run:
```
import radix
```
