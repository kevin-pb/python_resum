# python_resum

### 1-Data type

#### Intigeer
The intigers is te first type of data, this type of data covers, hows the names says, the Intigeer numbers. The negative and positive numbers

##### Operations:

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

The Intigeers can be use to some numerics operations.

#### String

The string are the data type referent to de texts.

##### Operations:

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

#### List 

Lists are a type of data that allows you to organize the storage of different types of data separated by commas (the data can include other lists)


1-Agregate:    
```python
list1 = [3, "This is a string", ["This is a another string", [4, 9088]]]
list1.append(5)
print(list1)
#Result: [3, 'This is a string', ['This is a another string', [4, 9088]], 5]
```

This fution agregate a value that you define to a list

2-Agregate multiple values:    
```python
list1 = [3, "This is a string", ["This is a another string", [4, 9088]]]
list1.extend([8, "exemple string", 998, 98997])
print(list1)
#Result: [3, 'This is a string', ['This is a another string', [4, 9088]], 8, 'exemple string', 998, 98997]
```

3-Chage a value for another value:    
```python
list1 = [3, "This is a string", ["This is a another string", [4, 9088]]]
list1[0] = "The change date"
print(list1)
#Result: ['The change date', 'This is a string', ['This is a another string', [4, 9088]]]
```

