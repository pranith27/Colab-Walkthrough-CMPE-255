# 01 — Introduction to Python

**Status:** Executed successfully

## Code and Output

### Cell 2

```python
import this
```

**Output**

```text
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

### Cell 7

```python
# EXAMPLE OF CREATING A VARIABLE

# We use # to add comment, it won’t run or affect the code
# You use = to assign a value to the name of the variable.
# Each code starts on the new line. No semicolon or {}
# Python is awesome. You do not need to provide the data type of variable when creating it.

int_var = 1
str_var = 'Hundred'
```

### Cell 9

```python
int_var = 10
float_var = 12.8

type(int_var)
```

**Output**

```text
int
```

### Cell 10

```python
type(float_var)
```

**Output**

```text
float
```

### Cell 11

```python
# Numeric Operations

# Addition

1 + 100
```

**Output**

```text
101
```

### Cell 12

```python
# Multiplication

1 * 100
```

**Output**

```text
100
```

### Cell 13

```python
# Division

1 / 100
```

**Output**

```text
0.01
```

### Cell 14

```python
# Floor division

7 // 2
```

**Output**

```text
3
```

### Cell 15

```python
# Modular (%)
# This is the remainder or a value remaining after dividing two numbers
# 100 / 1 = 100, remainder is 0

100 % 1
```

**Output**

```text
0
```

### Cell 16

```python
1 % 100
```

**Output**

```text
1
```

### Cell 17

```python
10 % 2
```

**Output**

```text
0
```

### Cell 18

```python
# Powers
# 1 power any number is 1 always

1 ** 100
```

**Output**

```text
1
```

### Cell 19

```python
2 ** 2
```

**Output**

```text
4
```

### Cell 20

```python
# We use print() to display the results of the operations or a variable

print(1 + 100)
```

**Output**

```text
101
```

### Cell 22

```python
str_var = 'One'
str_var2 = 'Hundred'
```

### Cell 23

```python
str_var + str_var2
```

**Output**

```text
'OneHundred'
```

### Cell 24

```python
str_var + ' ' + 'and' + ' '+ str_var2 + '.'
```

**Output**

```text
'One and Hundred.'
```

### Cell 25

```python
# We can use print() to display a string

print(" This is a string")
```

**Output**

```text
 This is a string
```

### Cell 26

```python
# We can also compare strings to check whether they are similar.
# If they are similar, case by case, comparison operator returns true. Else false

"A string" == "a string"
```

**Output**

```text
False
```

### Cell 27

```python
"A string" == "A string"
```

**Output**

```text
True
```

### Cell 29

```python
sentence = 'This IS A String'
```

### Cell 30

```python
# Case capitalization
# It return the string with first letter capitalized and the rest being lower cases.

sentence.capitalize()
```

**Output**

```text
'This is a string'
```

### Cell 31

```python
# Given a string, convert it into title (each word is capitalized)

sentence_2 = 'this is a string to be titled'
sentence_2.title()
```

**Output**

```text
'This Is A String To Be Titled'
```

### Cell 32

```python
# Converting the string to upper case

sentence.upper()
```

**Output**

```text
'THIS IS A STRING'
```

### Cell 33

```python
# Converting the string to upper case

sentence.lower()
```

**Output**

```text
'this is a string'
```

### Cell 34

```python
# Splitting the string

sentence.split()
```

**Output**

```text
['This', 'IS', 'A', 'String']
```

### Cell 36

```python
stri = "This movie was awesome"
stri.replace('movie', 'project')
```

**Output**

```text
'This project was awesome'
```

### Cell 37

```python
# In the following string, replace all spaces with `%20'

stri_2 = "The future is great"
stri_2.replace(' ', '%20')
```

**Output**

```text
'The%20future%20is%20great'
```

### Cell 44

```python
# Creating a list

