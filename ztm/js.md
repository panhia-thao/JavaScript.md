# JavaScript 

Course Outline

* Javascript
* development environment
* git 
* profile NPM/NPM Scripts
* react.js
* node.js
* databases


## Introduction


js was created by netscape in 1995

what is js? 
It is a file of commands or direction.

Netscape browser was the first browser to use js.

All website, vr, drone, robot use js. 

data type 

1. Number
2. string
3. boolean
4. undefined
5. null
6. symbol
7. objec

JAVASCRIPT COMPARISONS
-----------------

!==
===
>=
<=
>
<

JAVASCRIPT VARIABLES
-----------------
var
<!-- let (new in ECMAScript 6)-->  
<!-- const (new in ECMAScript 6)-->

JAVASCRIPT CONDITIONALS
-----------------aq 
if
else
else if
<!-- ternary operator -->
<!-- switch -->


JAVASCRIPT LOGICAL OPERATORS
-----------------
&&
||
!

JAVASCRIPT FUNCTIONS
-----------------
var a = function name() {}
function name() {}
return
<!-- () => (new in ECMAScript 6) -->

JAVASCRIPT DATA STRUCTURES
-----------------
Array
Object

JAVASCRIPT LOOPING
-----------------
for
while
do 
forEach (new in ECMAScript 5) 


JAVASCRIPT KEYWORDS
-----------------
break
case
catch
class
const
continue
debugger
default
delete
do
else
export
extends
finally
for
function
if
import
in
instanceof
new
return
super
switch
this
throw
try
typeof
var
void
while
with
yield


what is variable

variable to hold any js data type

; = semicolon means end of expression

expression= is anything that is written 
undefined = variable is not assign

to create a html doc just use command 
>!(tab)

the script tag is for javaScript and its best practice to put it on the bottom or defer it if its on top due to loading. 
You want to load html and css file before js. 

alert() 
prompt() its a function that pops up a prompt it has its own screen
console.log() 

Js has built in functions. 
arguments are what is given to the function for example 
console.log("hello") > "hello" is the argument 
you can have multiple of arguments.

There are two ways to create functions: 

    function sayHello() {
        console.log("hello");
    }

We need to run a function to see it in the console

    sayHello() 


What is a function? 

Function

> input (5, 10) > function > return

In a function we need to return to not get *undefine*  by using *return*

Functions are variables 

parameter and arguments are interchangable 

What is parameters? 
how many paramenters (a,b)

What is arguement?  are (4,5)
what are the arguements

What are premitives? 

primitive value or primitive type are not object, methods or properties and are immutable (cannot be alter)

 There are 7 primitive data types:

string
number
bigint
boolean
undefined
symbol
null

## Data Structures: Arrays

data structures are components that stores data using bracket notation 

What is an array? 

A container that holds a list of different types of data, the first list is called index 0. It always start with 0

A list

> var list = ["tiger", "cat", "bird", "bear"];
> var booleans = ["true", "false", "true", "true"] 
> var mixlist = ["tiger", "true", "3", "undefined"]
> var list2 = [["tiger", "cat", "bird", "bear"]] // this is an array inside an array



console.log(list[0])

An array is a nice list that allow us to organize our list

list of built in array methods

join()
slice()
indexof()
length
push()
splice()

Method special treatment for empty slots
    concat(), copyWithin(), every(), filter(), flat(), flatMap(), forEach(), indexOf(), lastIndexOf(), map(), reduce(), reduceRight(), reverse(), slice(), some(), sort(), and splice(). 

concat and copyWithin does not perserve empty slots when copying 

Methods that 


## Objects
data structure
-collections of property
James, 34, married, soccer

objects {} is property and value

    var user = {
        user = "john";
        age: 34;
        hobby: "soccer";
        isMarried: false;
    }

    var list = ["apple", "banana", "orange"]

Can i have list of users? Yes

    var list = {
        0: "John";
        1: 34
        2: "soccer"
    }

Why is an array and object not a data type? both are both very organization but data structure

They are the same 

object === user info.

array === list or to do list

can I have a array inside an object? yes
va user {
    username: "john",
    spells: ["boo", "hehehe"],
}


var list = [
    {
        username: andy
        pw: "secret"
    }, 
    {
        username: "pa", 
        pw: "secret"
    }
]

# null 

if a list or a variable is empty it can be undefined. 
If you have an empty object it can be null meaning that the object is null. 

Null means empty objects

## FB mini notes

To create fb we need a database 

Need to have username and pw to login.
Once logged in, You have newsfeed. 

how do we build a sign in ?

browser open fb. 


# Overview

Expression produce a value

    1+3;
    var a =3;
    return true;

Calling or invoking a function 

    alert();
    newFunction(param1, parem2)


# if else statements 

NEED TO LEARN


#  Loop 

For loop

    for (var i=0; i< todos.length; i++) {

    }

forEach();


# JavaScript Keywords

Cannot use keywords because its built into the js lango


JAVASCRIPT KEYWORDS
-----------------
break
case
catch
class
const
continue
debugger
default
delete
do
else
export
extends
finally
for
function
if
import
in
instanceof
new
return
super
switch
this
throw
try
typeof
var
void
while
with
yield

# Document Object Model

