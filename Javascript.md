How Javascript works?
What is Memory Component / Variable Environment ?
What is Code Component / Thread of Execution ?
How Javascript code is executed ?
How call stack in Javascript Engine works ?
How functions are executed ?
What is shortest JS Program ? ```this === window```
undefined and not defined ?
static typing and dynamic typing ?
let and const declarations ?
Temporal Deadzone ?
Syntax Error, Reference Error, Type Error ?
What is block scoped ?




Javascript is synchronous single threaded language loosely typed (weak typed) language.
Callstack maintains the order of execution of execution contexts

Fancy names for callstack
Call Stack
Execution Context Stack
Program Stack
Control Stack
Runtime Stack
Maching Stack


What is Hoisting ?
In JavaScript, Hoisting is the default behavior of moving all the declarations at the top of the scope before code execution. 


Three ways to define a function 

```
console.log(printHelloWorld1)
console.log(printHelloWorld2)
console.log(printHelloWorld3)

function printHelloWorld1(){
    console.log("hello world")
}

var printHelloWorld2 = function(){
    console.log("hello world")
}

var printHelloWorld3 = () => {
    console.log("helloWorld")
}

```

How functions are executed
```
var x = 1
a ();
b ();

function a (){
    var x = 10;
    console.log(x);
}

function b (){
    var x = 100;
    console.log(x);
}

```


The Scope Chain, 🔥Scope & Lexical Environment 

Lexical Environment = Local Memory + reference to lexical environment of parent

Chain of lexical environment is scope chain



Syntax Error 
```javascript

// Example 1

let a = 1000
let a = 10

// Example 2 
const a ;

//Uncaught SyntaxError: Identifier 'a' has already been declared
```

Reference Error 

```javascript
console.log(a)

//Uncaught ReferenceError: a is not defined
```

Type Error 

```javascript
const a = 1000
a = 50

//Uncaught TypeError: Assignment to constant variable.
```

Block - Combined Statement 

perfectly valid js code
```
{

}
```
{

}

Shadowing
```
var a = 100

{
    var a = 10
    console.log(a)

}

console.log(a)
```
output : 

10
10


The variables and functions we can access inside the block is called block scope


function along with its lexical scope forms a closure
