# The harmony behind servers

*This problem is created by Arnav Rustagi*

A server is asking for a function that takes a `key` (2D array of integers) as input and converts it into an array of the form

The `key` is a 64 x 64 array of the following form:

```sh
4 5 6 3 4 9 3 4|3 4 5 6 4 5 6 8| ...
```

i.e., Rows are split on the `|` character.

```sh
[[0 1 0 1 ...],
 [0 1 0 1 ...],
 ...]
```

José tried to implement this function, but the server is rejecting this input. The server can only take an input which is 52 characters long. Your function (set of python statements) can only be 52 characters long. The `request` cannot be longer than 52 characters long.

Can you write a program that is small enough to be accepted by the server, and gives the correct output?

The program `golf.py` is given to you so that you can test your function.
