# JavaScript

# Window

      Js > Window > function > variable 

The first child of window is function.
 variable and function are the children of window. 
a function can have as many children (function and variable) as it wants. 
a variable stores function and object such as document window



#### Object

Object has *property* and *method*

JS = property variable = method/function

#### Font Size

Always important to define the font size in the body before putting font-size on any tags due to different browser. Html elements font size has different font-size default. 

    Define font-size on body

<body> should have a *pt or px* for font
child of <body> can be em

#### Syntax for Variables
1. HTML - (Hyphenated)
2. CSS - Based on HTML (Hyphenated)
3. JS - Camel Case

#### Variables

There are variable that re reserved varibles. This means that some words cannot be use because it is special or already use by the program. 

var = " ";  this is conside a empty string

All "const" variable need to be capitalized. 

Variable are files that save data. 

Example of variables are: 

        Var, Let, Const,== these are capitalized

### Undefine

no return will always be undefine

### Function Scope

There are two types of function scope. 
        
    Local scope (Gobal Scope) vs. Outer Scope

        
The local scope is the immediate family inside the function. The local scope of window has special global scope. These are basically the child of the window.
The outer scope is the first layer of the function (siblings)

Execution in JS does not need to be exactly below its function but within the tree scope. 
Any level tree structure can execute in the function. 

        Execution goes up.
        Fuction does down

When you want to *get* a variable or *call* a function in js. The computer look at local if it cannot look for it. it will go up to the outer scope. If it cannot find the function it is undefine or not defined. 
        Function and variable excute inside JavaScript.

variable const cannot be higher and cannot go into out function


There are three places to execute functions

        1. HTML as onclick
        2. Console
        3. Js in the code function()



#### Function
Functions are reusable. 

Function return or returns undefined

        undefined == there is a function
        not defined == there is a error, no function



#### log()

new function window: console can be use in Js
console.log("panhia")
the function logs keep what you want in the log()

