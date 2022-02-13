# parse
Extract words from a string

## Usage
```python
>>> from parse import parse
>>>
>>> string = 'MY __mask__ --ofSanityIS.slowly#Slipping'
>>>
>>> parse(string)
['my', 'mask', 'of', 'sanity', 'is', 'slowly', 'slipping']
>>>
>>> parse(string, case_sensitive = True)
['MY', 'mask', 'of', 'Sanity', 'IS', 'slowly', 'Slipping']
```