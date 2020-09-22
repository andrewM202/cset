------------------------------------------------------------------------

<h2> All Definitions </h2>

------------------------------------------------------------------------

<h3> JavaScript Definitions </h3>


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

- **Rest Parameters** : Allows a function to accept any number of parameters

- **Synchronous Programming** :

- **Stack Overflow** :

- **Bit Overflow** :

- **Call Stack Overflow** :

- **Elegant Code vs Fast Code** : How elegant / how easy is it to read vs. how fast the code runs. If a super fast piece of code is super hard to understand, and it takes a week to make a change to it vs. a more “elegant” piece of code that is a slower piece of code, which one should we use? A game which has a close release date and needs optimizations, might use fast code mores than elegant code: cut corners to increase performance quickly. 

- **Functional Programming** :

- **Object Oriented Programming** :

- **Early Exit** :

- **Objects** : Allow us to group values, including other objects, to produce values. 

- **Array** : A data type specifically for storing sequences of values. 

- **Index** : The name for each spot in an array. Array indexes start at 0 and end at array.length - 1. 

- **Properties** : The values connected to an object; its attributes. 

- **Stack** : “A  data structure that allows you to push values into it and pop them out again in the opposite order so that the thing that was added last is removed first.”

- **Immutability** : A value is immutable when it is impossible to change values of those types. Numbers, Strings, and Booleans are all immutable. 

- **Correlation** : A measure of dependance between statistical variables

- **Object literal** : 

- **Address** : The place in memory a value is stored. 

- **Serialization** : It is used to convert data into a flat description. 

- **Variadic Function** : A function that accepts an infinite or variable number of arguments. 

- **Class** : It is the factory that builds all the different instances of things. 

- **Protypical Language** : Everything in JavaScript is based off of what is called JavaScript. Math is a prototype object, it is treated like an object but it has a few small differences.

- **Compiler** : A computer program that translates one computer language into another. Often used for translating source code from a high level language into a lower one. 

- **Interpreter** : Interacts with compiler. 

- **Data Structures** : Generally based on the ability of a computer to fetch and store data at any place in its memory, specified by a pointer—a bit string, representing a memory address, that can be itself stored in memory and manipulated by the program.

- **Abstract Data Types (ADT)** : Data structures serve as basis for. Is the mathematical model for data structures. 

- **Instances** : 

- **Prototypes** : JavaScript uses prototypes instead of classes. 

<h3> Web Development Definitions </h3> 

- **Web standards** : The technologies used to build websites. 

- **Specifications** : Technical documents which detail how web standards work. They are used by software engineers to implement web standards. Once instance is the HTML Living Standard, which details how HTML is implemented. 

- **Standards bodies** :Institutions that have famous technology company representatives discuss how to use web standards to fill each of their interests to the fullest extent. Examples are W3C (most known), WHATWG (modernized HTML), ECMA (published ECMAScript JavaScript is based on), and KHRONOS (publish 3D graphics technologies like WebGL)

- **Backwards and Forwards open web standard compatibility** : Any newly introduced web technology is compatible with older websites / what came before it, and future technologies will also be compatible with newly introduced web technology

- **Web Browsers** : Software programs people use to consume the web, include: Firefox, Chrome, Opera, Safari, Edge, Brave

- **Web Protocols** :

- **HTTP / Hypertext Transfer Protocol** : A messaging protocol that allows web browsers to communicate with web servers

- **Web servers** : Where websites are stored

- **Requests and Responses** : The name for the syntax of HTTP messages

- **HTML / Hypertext markup language** : A markup language consisting of different elements you can wrap (mark up) content in to give it meaning (semantics) and structure. It is not a programming language. 

- **CSS / Cascading Style Sheets** - A rule-based language used to apply styles to HTML

- **JavaScript** - Used to add interactivity to web sites

- **ISPs** - 

- **Latency** - The delay in response between a user and a server. 

- **Linters** - A tool that highlights places you have not followed a given set of rules properly

- **Minifiers** - A tool that removes all the whitespace from code files

- **Libraries and Frameworks** - Allow creation of certain types of websites very quickly

- **Back-end / Service side languages** - A class of programming languages that are run on a server before the result is sent to a browser to be displayed. Includes ASP.NET, Python, PHP, and NodeJS. 

- **Front-end / Client side languages** - A class of Programming languages that are run by a browser to produce a website front-end for users. Includes JavaScript, Html, and CSS, 

- **Performance** - Getting websites to load as quickly as possible.

- **Accessibility** - Making websites usable by as many types of people as possible. Includes those with audio or visual impairments, or physical or cognitive disabilities. 

- **Internationalization** - Making website usable by people who speak different languages

- **Responsive web design** - Practice of making functionality and layouts flexible so they can adapt to different browsers. 

- **Privacy** - Not spying on people, and collecting the minimum amount of data possible

- **Security** - Constructing website in a secure way so malicious users cannot steal information 

- **Cross-browser compatibility** - The practice of making a webpage available to as many users as possible. 

- **Clients** - The typical web user’s inter-connected devices and web accessing software on those devices.

- **Servers** - Computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.

- **DNS / Domain Name Servers** - Similar to address book for websites. A web address typed in a browser looks at the DNS to find the website’s real address before it can retrieve the website. 

- **TCP/IP** - Stands for Transmission Control Protocol and Internet Protocol. They are communication protocols that define how data should travel across the internet. 

- **Internet connection** - Allows sending and receiving of data on the web. 

- **Component files** - The main files a website is built on, which include code and asset files. Code files are mainly HTML, CSS, and JavaScript while Asset files are things like images, videos, pdfs, and word documents. 

