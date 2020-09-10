- **Closure (first definition)** : Being able to refer to a specific instance of a local binding in an enclosing scope. It basically allows you to make functions with functions. 

- **Closure (second definition)** : A function that references bindings from local scopes around it.

- **Function : a procedure** : a set of statements that performs a task or calculates a value. It should take some input and return an output where there is an obvious relationship between input and output. 

- **Primitive (primitive value / data type)** : Data that is not an object and has no methods. There are 6 primitives: undefined, boolean, Number, String, BigInt, Symbol. 

- **Parameter** : The inputs of a function

- **Body** : Statements of code that runs in a function

- **Value** : Optional result to send back in a function using return statement. 

- **Expression** : A fragment of code that produces a value. “Every value that is written literally (such as 22 or "psychoanalysis") is an expression. An expression between parentheses is also an expression, as is a binary operator applied to two expressions or a unary operator applied to one.”

- **Statement** : “If an expression corresponds to a sentence fragment, a JavaScript statement corresponds to a full sentence. A program is a list of statements.”

- **Side Effect** : Showing a dialogue box or text on the screen. Anything that is not a return statement. 

- **Binding/Variable** : Is used to catch and hold a value, otherwise it will immediately disappear when the program runs past it. let means a bind will be defined. The name of the binding is right after let. And if I want to give it a value, it is defined in an expression after an =. 

- **const/constant** : Defines a constant binding, which points at the same value for as long as it lives

- **Environment** : the collection of bindings, their values, that exist in any given moment is called the environment

- **Key words** : reserved words in JavaScript, include things like for, while, break, etc 

- **Numbers** : simply numeric values. 

- **Arithmetic** : operations like addition, mod, subtraction, etc. Of course, the main thing you do with numbers is arithmetic operations. 

- **Special Numbers** : Are considered numbers but don’t behave like normal ones. There are three total: infinity, -infinity, NaN. 

- **Strings** : They represent Text. Written using quotes, whether single, double, or backticks, they work.

- **Scope** : The part of the program in which a binding is visible. For bindings defined outside of a function or block, the scope encompasses the entire program - these bindings can be referred to anywhere in the program. 

- **Block** :  The code inside of brackets (like in a function). They are used to group 0 or more statements. In languages other than JavaScript it is called a compound statement. 

- **Global** : Used to describe bindings that are visible (can be used) anywhere in a program. Bindings declared with var in loops and functions are global. 

- **Local** : Refers to bindings that can only be accessed within a limited section of a program, such as let and const bindings created within the block of a function or in a function’s parameters.

- **Environment** : The area a function acts in. This includes the block as well as the area in the program where you called the function. 

- **Nested Scope** : Refers to when blocks or functions are created within another block or function: this produces a hierarchy or degree of locality. 

- **Call Stack** : The order the computer goes through when a function is called. Since a function must return a value to the spot where it was called, the computer must remember the order/context in where each return statement should be sent. This data is stored in the call stack. 

- **Lexical Scoping** : Each local scope can see the local scopes that contain it, and all scopes can see the global scope. 

- **Recursion** : Occurs when a function calls itself. It is useful when you want to solve a problem by calculating every possibility to an answer until you find the right one. 

- **Method** : A method is just a special function. All methods are functions, not all functions are methods. The specialty of a method is just that they are tied to a specific object. For instance, round is a method of the round object, and log is a method of the console object. A specific example: (“string”).toUpperCase() is a method, while toUpperCase(“string”) is a function. 

- **Pure function / Pure** : A function that has no side effects, and is not involved in any function with side effects.

- **Hoisting** : Pre-ES6 term to describe how JavaScript separated declaration from initialization. Only declarations are hoisted. 

- **Just in time compilation** : The program reads your code and then runs the code. (In Java I believe this is compile time and run time)

- **Closures** : A function has created a local scope, and then that function has stopped running, and thus that local scope is not being used, but it sticks around because other values might be relying on that scope. You can’t access that function’s scope, but other things that relied on that scope still has access.

- **Iterative** : Describes solutions that deal with one at a time, like a for loop looking through every number 1-100 for a solution. 

- **Base Case** : refers to the terminating condition for a recursive function. It is always put above all the actual recursive calling: when the terminating condition is met the recursion ends and a solution has been found. 

- **Rest Parameters** :

- **Default Parameters** : 

- **Synchronous Programming** :

- **Stack Overflow** :

- **Bit Overflow** :

- **Call Stack Overflow** :

- **Elegant Code vs Fast Code** : How elegant / how easy is it to read vs. how fast the code runs. If a super fast piece of code is super hard to understand, and it takes a week to make a change to it vs. a more “elegant” piece of code that is a slower piece of code, which one should we use? A game which has a close release date and needs optimizations, might use fast code mores than elegant code: cut corners to increase performance quickly. 

- **Functional Programming** :

- **Object Oriented Programming** :