week_days = ['Mon', 'Tue', 'Wed', 'Thur','Fri']
even_numbers = [2, 4, 6, 8, 10]
mixed_list = ['Mon', 1, 'Tue', 2, 'Wed', 3]

# Displaying elements of a list
print(week_days)
```

**Output**

```text
['Mon', 'Tue', 'Wed', 'Thur', 'Fri']
```

### Cell 45

```python
# Creating a list with range()

nums = range(5)

for i in nums:
    print(i)
```

**Output**

```text
0
1
2
3
4
```

### Cell 48

```python
# Accessing the first elements of the list

week_days[0]
```

**Output**

```text
'Mon'
```

### Cell 49

```python
even_numbers[2]
```

**Output**

```text
6
```

### Cell 50

```python
# Getting the last element of the list

print(even_numbers[-1])
```

**Output**

```text
10
```

### Cell 53

```python
# Get the elements from index 0 to 2. Index 2 is not included.

week_days = ['Mon', 'Tue', 'Wed', 'Thur','Fri']
week_days[0:2]
```

**Output**

```text
['Mon', 'Tue']
```

### Cell 54

```python
# Get elements from the last fourth elements to the first
# -1 starts at the last element 'Fri', -2 second last element `Thur'..... -4 to 'Tue'

week_days[-4:]
```

**Output**

```text
['Tue', 'Wed', 'Thur', 'Fri']
```

### Cell 55

```python
# Get all elements up to the fourth index

week_days[:4]
```

**Output**

```text
['Mon', 'Tue', 'Wed', 'Thur']
```

### Cell 56

```python
# Get all elements from the second to the last index

week_days[2:]
```

**Output**

```text
['Wed', 'Thur', 'Fri']
```

### Cell 58

```python
week_days[:]
```

**Output**

```text
['Mon', 'Tue', 'Wed', 'Thur', 'Fri']
```

### Cell 60

```python
names = ['James', 'Jean', 'Sebastian', 'Prit']
names
```

**Output**

```text
['James', 'Jean', 'Sebastian', 'Prit']
```

### Cell 61

```python
# Change 'Jean' to 'Nyandwi' and 'Sebastian' to 'Ras'

names[1:3] = ['Nyandwi', 'Ras']
names
```

**Output**

```text
['James', 'Nyandwi', 'Ras', 'Prit']
```

### Cell 62

```python
# Change 'Prit' to Sun

names[-1] = 'Sun'
names
```

**Output**

```text
['James', 'Nyandwi', 'Ras', 'Sun']
```

### Cell 63

```python
# Change `James` to ``Francois`

names[0] = 'Francois'
names
```

**Output**

```text
['Francois', 'Nyandwi', 'Ras', 'Sun']
```

### Cell 65

```python
# Delete Nyandwi in names list

del names[1]
names
```

**Output**

```text
['Francois', 'Ras', 'Sun']
```

### Cell 67

```python
names = ['James', 'Jean', 'Sebastian', 'Prit']
names.pop(2)
names
```

**Output**

```text
['James', 'Jean', 'Prit']
```

### Cell 69

```python
names = ['James', 'Jean', 'Sebastian', 'Prit']
names.remove('James')
names
```

**Output**

```text
['Jean', 'Sebastian', 'Prit']
```

### Cell 71

```python
# Adding the new elements in list

names = ['James', 'Jean', 'Sebastian', 'Prit']
names.append('Jac')
names.append('Jess')
names
```

**Output**

```text
['James', 'Jean', 'Sebastian', 'Prit', 'Jac', 'Jess']
```

### Cell 74

```python
# Given a list names, use for loop to display its elements

names = ['James', 'Jean', 'Sebastian', 'Prit']

for name in names:
    print(name)
```

**Output**

```text
James
Jean
Sebastian
Prit
```

### Cell 75

```python
# Given a list nums, add 1 to the first element, 2 to the second, 3 to 3rd element, 4 to 4th element
# Example: nums = [1,2,3,6] will be nums_new = [2,4,6,10]

