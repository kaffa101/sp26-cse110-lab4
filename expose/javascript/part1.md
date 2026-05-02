1. value added: 20
2. final result: 20
3. You should not use var because var has no block scope which make it so var variables may be accessed in places you do not want it to be accessed, var allows for redeclarations which can make code confusing,
and var declarations are processed at function start.
4. value added: 20
5. It returns an error because let is block scoped and result was declared inside the if statement, so it cannot be accessed out of the if statement.
6. It returns an error because const cannot be reassigned
7. It is never reached because of the error but even if there was no error, line 13 would return an error because result is still block scoped.
