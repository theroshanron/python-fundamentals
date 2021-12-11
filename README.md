# Python Fundamentals

A playground to learn basics of python with small programs and my personal docs based on them.

## Why learn Python?

- One of the most popular
- Been around a while, hence reliable
- Beginner friendly and easy to learn
- Can do all sorts of things like AI & ML, game or web dev, data science, automation, etc.
- Fundamentals are useful for all other languages too

## Getting Python

- Go to [www.python.org](https://www.python.org/)
- Click the download btn and choose the best option for your system.
- Install python and check the `python path` checkbox during the process.
- Installed 🚀

> To check if you have python, open a terminal like cmd and type `python --version`. If you have python in your system it will show the version or else you don't have it

## Coding in Python

- Open python from start menu in the default command line app
- Write your first `hello world` program
- Use `exit()` function to exit and close the program

#### Notepad

- We can also use notepad and other text editors for writing python code
- Simple open notepad and write some python code
- Save the file with `.py` extension which stands for python
- Open terminal and type `python <saved file's full path>`
- Code will be executed!

#### IDEs

- Get an IDE like VS Code for your system
- Open vscode and configure it to look pretty
- Get the `python` extension by microsoft
- Select the python intrepreter using command palette and set it as downloaded python version
- Open the python file and run it using play btn
- Code will be executed!

## Python Notes

#### Comments

- Can be used to explain code
- Use `#` symbol to start a comment which will be ignored by python
- Can be put above or right next to any code
- Can be used for line by line debugging

#### Variables

- Used to assign and store values
- Can be used to store different data types
- Should only contain letters, numbers, and underscores
- Shouldn't start w number
- Case sensitive and can't be python keywords
- Can be reset later after defining
- Refer to [variables.py](./variables.py)

#### Data Types

- There are multiple data types in python
- `str` represents strings - any text or characters
- `int` is for integers like 4, 7, 27328
- `float` is for numbers with decimals like 3.2, 7839.83
- `bool` is for True/False (case sensitive)
- One type can be converted to another via [type conversion](./type-conversion.py)
- Refer to [data-types.py](./data-types.py)

#### Strings

- Wrap text bw single or double quotes `print("Hello")`
- Numbers can also be used as strings `print('5')`
- Use quotes carefully and when required `print("Give me John's number")`
- For multiline strings use the quotes 3 times
- Use **formatted strings** for easy string concatenation
- Refer to [strings.py](./strings.py)

#### String Methods

- Used to handle and do more things with strings
- `len(name)` used to find the length of a string
- `name.upper()` - to convert string to uppercase
- `name.lower()` - to convert string to lowercase
- `name.find()` - to find the index of characters
- `name.replace()` - to replace one char to another
- `'...' in name` - to check existence of a char in variable
- Refer to [string-methods.py](./string-methods.py)

#### Operators

- Adding(+), subtract(-), multiple(\*), divide (%)
- White spaces are ignored
- Follows default mathematical BODMAS rule `2+2*5 = 12`
- Don't use commas in bw numbers

#### Conditional Logic

- Every expression breaks down to true or false
- Used to do perform tasks based on certain conditions
- Used with comparison operators and boolean values
- For eg, `print(5==4)` will print false
- `if-else` statements are used to perform conditional logic
- Refer to [if-else.py](./if-else.py)

#### Functions

- Block of code with a name that can be executed when called
- Makes code more reusable
- Can be built-in `print()` or can be created by us
- Created by using the **def** keyword followed by function name and parenthesis
- Cannot be called before defining it
- Can take arguments as function parameters
- If-else statements can be used inside functions
- Values can also be returned from function after executions
- Refer to [functions.py](./functions.py)

#### Loops

- Used to executed a block of code multiple times
- 2 types are **while loops** & **for loops**
- Use `break` to stop and exit the loop
- Use `continue` to skip over current iteration
- Refer to [for-loop.py](./for-loop.py) and [while-loop.py](./while-loop.py)

#### Importing Libraries and Modules

- Can be imported to built stuff on top of pre existing code
- Use `import` keyword followed by the library name
- Use the methods on the imported library or however the respective module works
- Refer to [libraries.py](./libraries.py)
