# Python resume

## 1-Data type

### 1.1-Integer
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

### 1.2-String

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

### 1.3-List

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

### 1.4-Tuples

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

### 1.5-Dictionaries

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

### 1.6-Float

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

## 2-Control structures

Control structures have the job of controlling the flow of code

#### 2.1-Condicionals

Conditionals in Python are widely used in code management. They are structures composed of three conditionals: if, elif and else.

#### Example:

```python
age = 17
if age < 18:
    print("You are a kid yet")
elif age > 150 or age < 0:
    print("Invalid ages")
else:
    print("You are a young man")
``` 

This is a simple example of a conditional structure. As you can see and the name indicates, it is based on conditions. The first thing you have to put is an “if”, this starts the conditional structure. In the if line you have to put a condition that if it is met, the lines below will be executed. The next is the “elif” which works like an “if” but can be put as many times as you want. Finally we have the “else”, this does not have to have a condition, just what it has to execute. This will be executed when neither the “elif” nor the “if” are met.


#### 2.2-Cycles

Cyclic structures are distinguished by the fact that the actions within them are repeated.

#### 2.2.1-While

"While" structures are made up of two things, a condition that will cause the inside to be executed until it stops being true. The other part is the inside, which is what will be executed until the condition stops being true.

#### Example

```python
count = 0
while count < 5:
    if count > 0:
        print(f"This is the iteration {count}")
    count = count + 1
"""Result:
This is the iteration 1
This is the iteration 2
This is the iteration 3
This is the iteration 4
"""
```

In this simple example you can see the usefulness of "while".

#### 2.2.2-For

The "for" loop is responsible for repeating an action as many times as a value in a range

#### Example

```python
for x in "this string":
    print(x)
""" 
Result:
t
h
i
s

s
t
r
i
n
g
"""
```

In this simple example you can see the usefulness of "for".


## 3-Functions

In Python we have two types of functions. The native ones that are already included in the language, such as “print”, those for data type conversion, such as “int”, “str”, etc., or for working with a data type, such as “reverse”, and then there are those that you can create yourself

#### Example

```python
def funtion_name(str1, str2):
    value_return = str(str1) + str(str2)
    return(value_return)

print(funtion_name("this a ", "example function"))

#Result: this a example function
```

The first thing to put is the reserved word “def” followed by the name of the function, some parentheses to define the parameters, a colon and what the function is going to do in the lines below. This is how a function is defined in Python, now I am going to explain each part, the parameters are what we will introduce to the function and with which the operations will be performed, the functions may not have parameters, but usually they have at least one. The functions will always have some operation inside, and they will have a “retrun” that will return a value. The functions will not be executed alone, they must be called

## 4-Reading and writing of files

Reading and writing of files is essential for the correct storage of information


#### Example

```python
purchase = 'C:/Users/adm/Documents/data/cookie_shop/purchase.txt'

purchase_read = open(purchase, 'r')

print(purchase_read.read())
```

To start, you need to enter the address of the file. You save this in a variable and then in another variable you save the result of the open (in the open you have to enter the variable with the address and with what permissions you want to open it). Then you can use any reading and writing function (depending on the permissions given).

## 5-Exepcions

Exception work is useful to prevent possible errors

#### Example

```python
try:
    5/0
except ZeroDivisionError:
    print("Cannot be divided by zero")
```

Working with exceptions is about trying an operation and thinking of a possible error to catch it with an “except”. This allows the program to continue moving forward without stopping due to that error, as well as having the possibility of sending a customizable message to the users.

## 6-Object Oriented Programming

Object-oriented programming is a way of organizing code that is based on thinking about real-life objects.

#### 6.1-Classes and objects

Classes are one of the fundamental elements in object-oriented programming. Classes basically define the behavior of the objects belonging to them

#### Example:

```python
class  person: 
    
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def say_name(self):
        return(f"Hello i am {self.name}")

person_intance = person("example_name", 26)

print(person_intance.say_name())

print(person_intance.name)

print(person_intance.age)
```

Classes define how the objects belonging to this class act. The class can have: methods that are like functions that can be called through the objects of a class and attributes that are values ​​that the classes have, for example, for the person class an attribute could be the name, age, etc. Objects are created from classes as if the classes were a kind of mold. From the objects, operations can be performed with the methods and attributes of the classes to which these objects belong.