nums = [1, 2, 3, 6]
nums_new = []

for i in range(len(nums)): #len(nums) gives the length of the list
    num = nums[i] + i + 1
    nums_new.append(num)

nums_new
```

**Output**

```text
[2, 4, 6, 10]
```

### Cell 77

```python
# Concatenating two lists

a = [1,2,3]
b = [4,5,6]

c = a + b

c
```

**Output**

```text
[1, 2, 3, 4, 5, 6]
```

### Cell 78

```python
# We can also use * operator to repeat a list a number of times

[None] * 5
```

**Output**

```text
[None, None, None, None, None]
```

### Cell 79

```python
[True] * 4
```

**Output**

```text
[True, True, True, True]
```

### Cell 80

```python
[1,2,4,5] * 2
```

**Output**

```text
[1, 2, 4, 5, 1, 2, 4, 5]
```

### Cell 82

```python
# Creating a list in other list

nested_list = [1,2,3, ['a', 'b', 'c']]


# Get the ['a', 'b', 'c'] from the nested_list

nested_list[3]
```

**Output**

```text
['a', 'b', 'c']
```

### Cell 83

```python
# Indexing and slicing a nested list is quite similar to normal list

nested_list[1]
```

**Output**

```text
2
```

### Cell 85

```python
# Sorting a list with sort()

even_numbers = [2,14,16,12,20,8,10]

even_numbers.sort()

even_numbers
```

**Output**

```text
[2, 8, 10, 12, 14, 16, 20]
```

### Cell 86

```python
# Reversing a string with reverse()

even_numbers.reverse()
even_numbers
```

**Output**

```text
[20, 16, 14, 12, 10, 8, 2]
```

### Cell 87

```python
# Adding other elements to a list with append()

even_numbers = [2,14,16,12,20,8,10]

even_numbers.append(40)
even_numbers
```

**Output**

```text
[2, 14, 16, 12, 20, 8, 10, 40]
```

### Cell 88

```python
# Removing the first element of a list

even_numbers.remove(2)
even_numbers
```

**Output**

```text
[14, 16, 12, 20, 8, 10, 40]
```

### Cell 89

```python
## Return the element of the list at index x

even_numbers = [2,14,16,12,20,8,10]

## Return the item at the 1st index

even_numbers.pop(1)
```

**Output**

```text
14
```

### Cell 90

```python
# pop() without index specified will return the last element of the list

even_numbers = [2,14,16,12,20,8,10]
even_numbers.pop()
```

**Output**

```text
10
```

### Cell 91

```python
# Count a number of times an element appear in a list

even_numbers = [2,2,4,6,8]
even_numbers.count(2)
```

**Output**

```text
2
```

### Cell 94

```python
# We can convert a string into list

stri = 'Apple'

list(stri)
```

**Output**

```text
['A', 'p', 'p', 'l', 'e']
```

### Cell 95

```python
# Splitting a string produces a list of individual words

stri_2 = "List and Strings"
stri_2.split()
```

**Output**

```text
['List', 'and', 'Strings']
```

### Cell 97

```python
stri_3 = "state-of-the-art"

stri_3.split('-')
```

**Output**

```text
['state', 'of', 'the', 'art']
```

### Cell 102

```python
# Creating a dictionary

countries_code = dict()
print(countries_code)
```

**Output**

```text
{}
```

### Cell 104

```python
type(countries_code)
```

**Output**

```text
dict
```

### Cell 106

```python
# Adding items to the empty dictionary.

countries_code["United States"] = 1
```

### Cell 107

```python
countries_code
```

**Output**

```text
{'United States': 1}
```

### Cell 109

```python
countries_code = {
        "United States": 1,
        "China": 86,
        "Rwanda":250,
        "Germany": 49,
        "India": 91,
}

