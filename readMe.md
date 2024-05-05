# Python Refresher

## Definitions 
The term is in **bold** followed by the python specific nomenclature in (parentheses) if applicable. Some definition will have a basic example code.

**Variable** - A nickname or label for an object or a piece of data in Python. 

**integer** (int) - A whole number.   

**float** (float) - A number with a decimal point.  

**string** (str) - A sequence of letters, numbers, symbols, or whitespaces enclosed by 'single' or "double" quotation marks.   

**list** (list) - A sequence of data. The data in a list are indexed (labeled) by their numerical order in the list starting from 0.
```python
li = ['a','b','c'] #a list of strings. 
print( li[0] ) #prints 'a'
```

**dictionary** (dict) - A dictionary maps keys to values. Unlike sequences (e.g., strings, lists) which are indexed by their order, a dictionary is indexed by its keys. The example below is a dictionary, di, mapping pokemon (the keys) to their national dex numbers (the values)
```python
di = {'Bulbasaur':1, 'Ivysaur':2, 'Venusaur':3}
print( di['Ivysaur'] ) #prints 2
```

**for loop** - A for loop walks over a collection of data (e.g., a string, a list, a range of numbers), accessing each piece of data in the collection one at a time, running the specified code each time, and then ending when it reaches the end of the collection. 
```python
li = [1,2,3] #a list of ints
for i in li: 
    print(i)

