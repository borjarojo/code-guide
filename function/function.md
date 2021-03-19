# The *Function*

Functions are the fundamental building block of all software. They are analogous, in many ways, to the English paragraph. They are meant to represent one specific idea. They most simply have three parts, and are defined[^1] are as follows:

C++: output-type function-name(input-type-1 input-name-1, input-type-2 input-name-2, ..., input-type-x input-name-x) { return output-type-data; }

Python: def function-name(input-name-1, input-name-2, ..., input-name-x): return data

For example, a simple add function.

C++:
int add(int x, int y)
{
	return x + y;
}

Python:
def add(x, y):
	return x + y

Now, if you want the official meta-definition of a function, meaning the structure of a function definition, you can find it [here for C++][c++-function-definition] and [here for Python][python-function-definition].

[^1]: A *definition* in programming refers to how something *you* created is defined. I am not refering to the dictionary definition (I know, it's confunding), but rather the fact that you as a programming will be responsible for constantly creating new named functions, and spelling out the fundamental requirements for how they work. You are, in fact, *defining* something. So, aboe explains how exactly *you* define them, or how *they* are defined.

[c++-function-definition]: https://en.cppreference.com/w/c/language/function_definition
[python-function-definition]: https://docs.python.org/3/reference/compound_stmts.html#function-definitions 