countries_code
```

**Output**

```text
{'United States': 1, 'China': 86, 'Rwanda': 250, 'Germany': 49, 'India': 91}
```

### Cell 111

```python
countries_code['Australia'] = 61
countries_code
```

**Output**

```text
{'United States': 1,
 'China': 86,
 'Rwanda': 250,
 'Germany': 49,
 'India': 91,
 'Australia': 61}
```

### Cell 114

```python
# Getting the code of Rwanda

countries_code["Rwanda"]
```

**Output**

```text
250
```

### Cell 116

```python
"India" in countries_code
```

**Output**

```text
True
```

### Cell 117

```python
# Should be False

"Singapore" in countries_code
```

**Output**

```text
False
```

### Cell 119

```python
# Getting the keys and the values and items of the dictionary

dict_keys = countries_code.keys()
dict_values = countries_code.values()
dict_items = countries_code.items()

print(f"Keys: {dict_keys}\n Values:{dict_values}\n Items:{dict_items}")
```

**Output**

```text
Keys: dict_keys(['United States', 'China', 'Rwanda', 'Germany', 'India', 'Australia'])
 Values:dict_values([1, 86, 250, 49, 91, 61])
 Items:dict_items([('United States', 1), ('China', 86), ('Rwanda', 250), ('Germany', 49), ('India', 91), ('Australia', 61)])
```

### Cell 121

```python
# Get the value of the Australia

countries_code.get('Australia')
```

**Output**

```text
61
```

### Cell 122

```python
# In case a provided key is absent....

countries_code.get('UK', 41)
```

**Output**

```text
41
```

### Cell 125

```python
stri = 'aaaaajjj222@@@sss^^^888'

counts = [0] * 128 # Create a list of 128 elements, initially each character count is 0.

for c in stri:
    c_num = ord(c)

    counts[c_num] = counts[c_num] + 1

counts
```

**Output**

```text
[0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 5,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0]
```

### Cell 127

```python
stri = "jdjjdjdjdjjdjdjdj"

counts_dict = {}

for c in stri:
    if c not in counts_dict:
        counts_dict[c] = 1

    else:
        counts_dict[c] += 1

print(counts_dict)
```

**Output**

```text
{'j': 10, 'd': 7}
```

### Cell 129

```python
stri = input(str) #input must be a string

char_count = {}

for c in stri:
    char_count[c] = char_count.get(c,0) + 1

print(char_count)
```

**Output**

```text
<class 'str'>hello world
{'h': 1, 'e': 1, 'l': 3, 'o': 2, ' ': 1, 'w': 1, 'r': 1, 'd': 1}
```

### Cell 131

```python
countries_code
```

**Output**

```text
{'United States': 1,
 'China': 86,
 'Rwanda': 250,
 'Germany': 49,
 'India': 91,
 'Australia': 61}
```

### Cell 132

```python
for country in countries_code:
    print(country)
```

**Output**

```text
United States
China
Rwanda
Germany
India
Australia
```

### Cell 134

```python
for country, code in countries_code.items():
    print(country, code)
```

**Output**

```text
United States 1
China 86
Rwanda 250
Germany 49
India 91
Australia 61
```

### Cell 136

```python
countries_code.setdefault("UK", 41)
```

**Output**

```text
41
```

### Cell 137

```python
countries_code
```

**Output**

```text
{'United States': 1,
 'China': 86,
 'Rwanda': 250,
 'Germany': 49,
 'India': 91,
 'Australia': 61,
 'UK': 41}
```

### Cell 139

```python
stri = (Hello) #input must be a string

char_count = {}

for c in stri:
    char_count.setdefault(c,0) #If character doesn't exist in char_count, add it and set it to 0
    char_count[c] += 1

print(char_count)
```

**Output**

```text
<class 'str'>Hello
{'H': 1, 'e': 1, 'l': 2, 'o': 1}
```

### Cell 142

```python
tup = (1,4,5,6,7,8)
```

### Cell 143

```python
# Indexing

