# Python resume

## 1-Data type

### Integer
The integers are the first type of data, this type of data covers the Integer numbers. The negative and positive numbers

#### Operations:

1-Sum:    
```python
print(45 + 89)
#Result: 134
```

2-Subtraction:    
```python
print(45 - 89)
#Result: -44
```

3-Multiplication:    
```python
print(45 * 89)
#Result: 4005
```

4-Division:    
```python
print(45 / 89)
#Result: 0.5056179775280899
```

5-Division with no decimal:    
```python
print(45 // 89)
#Result: 0
```

6-Potencia:    
```python
print(45 ** 89)
#Result: 9556343262083828449249267578125
```

7-Rest:    
```python
print(45 % 89)
#Result: 45
```

The Integers can be use to some numerics operations.

### String

The string are the data type referent to the texts.

#### Operations:

1-Concatenation:    
```python
print("This is a " + "string")
#Result: "This is a string"
```

The concatenation join two string.

2-All in uppercase:    
```python
print("in uppercase".upper())
#Result: "IN UPPERCASE"
```

Put all the letters in uppercase.

3-All in lowercase:    
```python
print("IN LOWERCASE".lower())
#Result: "in lowercase"
```

Put all the letters in lowercase.

4-Is numeric:    
```python
print("45".isnumeric())
#Result: True
```

This funtion return a boolean(a true o false value) referent to if is a numeric date or not.

5-Replace:    
```python
print("This is a string".replace("i", "o"))
#Result: Thos os a strong
```

This funtion replace the the frist character that is introduced by the sencon character introduced in all the string.

### List

Lists are a type of data that allows you to organize the storage of different types of data separated by commas (the data can include other lists)

#### Operations

1-Agregate:    
```python
list1 = [3, "This is a string", ["This is another string", [4, 9088]]]
list1.append(5)
print(list1)
#Result: [3, 'This is a string', ['This is another string', [4, 9088]], 5]
```

This fution agregate a value that you define to a list

2-Agregate multiple values:    
```python
list1 = [3, "This is a string", ["This is another string", [4, 9088]]]
list1.extend([8, "example string", 998, 98997, [2, True]])
print(list1)
#Result: [3, 'This is a string', ['This is a another string', [4, 9088]], 8, 'example string', 998, 98997, [2, True]]
```
This function aggregate multiple values that you define to a list

3-Chage a value for another value:    
```python
list1 = [3, "This is a string", ["This is another string", [4, 9088]]]
list1[0] = "The change date"
print(list1)
#Result: ['The change date', 'This is a string', ['This is a another string', [4, 9088]]]

list1 = [3, "This is a string", ["This is another string", [4, 9088]]]
list1[0:1] = ["The change date", 5]
print(list1)
#Result: ['The change date', 5, 'This is a string', ['This is a another string', [4, 9088]]]
```

This function changes one or multiple data to another through the dictionary

4-Turn the list upside down
```python
list1 = [3, "This is a string", ["This is another string", [4, 9088]]]
list1 = list(reversed(list1))
print(list1)
#Result: [['This is a another string', [4, 9088]], 'This is a string', 3]
```

This function turn the list upside down

5-Eliminate data
```python
list1 = [3, "This is a string", "This is a string", ["This is another string", [4, 9088]]]
list1.remove("This is a string")
#Result: [3, "This is a string", ["This is a another string", [4, 9088]]]
```

This function eliminate the first coincidence of the value that you want to eliminate

### Tuples

This is a data type similar to the list but immutable

#### Operations

1-Union:

```python
tuple1 = ("This is imutable", 3, 6, 893)
tuple2 = ("Exemple", 9, 2, 890123)
tuple3 = tuple1 + tuple2
print(tuple3)
#Result: ('This is imutable', 3, 6, 893, 'Exemple', 9, 2, 890123)
```

This function joins the contents of two tuples

2-Duplication:
```python
tuple1 = ("This is imutable", 3, 6, 893)
tuple2 = tuple1 * 5
print(tuple2)
#Result: ('This is imutable', 3, 6, 893, 'This is imutable', 3, 6, 893, 'This is imutable', 3, 6, 893, 'This is imutable', 3, 6, 893, 'This is imutable', 3, 6, 893)
```

This allows to repeat the contents of a tuple multiple times

3-Count:
```python
tuple1 = ("This is imutable", 3, 3, 893)
print(tuple1.count(3))
#Result: 2
```

Counts the number of times a value is appeared in a tuple

4-Seek the index of a value:
```python
tuple1 = ("This is imutable", 3, 3, 893)
print(tuple1.index(3))
#Result: 1
```

### Dictionaries

Dictionaries are data that are primarily characterized by key-value structures.

#### Operations

1-Replace values:
```python
dictionary = {"key1": "value1", "key2": "value2", "key3": "value3"}
dictionary["key2"] = "Exemple string"
print(dictionary)
#Result: {'key1': 'value1', 'key2': 'Exemple string', 'key3': 'value3'}
```

2-Seek values:
```python
dictionary = {"key1": "value1", "key2": "value2", "key3": "value3"}
print(dictionary["key3"])
print(dictionary.get("key3"))
#Result: value3
```

3-Obtine length:
```python
dictionary = {"key1": "value1", "key2": "value2", "key3": "value3"}
print(len(dictionary))
#Result: 3
```

Obtain the number of Keys

4-Key in dictionary:
```python
dictionary = {"key1": "value1", "key2": "value2", "key3": "value3"}
print("key1" in dictionary)
print("string" in dictionary)
#Result: True
#Result: False
```

5-Elimination:
```python
dictionary = {"key1": "value1", "key2": "value2", "key3": "value3"}
del dictionary["key3"]
print(dictionary)
#Result: {'key1': 'value1', 'key2': 'value2'}
```

### Float

Floats are a data type that includes numbers with decimals, positive and negative

#### Operations

1-Separation of integer and decimal parts

```python
import math
math.modf(5.75)  
# Result: (0.75, 5.0)
```

Returns a tuple containing the fractional and integer parts of a floating point number

2-Round

```python
round(5.6789, 2)  
# Resultado: 5.68
``` 

#### Info: floats have the operations of the integers too.