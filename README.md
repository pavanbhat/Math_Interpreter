# Math_Interpreter
An interpreter is a program that executes instructions for a programming language.

Introduction:

The python3 interpreter executes Python programs. This assignment involves writing an inter-preter for a very simple language called PreTee.The interpreter accepts prefix mathematical expressions as input, where a prefix expression is one in which the mathematical operation is written at the beginning rather than in the middle. Inside the interpreter is a parser,whose job is to convert prefix expressions, represented as a string, into a collection of tree structures known as parse trees.The PreTee interpreter can evaluate mathematical expressions using the operators +, -, *, and //. The supported operands are positive integer literals (e.g. 8) and variables (e.g.,’x’). A data structure called a symbol tableis used by the interpreter to associate a variable with its integer value. When given a prefix expression, PreTee displays the infix form of the expression and evaluates the result.

It involves the following classes-
•	PreTee: The main interpreter class. It is responsible for parsing the PreTee source
code, displaying it in infix, and then executing it.

•	AssignmentNode: A class to represent the assignment node. It assigns the result of an
expression to a variable.

•	LiteralNode: A class to represent a literal node containing a positive integer.

•	MathNode: A class to represent a mathematical node. It contains the operation, plus
the left and right expressions. 

•	PrintNode: A class to represent a print node. It displays the result of an expression
to standard output.

•	VariableNode: A class to represent a variable node.It stores the id of the variable and
can retrieve its stored value from the symbol table.

•	SyntaxError: An exception class used to indicate syntax errors when compiling the code.

•	RuntimeError: An exception class used to indicate runtime errors that occur during
execution.


