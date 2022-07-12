# The monty language
What is Monty?
Monty is a scripting language that is first compiled into monty byte code. It relies on a unique stack which has specific instructions for manipulation.
This project creates an interpreter for monty bytecode files(files that have a ```.m``` extension).

## Usage
```monty <file>``` - file is the path containing the monty byte code
#### NOTE
if no file is given or more than one argument, there is an error.


## Op codes
```push <int> ``` - pushes an element to the stack