tup[4]
```

**Output**

```text
7
```

### Cell 144

```python
## Tuples are not changeable. Running below code will cause an error

# tup[2] = 10
```

### Cell 145

```python
# You can not also add other values to the tuple. This will be error
#tup.append(12)
```

### Cell 148

```python
set_1 = {1,2,3,4,5,6,7,8}

set_1
```

**Output**

```text
{1, 2, 3, 4, 5, 6, 7, 8}
```

### Cell 149

```python
set_2 = {1,1,2,3,5,3,2,2,4,5,7,8,8,5}
set_2
```

**Output**

```text
{1, 2, 3, 4, 5, 7, 8}
```

### Cell 151

```python
# List Vs Set

odd_numbers = [1,1,3,7,9,3,5,7,9,9]

print("List:{}".format(odd_numbers))

print("********")

set_odd_numbers = {1,1,3,7,9,3,5,7,9,9}

print("Set:{}".format(set_odd_numbers))
```

**Output**

```text
List:[1, 1, 3, 7, 9, 3, 5, 7, 9, 9]
********
Set:{1, 3, 5, 7, 9}
```

### Cell 153

```python
## Greater than
100 > 1
```

**Output**

```text
True
```

### Cell 154

```python
## Equal to

100 == 1
```

**Output**

```text
False
```

### Cell 155

```python
## Less than

100 < 1
```

**Output**

```text
False
```

### Cell 156

```python
## Greater or equal to

100 >= 1
```

**Output**

```text
True
```

### Cell 157

```python
## Less or equal to

100 <= 1
```

**Output**

```text
False
```

### Cell 158

```python
'Intro to Python' == 'intro to python'
```

**Output**

```text
False
```

### Cell 159

```python
'Intro to Python' == 'Intro to Python'
```

**Output**

```text
True
```

### Cell 161

```python
100 == 100 and 100 == 100
```

**Output**

```text
True
```

### Cell 162

```python
100 <= 10 and 100 == 100
```

**Output**

```text
False
```

### Cell 163

```python
100 == 10 or 100 == 100
```

**Output**

```text
True
```

### Cell 164

```python
100 == 10 or 100 == 10
```

**Output**

```text
False
```

### Cell 165

```python
not 1 == 2
```

**Output**

```text
True
```

### Cell 166

```python
not 1 == 1
```

**Output**

```text
False
```

### Cell 170

```python
if 100 < 2:

  print("As expected, no thing will be displayed")
```

### Cell 171

```python
if 100 > 2:

  print("As expected, no thing will be displayed")
```

**Output**

```text
As expected, no thing will be displayed
```

### Cell 172

```python
if 100 < 2:

  print("As expected, no thing will be displayed")

else:
  print('Printed')
```

**Output**

```text
Printed
```

### Cell 173

```python
# Let's assign a number to a variable name 'jean_age' and 'yannick_age'

john_age = 30
luck_age = 20

if john_age > luck_age:
  print("John is older than Luck")

else:
  print(" John is younger than Luck")
```

**Output**

```text
John is older than Luck
```

### Cell 174

```python
# Let's use multiple conditions

john_age = 30
luck_age = 20
yan_age = 30

if john_age < luck_age:
  print("John is older than Luck")

elif yan_age == luck_age:
  print(" Yan's Age is same as Luck")

elif luck_age > john_age:
  print("Luck is older than John")

else:
  print("John's age is same as Yan")
```

**Output**

```text
John's age is same as Yan
```

### Cell 176

```python
# Example 1: Return 'Even' if below num is 'Even' and `Odd` if not.

num = 45

'Even' if num % 2 == 0 else 'Odd'
```

**Output**

```text
'Odd'
```

### Cell 177

```python
# Example 2: Return True if a given element is in a list and False if not

nums = [1,2,3,4,5,6]

