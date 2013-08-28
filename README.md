Wordplay
==========
v 0.0.1
-----

A simple-minded keyword argument parser for Matlab. Takes a
list of keyword - value pairs and returns a ```containers.Map```
of them.

Useage
------
 
```matlab
>> kwargs = wordplay.getKwargs('greeting', 'hello', 'name', 'Chad', 'age', 35)

kwargs = 

  containers.Map handle
  Package: containers

  Properties:
        Count: 3
      KeyType: 'char'
    ValueType: 'any'

  Methods, Events, Superclasses

>> kwargs('name')

ans =

Chad

>> kwargs('age')

ans =

    35
```


Installation
------------
1. Download. 
2. Place ```+wordplay`` in your MATLAB path.


License
-------
BSD
