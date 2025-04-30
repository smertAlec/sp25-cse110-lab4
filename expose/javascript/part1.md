1. `values added: 20`
2. `final result: 20`
3. var variables don't have block scope, which means unless they're declared in a function, they are global variables. This means that the variable can be accessed and changed from anywhere in your program, which may lead to unintended errors.
4. `values added: 20`
5. The code causes an error because the variable `result` is a let variable, which means that it is local to the block it is within. This means it can't be seen outside the block it is in.
6. The code causes an error because the it is trying to reassign `result`, which can't be changed due to it being a const variable.
7. The code causes an error for the same reason as number 6.