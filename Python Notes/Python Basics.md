# Python Bible

## DATA TYPES

#### Integers

```python
15321
-5713215
```

#### Float

```python
-23.54
52354.0
483.4569
```

#### Strings

```python
'Hello, World'
"Hello, World"
```

#### Boolean

```python
True
False
```



## Output & Printing

Sample Code:

```python
print('Hello, World')
print(135.69)
print(6969777)
print(False)
```

Output:

```bash
Hello, World
135.69
6969777
False
```



## Variables

Sample Code:

```python
name = 'adrian'
number = 1224
isGood = True

print(name, number, isGood)
```

Output: 

```bash
adrian 1224 False
```



## User Input

Sample Code:

```python
Name = input('enter your name: ')
Age = input('enter your age: ')

print('Hello '+ Name + ', you are ' + Age + ' years old.' )
```

Output: 

```bash
enter your name: adrian
enter your age: 19

Hello adrian, you are 19 years old.
```



## Operators

```bash
+    | addition
-    | subtraction
*    | multiplication
/    | division
**   | gives exponents
//   | removes the remainder
%    | gets the remainder of the result

B . E . D . M . A . S

(B)rackets
	(E)quations
		(D)ivisions
			(M)ultiplication
				(A)ddition
					(S)ubtraction
```



##  Conditional Operators

```bash
==   | is equal to
!=   | not equal to
<=   | less than or equal to
>=   | greater than or equal to
<    | less than
>    | greater than

```



##  Chained Operators

#### and

Sample Code:

```python
x = 9
y = 19
z = 10
result1 = x + z == 19
result2 = y == 19

result3 = result1 and result2
print(result3)
```

Output: 

```bash
True
```



#### or

Sample Code:

```python
x = 7
y = 8
z = 3

result1 = x == y
result2 = y > x
result3 = z -2 < x + 2

result4 = result1 or result2
print(result4)
```

Output: 

```bash
True
```



#### not

Sample Code:

```python
print(not True)
```

Output: 

```bash
False
```



## Strings

#### Conversion of Str to Int

Sample Code:

```python
user_num = input('enter a number:')
print('output:', int(user_num) - 5)
```

Output: 

```bash
enter a number:50
output: 45
```



#### .upper()

Sample Code:

```python
Sayhi = 'Hi, There'
print(Sayhi.upper())
```

Output: 

```bash
HI THERE
```



#### .lower()

Sample Code:

```python
Sayhi = 'HI, THERE'
print(Sayhi.lower())
```

Output: 

```bash
hi, there
```



#### .capitalize()

Sample Code:

```python
Sayhi = 'hi, there'
print(Sayhi.capitalize())
```

Output: 

```bash
Hi, there
```



#### type

Sample Code:

```python
Sayhi = 'Hi, There'
print(type(Sayhi))
```

Output: 

```bash
<class 'str'>
```



## List

Sample Code:

```python

```

Output: 

```bash

```



## List Functions

Sample Code:

```python

```

Output: 

```bash

```



## Tuples

Sample Code:

```python

```

Output: 

```bash

```



## Functions

Sample Code:

```python
def Sayhi():
    print('HI, There!!')
    
Sayhi()
```

Output:

```bash
HI, There!!
```

## Return Statements

Sample Code:

```python
def square(num):
	return num*num

result = square(5)

print(result)
```

Output: 

```bash
25
```



## If Statements

Sample Code:

```python
User_Input_Name = input('Please enter your name: ')
if User_Input_Name.lower() == 'adrian':
    print('Hi Adrian, Welcome Back!')
elif User_Input_Name.lower() == 'ralph':
    print('Hi Ralph, Welcome Back!')
else:
    print('Your name is not registered in our Database, please try again')
```

Output 1: 

```bash
Please enter your name: Adrian

Hi Adrian, Welcome Back!
```

Output 2: 

```bash
Please enter your name: Ralph

Hi Ralph, Welcome Back!
```

Output 3: 

```bash
Please enter your name: Khen

Your name is not registered in our Database, please try again
```



## Dictionaries

Sample Code:

```python
Month_Convertions = {
	'Jan' : 'January',
	'Feb' : 'February',
	'Mar' : 'March',
	'Apr' : 'April',
	'May' : 'May',
	'Jun' : 'June',
	'Jul' : 'July',
	'Aug' : 'August',
	'Sep' : 'September',
	'Oct' : 'October',
	'Nov' : 'November',
	'Dec' : 'December'
}


print(Month_Convertions.get('Dec', 'not a valid key'))
```

Output: 

```bash
December
```



## For Loops

Format:

```python
for <> in range(stop):
    
for <> in range (start, stop):

fro <> in range (start, stop, step/pattern):
```

Sample Code:

```python
My_Name = ['ralph', 'khen', 'adrian']

for i in range(len(My_Name)):
	print(My_Name[i])
```

Output: 

```bash
ralph
khen
adrian
```



## While Loop

Sample Code:

```python
i = 0
while i <= 10:
    print('Hello, World')
    i += 1
```

Output: 

```bash
Hello, World
Hello, World
Hello, World
Hello, World
Hello, World
Hello, World
Hello, World
Hello, World
Hello, World
Hello, World
Hello, World
```



## 2D Lists and Nested Loops

Sample Code:

```python
number_grid = [
	[1,2,3],
	[4,5,6],
	[7,8,9]
]

for row in number_grid:
	for col in row:
		print(col)
```

Output: 

```bash
1
2
3
4
5
6
7
8
9
```



## Try / Except

Sample Code:

```python
try:
    number = int(input('Enter a number: '))
    print(number)
except ValueError as err:
    print(err)
```

Output: 

```bash
Enter a number: dfasd
invalid literal for int() with base 10: 'dfasd'
```



## File Handling (Read)

Sample Code:

```python
file_reader = open('hi.txt', 'r')
print(file_reader.read())
file_reader.close()
```

Output: 

```bash
Hi There! ==>> TEXT FROM FiLE
```



## File Handling (Write)

Sample Code:

```python
file_reader = open('hello.txt', 'a+')
print(file_reader.write('boombot\n'))
file_reader.close()
```

Output: 

```bash
//creates new file 'hello.txt'
//inside of the file,

boombot
```



## Modules and Pip

From basics.py:

```python
erpcal = ['ralph', 'paolo', 'anthony', 'roy']
```

Sample Code:

```python
import basics as friends

for name in friends.erpcal:
    print(name)
```

Output: 

```bash
ralph
paolo
anthony
roy
```



## Classes and Objects

From basics.py:

```python
class Student:

    def __init__(self, name, course, gwa, is_on_probation):
        self.name = name
        self.course = course
        self.gwa = gwa
        self.is_on_probation = is_on_probation
```

Sample Code:

```python
from basics import Student

student1 = Student('ralph', 'CPE', 1.5, False)

print(student1.course)
```

Output: 

```bash
CPE
```



## Object Functions

From basics.py:

```python
class Student:

    def __init__(self, name, course, gwa, is_on_probation):
        self.name = name
        self.course = course
        self.gwa = gwa
        self.is_on_probation = is_on_probation

    def dean_lister(self):
        if self.gwa <= 1.50:
            return True
        else:
            return False
```

Sample Code:

```python
from basics import Student

student1 = Student('ralph', 'CPE', 1.5, False)

print(student1.name)
print(student1.course)
print(student1.gwa)
print(student1.is_on_probation)
print(student1.dean_lister())
```

Output: 

```bash
ralph
CPE
1.5
False
True
```
