# How to make an import

## Prerequistites

TDB

## When would you need these?

Imports are a versatile tool and an important ability to master. They are used when you need to access code from another file or library that you need to use in your current file. You will import the entire file or individual parts into your current file.

## How to import!

```
# If you need a class called MyClass that you need to import from the UsefulClasses library, you'd do:

from UsefulClasses import MyClass

# Then, you would use it however you need!

myObject = MyClass("foobar", 1)
```

## Important Note!

You cannot import one file into another than is already importing the first. This will result in a circular import error!

<u>**Example:**</u>

```
# File: foo.py

import bar

// Code here...
```

```
# File: bar.py

import foo

// Code here...
```

This will Cause a circular import error because of how foo.py and bar.py are both attempting to import each other. This error will also occur if you try to import specific parts of a file (i.e. a class, a function, a variable, etc) even if the specific parts of the files do not dircetly rely on each other.

## Practice Problems:

Go to the [main.py](./main.py) file in this folder and import exampleFunction from [exampleFile.py](./exampleFile.py) and run it
