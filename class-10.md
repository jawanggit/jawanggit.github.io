Key points:

Every statement in a script lives in one of three execution contexts (pg 453):
- global context, function contet, eval context

2 types of variable scope
- global and function-level scope

Stack refers to when a statement needs data from another function, it piles the new function on top of the current task (pg 454)

Any variables and functions within each execution context are created before they are executed. Hoisting is taking variables and functions and bringing them up to the top of the execution context.

Scope - if a variable if no found in the child function, the interpreter can look in the parent function, however a parent function cannot access a child's variables.

errors have the following properties: name,message, fileNumber, lineNumber

7 types of built-in error objects in Javascript (pg 459):
-error, syntaxError, ReferenceError, TypeError, RangeError, URIError, EvalError
-detailed examples on pg 460 and 461

console methods:
-console.info(), console.warn(),console.error()

how to use breakpoints in chrome and firefox on pg 476

try, catch, finally methods on pg 481 are helpful when you see issues with your input data
