## Javascript 101 


### How Javascript Works
Everything in JS happens inside an execution context.

Two components in Execution Context
- Memory Component / Variable environment (key, value) pairs
- Code Component / Thread of Execution 

Javascript is Synchronous Single Threaded Language - (like python)

### How Javascript Code is Executed

What happens when you run Javascipt Program ?

Execution Context is created in Two Phases

Phase one - Memory Creation Phase

Javascript allocates memory to all variables.
For variables it stores undefined and for functions it stores the whole code in memory space.

Phase two - Code Execution Phase

All variable get their values line by line.
Function behave differently in Javascript. When you invoke a function a brand new execution context is created.
After returning the function value whole Execution Context will be deleted.


JS Engine manages The execution context with Call Stack.

Call stack maintains the order of execution of Execution Context.

Call Stack is also know as 
- Execution Context Stack
- Program Stack
- Control Stack
- Runtime Stack
- Machine Stack

### Hoisting in Javascript

Hoisting is Javascripts default behaviour, where JavaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables or classes to the top of their scope, prior to execution of the code. 

// function 
function getName (){

}

// behaves like variable so allocates memory like a place holder with undefined
var getName = () => {

}

// behaves like variable so allocates memory like a place holder with undefined

var getName = function (){

}

### uncaught Reference Error vs undefined

var x = 7

called before memory execution phase gives undefined
no reference provided it will be not defined


### How functions work in JS








