# Summary of Function and Array

## 1. JavaScript Array Methods
[Array Methods](https://www.w3schools.com/js/js_array_methods.asp)

JavaScript Array Methods are inbuilt Js functions that are associated with arrays, they are of different types, they include:
* **Array length** - Returns the length (size) of an array
* **Array toString()** - Converts an array to a string of the array values(i.e, converts it from an array ([]) to its string representation separated by commas)
* **Array pop()** - Removes the last element from an array.
* **Array push()** - Adds a new element to the end of an array.
* **Array shift()** - Removes the first element in an array and shifts all other elements to a lower index
* **Array unshift()** - Adds a new element to the beginning of an array and return a new array length
* **Array join()** - Joins all array elements into a string with an optional separator.
* **Array delete()** - It can be used to Deletes array elements, but it leaves undefined holes therefore pop() or shift() should be used instead.
* **Merging (Concatenating) Arrays** - Creates a new array by merging existing arrays (to concert more than 1 array into an existing array use comma i.e arr1.concat(arr2, arr3)).
* **Array flat()** - Creates a new array with sub-array elements concatenated to a specified depth.
* **Array splice()** - Adds new items to an array or removes items using clever parameter setting 
to use - (x, y, "new item", "new item" ...)
x - the position where the new elements should be added (spliced in)
y - defines how many elements should be removed.
new items - define the new elements to be added.
* **Array slice()** - Slices out a piece of an array into a new array without modifying the source array. 
to use - (x, y)
x - starting point
y - ending point (but not ibncluded).



## 2. JavaScript Functions
[JavaScript Functions](https://www.w3schools.com/js/js_functions.asp)

A JavaScript function is a block of code designed to perform a specific task and can only execute when it is invoked.

### JavaScript Function Syntax
A function is written using the function keyword followed by a name, then parentheses (). The parentheses may include parameter names separated by commas. The code to be executed by the function is placed inside curly brackets {}

### Function Return
When JavaScript encounters a return statement, the function will stop execution. The value specified in the return statement is then sent back to the caller.

### The () Operator
The () operator invokes (calls) the function
Accessing a function with incorrect parameters can return an incorrect answer
Accessing a function without () returns the function and not the function result

### Functions Used as Variable Values
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.
Variables declared within a JavaScript function, become LOCAL to the function.


## 3. JavaScript Functions 2
[JavaScript Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)

### Function Return
if a function's execution doesn't end at a return statement, or if the return keyword doesn't have an expression after it, then the return value is undefined


## 4. Control Flow Statements
[Control Flow Statements](https://www.javascripthelp.org/learn/basics/control-flow-statements/)

Control flow statements allow you to control the order in which statements are executed in your program, based on certain conditions or criteria. In JavaScript, there are three main types of control flow statements:

* if/else statements
* switch statements
* loops

### If/Else Statements
If/else statements are used to execute a block of code if a certain condition is true, and a different block of code if the condition is false.

### Switch Statements
Switch statements are used to execute a block of code based on the value of a variable or expression.

### Loops
Loops are used to execute a block of code multiple times, based on a certain condition. The loops in JavaScripts include
* For Loops
* while loops
* While and Do…While Loops


## 5. Functions 3
[Functions 3](https://javascript.info/function-basics) 

Functions are the main “building blocks” of the program. They allow the code to be called many times without repetition.
Examples of built-in functions include:  alert(message), prompt(message, default), confirm(question) et.c

### Function Declaration
### Local variables
### Outer variables
### Default values - 
If a function is called without providing an argument, the corresponding parameter value becomes undefined. In such cases, default values can be used to prevent the parameter from being undefined
### Function naming
* when naming functions in JavaScript, it is important to choose names that clearly describe the function's purpose and the value it returns
* Function names should be verbal, representing actions. 
* This naming convention enhances code readability and understanding during function calls