True if 3 in nums else False
```

**Output**

```text
True
```

### Cell 180

```python
even_nums = [2,4,6,8,10]

for num in even_nums:
  print(num)
```

**Output**

```text
2
4
6
8
10
```

### Cell 181

```python
week_days = ['Mon', 'Tue', 'Wed', 'Thur','Fri']

for day in week_days:
  print(day)
```

**Output**

```text
Mon
Tue
Wed
Thur
Fri
```

### Cell 182

```python
sentence = "It's been a long time learning Python. I am revisiting the basics!!"

for letter in sentence:
  print(letter)
```

**Output**

```text
I
t
'
s
 
b
e
e
n
 
a
 
l
o
n
g
 
t
i
m
e
 
l
e
a
r
n
i
n
g
 
P
y
t
h
o
n
.
 
I
 
a
m
 
r
e
v
i
s
i
t
i
n
g
 
t
h
e
 
b
a
s
i
c
s
!
!
```

### Cell 183

```python
sentence = "It's been a long time learning Python. I am revisiting the basics!!"

# split is a string method to split the words making the string

for letter in sentence.split():
  print(letter)
```

**Output**

```text
It's
been
a
long
time
learning
Python.
I
am
revisiting
the
basics!!
```

### Cell 184

```python
# For loop in dictionary

countries_code = { "United States": 1,
                 "India": 91,
                 "Germany": 49,
                 "China": 86,
                 "Rwanda":250
            }

for country in countries_code:
  print(country)
```

**Output**

```text
United States
India
Germany
China
Rwanda
```

### Cell 185

```python
for code in countries_code.values():
  print(code)
```

**Output**

```text
1
91
49
86
250
```

### Cell 187

```python
for number in range(10):
  print(number)
```

**Output**

```text
0
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

### Cell 188

```python
for number in range(10, 20):
  print(number)
```

**Output**

```text
10
11
12
13
14
15
16
17
18
19
```

### Cell 190

```python
letters = []

for letter in 'MachineLearning':
  letters.append(letter)

letters
```

**Output**

```text
['M', 'a', 'c', 'h', 'i', 'n', 'e', 'L', 'e', 'a', 'r', 'n', 'i', 'n', 'g']
```

### Cell 192

```python
letters = [letter for letter in 'MachineLearning']

letters
```

**Output**

```text
['M', 'a', 'c', 'h', 'i', 'n', 'e', 'L', 'e', 'a', 'r', 'n', 'i', 'n', 'g']
```

### Cell 194

```python
a = 10
while a < 20:
    print('a is: {}'.format(a))
    a = a + 1
```

**Output**

```text
a is: 10
a is: 11
a is: 12
a is: 13
a is: 14
a is: 15
a is: 16
a is: 17
a is: 18
a is: 19
```

### Cell 196

```python
# Function to add two numbers and return a sum

def add_nums(a,b):

  """
  Function to add two numbers given as inputs
  It will return a sum of these two numbers
  """

  sum = a+b

  return sum
```

### Cell 197

```python
add_nums(2,4)
```

**Output**

```text
6
```

### Cell 198

```python
add_nums(4,5)
```

**Output**

```text
9
```

### Cell 199

```python
# Displaying the doc string noted early

print(add_nums.__doc__)
```

**Output**

```text
Function to add two numbers given as inputs
It will return a sum of these two numbers
```

### Cell 200

```python
def activity(name_1, name_2):

  print("{} and {} are playing basketball!".format(name_1, name_2))
```

### Cell 201

```python
activity("Chris", "Francois")
```

**Output**

```text
Chris and Francois are playing basketball!
```

### Cell 202

```python
activity("Kennedy", "Kleber")
```

**Output**

```text
Kennedy and Kleber are playing basketball!
```

### Cell 205

```python
## Sum of two numbers

def add_nums(a,b):

  sum = a+b

  return sum

add_nums(1,3)
```

**Output**

```text
4
```

### Cell 207