change all html element
change all html attributes

we can change using js while user is on the website

What is the DOM? 

Document Object Model that defines a standard for accessing docs. 

The w3c standard is separated into 3 different parts: 

Core DOM - standard model for all document types
XML DOM - standard model for XML documents


HTML DOM - standard model for HTML documents

HTML DOM methods are actions you can perform (on HTML Elements).

HTML DOM properties are values (of HTML Elements) that you can set or change.



the HTML elements as objects
The HTML DOM is a standard for how to get, change, add, or delete HTML elements.

is simply a document that change be change using html and css files. 

Each browser has a js engine with different name for example

chrome === v8 engine
safari === Nitros
explorer/edge === chakra core
firefox === spider monkey

these js engine execute and read js filethe 

window is an object with a


the browser create the dom and then 

 
DOM Selectors
--------------
getElementsByTagName
getElementsByClassName
getElementById

querySelector
querySelectorAll

getAttribute
setAttribute

##Changing Styles
style.{property} //ok

className //best
classList //best

classList.add
classList.remove
classList.toggle

##Bonus
innerHTML //DANGEROUS

parentElement
children

##It is important to CACHE selectors in variables


## KeyboardEvent: key property


Keyboardevent interface's  key 

read-only property that returns the value of key pressed by the user. 

Keyboard are pre-defined key values

dead key are key vlaue must be dead

if key cannot be id it returned unindentified

## what is JavaScript Char Codes (key codes)

https://www.cambiaresearch.com/articles/15/javascript-char-codes-key-codes

    const log = document.getElementById("log");
    const input = document.querySelector("input");

    input.addEventListener("keypress", logKey);

    function logKey(e) {
    log.textContent += ` ${e.code}`;
    }


Event Reference 

arise from user interaction 
> moving a mouse
>resizing a window

Event index

animation, asynchronous data fetching, clipboard, composition, css transition, database, dom mutation, focus form

event reference 
https://developer.mozilla.org/en-US/docs/Web/Events


## callback function


## JQuery
https://youmightnotneedjquery.com/

caniuse
JQuery solve the problem of checking elements are compatible with browser. 

making element incompatibility === compatibility

Syntax code of JQuery
>$(selector).action()

        1.  $ is a reference to the jQuery object (it's a function).
        2. selector is used to select HTML elements to manipulate.
        3. action() is a method to perform on the selected elements.

this is like call back function

        p.addEventListener("click", ())AZ  

jQuery once made JS very easy and adaptive to web browser but now querySelector is used instead of JQuery.

To view the different of jquery usage and querySelector

React is a library that solve the problem of Jquery. 

History of the Web:
 Html > CSS > JS > jQuery > libraries

## DOM manipulation

DOM manipulation is changing the HTML element and their attribute. 

DOM manipulation is a fundamental aspect of front-end web development and is used to create dynamic and interactive web pages.

## Developer fundamentals: V 

Performance is key. 

     Minimized backend request
    1. Location of server
    2. How many trips
    3. Size of files

minimized the dom manipulation and event and use the best method

This is the reason for React. 

## Scope

Root or parent scoop

it is in the window scope

any function has access to variable. 
        var b = 5;
        function add5(num) {
            5+num
            console.log(add5)
        }


local vs global

make sure our code is run  when run accidental interference. 



# Advanced Control Flow

Ternary Operation

Condition? exper1: exper2
function isUserValid(boolean) {
    return boolean;
}

var answer = isUserValid(true) ? "enter" : "access denied"

Switch Statement is better than if else

What is a library? 
a piece of code that makes it easier to use. 

ECMAScript 6 

ECMA Internation === standarized js language

ES6 stands for ECMAScript 6

What is babel? 
Babel is a js compile that makes js code more cleaner 

    const a = (x,z) => x+z;


const = variable cannot be change
var = a global variable
let = reassign variable for changing

declaring object 



template string

    ${variable}

function greeting(name, age, )

arrow function 

(a,b) => {}

## Advanced Functions

### scope 

local scope - variable that are accessible only within the function (local scope) 

global scope - variable that are accessible from anywhere in the code

closure - a closure function access variables from its parent scope, it remember its environment in which it was created, including any variable that wree in a scope at the time. 
        function outerFunction() {
        let outerVariable = 'I am outer';

        function innerFunction() {
            console.log(outerVariable);
        }

        return innerFunction;
        }

        const myClosure = outerFunction();
        myClosure(); // Output: I am outer



Scope prevents bugs or errors


What is Curry?

currying is a technique used to transform a function with multiple arguments into a sequence of nested functions, each taking a single argument. The curried function allows you to pass arguments one at a time and returns a new function with each argument until all arguments are provided and the original function is invoked.

        function multiply(a) {
        return function(b) {
            return a * b;
        };
        }

const multiplyByTwo = multiply(2);
console.log(multiplyByTwo(3)); // Output: 6

What is a compose? 

 is the act of combining two or more functions to produce a new function


        function addTwo(x) {
        return x + 2;
        }



## Avoiding side effects and functional purity

avoid side effects and functional purity and deterministic. 

*As a coder you want to create function that minized side effects and has functional purity. This means that the function is deterministic.


## Arrays

ForEach

## Advance Object

objects are reference type






