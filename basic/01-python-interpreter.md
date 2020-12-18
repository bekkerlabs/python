# Basic: 01 - The Python Interpreter

The python interpreter is similar to a unix shell, you provide it input and it provides you with output interactively.

## Checks

First we need to check if python is installed, to do that run the following:

```bash
$ python --version
```

You should see something like this:

```bash
$ python --version
Python 3.7.3
```

## Python Interpreter

Now that we can see Python 3.7.3 is installed, we can enter the python interpreter by running:

```bash
$ python
```

You should be seeing this:

```bash
$ python
Python 3.7.3 (default, Jul 25 2020, 13:03:44) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

As learning any language, let's do the traditional "hello, world" example, where we will use the `print()` function to return the keyword that you pass it, we will go more into this later:

```python
>>> print('hello, world')
hello, world
```

As you can see we provided keyword "hello, world" to the `print()` function as an argument, and it returned the value to our screen.

## Next up

Next, we will go into [Variables](02-variables.md)