```python
sum_of_two_nums = lambda c,d: c + d

sum_of_two_nums(4,5)
```

**Output**

```text
9
```

### Cell 209

```python
# using len() to count the length of the string

message = 'Do not give up!'
len(message)
```

**Output**

```text
15
```

### Cell 210

```python
odd_numbers = [1,3,5,7]
len(odd_numbers)
```

**Output**

```text
4
```

### Cell 211

```python
# Using max() to find the maximum number in a list

odd_numbers = [1,3,5,7]
max(odd_numbers)
```

**Output**

```text
7
```

### Cell 212

```python
# Using min() to find the minimum number in a list

min(odd_numbers)
```

**Output**

```text
1
```

### Cell 213

```python
# Sorting the list with sorted()

odd_numbers = [9,7,3,5,11,13,15,1]

sorted(odd_numbers)
```

**Output**

```text
[1, 3, 5, 7, 9, 11, 13, 15]
```

### Cell 216

```python
def cubic(number):
  return number ** 3
```

### Cell 217

```python
num_list = [0,1,2,3,4]
```

### Cell 218

```python
# Applying `map` to the num_list to just return the list where each element is cubed...(xxx3)

list(map(cubic, num_list))
```

**Output**

```text
[0, 1, 8, 27, 64]
```

### Cell 220

```python
def odd_check(number):

  return number % 2 != 0

# != is not equal to operation
```

### Cell 221

```python
num_list = [1,2,4,5,6,7,8,9,10,11]

list(filter(odd_check, num_list))
```

**Output**

```text
[1, 5, 7, 9, 11]
```

### Cell 226

```python
# Given a list of numbers, can you make a new list of even numbers from the list nums?
# Even numbers are numbers divisible by 2, and they give the remainder of 0

nums = range(1,20)
even_nums = []


# A traditional way to do it is:

for num in nums:
  if num % 2 == 0:
    even_nums.append(num)

print(even_nums)
```

**Output**

```text
[2, 4, 6, 8, 10, 12, 14, 16, 18]
```

### Cell 228

```python
even_nums = [num for num in nums if num % 2 == 0]
print(even_nums)
```

**Output**

```text
[2, 4, 6, 8, 10, 12, 14, 16, 18]
```

### Cell 230

```python
days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday']
day_T = []

# Make a list of days that start with `T`

for day in days:
  if day[0] == 'T':
    day_T.append(day)

print(day_T)
```

**Output**

```text
['Tuesday', 'Thursday']
```

### Cell 232

```python
day_T = [day for day in days if day[0] == 'T']
print(day_T)
```

**Output**

```text
['Tuesday', 'Thursday']
```

### Cell 235

```python
seasons = ['Spring', 'Summer', 'Fall', 'Winter']

list(enumerate(seasons))
```

**Output**

```text
[(0, 'Spring'), (1, 'Summer'), (2, 'Fall'), (3, 'Winter')]
```

### Cell 237

```python
list(enumerate(seasons, start=1))
```

**Output**

```text
[(1, 'Spring'), (2, 'Summer'), (3, 'Fall'), (4, 'Winter')]
```

### Cell 239

```python
class_names = ['Rock', 'Paper', 'Scissor']

for index, class_name in enumerate(class_names, start=0):
  print(index,'-',class_name)
```

**Output**

```text
0 - Rock
1 - Paper
2 - Scissor
```

### Cell 242

```python
name = ['Jessy', 'Joe', 'Jeannette']
role = ['ML Engineer', 'Web Developer', 'Data Engineer']

zipped_name_role = zip(name, role)
zipped_name_role
```

**Output**

```text
<zip at 0x7a32bc34cfc0>
```

### Cell 244

```python
list(zipped_name_role)
```

**Output**

```text
[('Jessy', 'ML Engineer'),
 ('Joe', 'Web Developer'),
 ('Jeannette', 'Data Engineer')]
```

