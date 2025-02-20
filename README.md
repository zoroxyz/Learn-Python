
# Learn Python - A simplified documentation on Python.

Hello folks, you can call me PEACE. As you can see the heading, this is an unofficial, simplified documentation for Python, for beginners. In this repository, I have tried to explain Python as simple as possible. So without wasting any more time, let's begin!

## Dedicated discord server for this repository
Let's make a good discord community and help each other out with it. You can also drop feedback and suggestions over there if you are not willing to do it here.\
  [![](https://dcbadge.vercel.app/api/server/v9RsytwNFU)](https://discord.gg/v9RsytwNFU)

## **Python**
**What is Python ?** 

Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. In sort, it's an easy programming language that one can learn. It's readability is way better as compared to any other programming language out there. Also the Python community is so helpful, healthy and active.  I believe this is all you need to know about Python(summary ofcourse).

# Installing Python
- [Windows](https://www.python.org/ftp/python/3.11.1/python-3.11.1-amd64.exe) ⚠️Note that Python 3.9+ cannot be used on Windows 7 or earlier.
- [macOS](https://www.python.org/ftp/python/3.11.1/python-3.11.1-macos11.pkg)
- [Other OS](https://www.python.org/download/other/)

# IDE(s) for Python
Visual Studio Code aka VSCode
- [Windows](https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user) ⚠️ windows 8 and above only.
- [macOS](https://code.visualstudio.com/sha/download?build=stable&os=darwin-universal)
- [Debian/Ubuntu(.deb)](https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64)
- [Fedora/Opensuse](https://code.visualstudio.com/sha/download?build=stable&os=linux-rpm-x64)

PyCharm by JETBRAINS
- [Windows](https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=windows)
- [macOS .dmg Intel](https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=mac)
- [macOS .dmg Apple silicon](https://download.jetbrains.com/python/pycharm-professional-2022.3.1-aarch64.dmg)
- [Linux](https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=linux)

Above are some of good ide(s) in which you can code python on. I personally use PyCharm more because its Simple by Default Powerful When Needed, I mean VSCode's UI is good too but for some reason I prefer PyCharm.

# Writing first code in Python.

Let's begin with Writing our first code in Python. Literally in every single documentation and books, first code I have ever seen is printing hello world. Have you ever wondered why? I got to know recently, it is because in a book named [The C Programming Language by Brian Kernighan and Dennis Ritchie](https://en.wikipedia.org/wiki/The_C_Programming_Language) had first code as printing hello world, since then it is kind of made universal to have print hello world as a first code for any beginner in any programming language. Guess what? our first code won't be to print "Hello world".

[First code](https://github.com/peacekeeper09/Learn-Python/blob/main/first%20program.py)\
```print("Spread PEACE")```
# Python Syntax

**Python Indentation**
- Indentation refers to the spaces at the beginning of a code line.
- Important in Python.
- Python uses indentation to indicate a block of code.

**Python Variables**
- Declaring variables in Python? It is easy. Python Variable does not needs to define the data type or such like in some programming language.

- We have to always keep the variable name in string, it should not be any special character or any integer.
You can check how to use variables from [here](https://github.com/peacekeeper09/Learn-Python/blob/main/variables.py).

You should keep a note that variable is case sensitive. Example [here](https://github.com/peacekeeper09/Learn-Python/blob/main/case%20sensitive-variable.py).

# Comments in Python

You can simply add up a comment in Python by using #, example [here](https://github.com/peacekeeper09/Learn-Python/blob/main/comment.py).\
Adding up a comment in a program makes it user friendly and actually allows you or your fellow contributer to understand the code easily when you are accessing it later for rewriting the code or updating some feature.

# Data Type(s) in Python

|Text Type| str     | 
| :-------- | :------- |
| Numeric Types     | 	int, float, complex|
|Sequence Types|	list, tuple, range|
|Mapping Type|	dict|
|Set Types|	set, frozenset|
|Boolean Type|	bool|
|Binary Types|	bytes, bytearray, memoryview|
|None Type|	NoneType|

You can get to see the example/usage of each data types in [here](https://github.com/peacekeeper09/Learn-Python/blob/main/data%20type.py).

# Types of operators in Python.

Operators are used to perform operations in Python.\
One of simplest example of operators is addition and substraction.

**Let's dive more deeper into "operators in Python."**\
Operators in Python can be divided into following major groups:-

- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Identity operators
- Membership operators
- Bitwise operators

Now let's see each operators closely.

- ****Arithmetic operators in Python****\
Used only with numeric values to perform simple/complex mathematics opeartions/calculations.

|Arithmetic operators|  sign | usage|
| :---- | :----|:------- |
|  Addition   | 	+| [x+y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|
|substraction|	-|[x-y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|
| Multiplication|	*|[x*y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|
|Division|	/|[x/y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|
|Modulus|	%|[x%y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|
|Exponentation|**|[x**y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|
|Floor Division|	//|[x//y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|

- ****Assignment Operators in Python****
> Used to assign values to a specified variable.

|Assignment Operators | usage| same as|
| :---- |:------- |:---|
|  =   | [x= 7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| x= 7|
|+=	| [x += 7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| x= x+7|
| -=|[x-=7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| x = x-7|
|*=|[x *= 7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|x = x*7|
|/=|	[x/=7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| x = x/7|
|%=|[x%=7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| 	x = x % 7|
|//= |[x//=7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|x = x // 7|
|  **=  | [x**=7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| x = x ** 7|
|&=	| [x &=	7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| 	x = x & 7|
| ^= 	|[x ^= 7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| x = x ^ 7|
|>>=	|[x>>=	7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|	x = x >> 7|
|<<=|	[x<<=7](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| x = x << 7|


- ****Comparison Operators in Python****
> Use to compare two values.


|Comparison operators|  sign | usage|what does it do?
| :---- | :----|:------- |:--|
|  Equal   |==	| [x==y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| compares if the value of two given element is same or not.|
|Not equal|!=|[x!=y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|checks if the value of two given element is not equal or not.|
| Greater than|	>|[x>y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)|checks if the value of a given element is greater than that of another element.|
|Less than	|	<	|[x<y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| checks if the value of a given element is smaller than that of another element.|
|Greater than or equal to	|	>=	|[x>=	y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| checks if the value of a given element is greater than or equal to the another element.
|Less than or equal to	|<=|[x<=y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| checks if the value of a given element is smaller than or equal to the another element.

- **Logical Operators in Python**
> Basically used to combine up operators.

|Logical Operators | usage| what does it do?|
| :---- |:------- |:---|
|  and | [x < 7 and  x < 9](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| This will return True if the given condition is true. |
|or	| [x < 7 or  x < 9](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| This will return True if any of the given condition is true.|
| not|[not(x < 7 and x < 9)](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| This will return False if the condition is true and True if the condition is false.|

- **Identity Operators in Python**
> Used to check if two element are equal or not.

|Identity Operators | usage| what does it do?|
| :---- |:------- |:---|
|  is  | [x is y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| This will return True if both the elements are same. |
|is not| [x is not y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| This will return True if both the elements are not same.|

- **Membership Operators in Python**
> Membership operators are used to test if a sequence is presented in an element.

|Membershit Operators | usage| what does it do?|
| :---- |:------- |:---|
|  in   | [x in  y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| This will return True sequence with the specified value is present in the element. |
|is not| [x is not y](https://github.com/peacekeeper09/Learn-Python/blob/main/operators.py)| This will return True if True if a sequence with the specified value is not present in the object.|

- **Bitwise Operators**
> Used to compare binary numbers.

|Bitwise Operators|NAME| what does it do?|
| :---- |:------- |:---|
|  &    |AND| 	Sets each bit to 1 if both bits are 1.|
|^|	XOR|	Sets each bit to 1 if only one of two bits is 1.|
|~|	NOT|	Inverts all the bits.|
|<<	|Zero| fill left shift	Shift left by pushing zeros in from the right and let the leftmost bits fall off.|
|>>	|Signed right shift	|Shift right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off.|

`|`	`OR` `Sets each bit to 1 if one of two bits is 1.`\
That's it. We covered all the operators in Python! 🤗 

# Asking for an input from user in Python.

Let's see how you can take an input from a user in Python, you need to learn this before proceeding any further.

`a= int(input("Enter an integer input :-"))` :- this is how you can take an integer input in python.\
`a = str(input("Enter a string input :- "))` :- this is how you can take a string inpu)t in python.\
`a = input("Enter an input")` :- this is will accept any kind of input in python.\
[Code here](https://github.com/peacekeeper09/Learn-Python/blob/main/input.py)
# Python If Else
-Let's begin with understand `If` and `Else` in Python.

As you can guess from name, what if and else can be used for, you must be guessing it pretty right (I hope). Let me give you a simple example to show how if and else works in here.

- Example and working:- 
Imagine if you want to want to check if a person is eligible for voting or not, how will you be checking that? By seeing that if the person is below or above [18 age](https://en.wikipedia.org/wiki/Voting_age). Right? Now I will be explaining the usage of if-else in python with taking this voting as an idea.

[Here is the code for above example!](https://github.com/peacekeeper09/Learn-Python/blob/main/if-else.py)

OR\
you can just see the code here if you don't wanna jump to that link.
![if-else code](https://media.discordapp.net/attachments/929653900812886076/1065514200635560006/image.png)

## Elif
Let's imagine a case where do you want to check multiple cases for example here if you want to check if a person if above and equal to age 18, what will you do? use if twice? no, it will not look possible at all. In such case we use `Elif`. Now let us see the usage of elif with an example.

[Here is the code for above example.](https://github.com/peacekeeper09/Learn-Python/blob/main/elif.py)

OR\
you can just see the code here if you don't wanna jump to that link.\ 
![Elif](https://media.discordapp.net/attachments/929653900812886076/1065585832750231662/image.png)

## Pass
If statements can not be empty, sometimes there are cases when you want to keep the if statement to be empty. So to avoid any kind of errors, we simply use `pass`.
[Here is the code for above example.](https://github.com/peacekeeper09/Learn-Python/blob/main/if_pass.py)
# Python While Loops

So we here comes another important thing in python, while loops. Using while loops we can execute some set of statement if the condition is true. Let us see how we can use while loops in Python.

Let's take an example for demonstrating the usage of `while-loop` in Python. Imagine if you want to check if value of a variable is lesser than 4 and if it is true, you want to print those numbers.

[Here is the code for above example.](https://github.com/peacekeeper09/Learn-Python/blob/main/while-loop.py)

OR\
you can just see the code here if you don't wanna jump to that link.

![while-loop](https://media.discordapp.net/attachments/929653900812886076/1065519285847465984/image.png)

# Python For Loops

For is used in python for iterating over a sequence that has to be either list, tuple, dictionary, set or string.
[Here is an example of how for loops is used.](https://github.com/peacekeeper09/Learn-Python/blob/main/for%20loop.py)

## Break statement

Break can be used to stop the loop before it looped through all the items.
[Here is an example of how you can use break.](https://github.com/peacekeeper09/Learn-Python/blob/main/break%20statement.py)

## Continue statement
Continue can be used to stop the current iteration and skip to the next one.
[Here is an example of how you can use continue.](https://github.com/peacekeeper09/Learn-Python/blob/main/continue%20statement.py)

\