- **Data packets** - Used to send website files as a series of small pieces 

- **IP Address** - Represents a unique location on the web. They are a series of numbers and periods, like 24.124.325.52. DNS is created so that a url can be typed instead of the entire IP address: DNS match the IP with the web address. 

<h3> HTML / CSS / JavaScript Definitions (as it applies to website creation) </h3>

- **HTML / Hypertext markup language** - A markup language consisting of different elements you can wrap (mark up) content in to give it meaning (semantics) and structure. It is not a programming language. 

- **CSS / Cascading Style Sheets** - A rule-based language used to apply styles to HTML

- **HTML content** - Includes whatever is between the tags. 

- **HTML element** - Includes the opening tag, closing tag, and content. 

- **Attribute**s - Extra information about an element that does not appear in content. 

- **JavaScript** - Used to add interactivity to web sites

- **Empty elements** - Elements that have no content. For instance, the <img> tag. 


------------------------------------------------------------------------

<h2> JavaScript Methods and Functions </h2>

------------------------------------------------------------------------

<h3> Math </h3>

- **Math.random() * (max - min) + min)** ——>  Generates a number between min(inclusive) and max(exclusive)

- **Math.round(x)** ——> rounds number inside parentheses to nearest whole number

- **Math.floor(x)** ——> rounds down to the nearest whole number

- **Math.ceil(x**) ——> rounds up to the nearest whole number

- **Math.abs()**  ——> returns absolute value of a number

- **Math.PI()** ——> returns the closest approximation of PI in JavaScript

- **Math.max(low, high) and Math.min(low, high)** ——> Returns the minimum between two values

- **Math.pow(base, exponent)** ——> Returns base to exponent power

- **(x).toFixed(# of sig figs)** ——> Adds significant digits to a number

- **Math.sin/cos/tan/asin/acos/atan(angle)** ——> returns trigonometry answers

<h3> Strings </h3>

- **charAt()** ——> Returns the character at specified index

- **toLowerCase()** ——> returns string converted to lowercase

- **toUpperCase()** ——> returns string converted to uppercase

- **(string name).length** ——> returns length of string

- **“string”[n]** ——> Will return the nth letter of “string”

- **(“string”).charCodeAt(x)** ——> It returns the binary number at index x of “string”

- **“string”.indexOf(x)** ——> returns first index of x in “string”. 

- **“string”.slice(start, end)** ——> Returns a string with elements between start and end (start is inclusive in returned array, end is not). If end is not given, gives entire string from start to “string”.length. 

- **“string”.trim()** ——> removes whitespace (spaces, newlines, tabs, and similar characters) from the start and end of a string.

- **“string”.padStart(amount, “character”)** ——> adds amount number of “character” at the front of “string”

- **“string”.split(“x”)** ——> returns an array with all the pieces of “string” split at x

- **“string”.repeat(amount)** ——> creates a new string containing multiple copies of the original string, glued together.

<h3> Objects </h3>

- **Object.freeze(object name)** ——> Once frozen, you can no longer add, update, or delete properties from the object

- **delete (object).(property)** ——>  It is a unary operator that, when applied to an object property, will remove the named property from the object.

- **Object.keys(object)** ——> To find out what properties an object has, you can use the Object.keys function. You give it an object, and it returns an array of strings—the object’s property names.

- **Object.assign(objectA, objectB)** ——> Copies all the properties from one object to another

<h3> Arrays </h3>

- **array.pop()** ——> Removes last value in array and returns it

- **array.push(x)** ——> Adds value x to the end of an array

- **array.shift()** ——>  Removes first value in array and returns it

- **array.unshift(x)** ——> Adds x to beginning of array

- **array.indexOf(x)** ——> Returns the first index of x in array, returns -1 if not found

- **array.lastIndexOf(x)** ——> Returns the last index of x in array, returns -1 if not found

- **array.slice(start, end)** ——> Returns an array with elements between start and end (start is inclusive in returned array, end is not). If end is not given, gives entire array from start to array.length. 

- **array.concat(x)** ——> The concat method can be used to glue arrays together to create a new array, similar to what the + operator does for strings.

- **array.length** ——> Returns the length of array

- **array.join()** ——> returns a string with all the strings inside the array joined. 

- **array.flat(depth)** ——> If arrays are nested inside each other, it removes the nesting up to depth number of levels and puts all of the values in the nested arrays into one returned array. If no depth is given, it removes all nested arrays and places all values inside of one returned array. 




------------------------------------------------------------------------

<h2> HTML, CSS, JavaScript </h2>

------------------------------------------------------------------------

<h3> HTML Tags </h3>

- **< h1 >-< h6 >** ——> Called a header. The smaller the number in the end the small the header text.
  
- **< div >** ——> 

- **< p >** ——> Used to make paragraphs. Called a paragraph tag. 
  
- **< head >** ——> 
  
- **< body >** ——>
  
- **< script >** ——>
  
- **< html >** ——>
  
- **< style >** -——>

- **< ul >** ——> Unordered lists. Used for when order of elements does not matter, like a shopping list
  
- **< ol >** ——> Ordered lists. Used for where order of elements does matter, like a recipe
  
- **< li >** ——> List item. 
  
- **< a >** ——> Anchor. Used to add links

- **< img >** ——> 

- **< iframe >** ——> 

- **< link >** ——> 

<h3> HTML Attributes </h3>

- **src** ——> Used inside of <img> tags to imbed an image. 

- **alt** ——> Used inside of tags that have images. If the image does not load properly, the text appears. Also used for those who have vision problems. 

- **href** ——> Used inside of <a> tags to add links. For example: <a href = “example.com”>text</a>

<h3> CSS </h3>









