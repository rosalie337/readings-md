# Ch. 10, “Error Handling & Debugging”

**Order of execution** - The order in which statements are processed

**Global Context** - Code that is in the script, but not in a function. There is only one global context in any page.

**Function Context** - Code that is being run within a function. Each function has its own function context.

**Q Eval Context- Text is executed like code in an internal function called eval.

**Global Scope** - If a variable is declared outside a function, it can be used anywhere because it has a global scope. If you do not use the var keyword when creating a variable, it is placed in a global scope.

**Function Level Scope** - When a variable is declared within a function, it can only be used within that function.

**Variables Object** - This object contains details of all of the variables, functions, and parameters for that execution context.

**Hoisting** - When variables and function declarations are moved to the top of their scope before code execution. Inevitably, this means that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local

**Lexical scope** - Functions are linked to the object they were defined within. For each execution context, the scope is the current execution context's variables object, plus the variables object for each parent execution context.