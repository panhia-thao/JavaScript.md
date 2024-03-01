JavaScript

## JavaScript Object Syntax

Object's building blocks are commonly referred to as its fields or properties

    Properties = aspect of object
    Object literal notation

## What happens in event propagation? 

There are two event that happens at event propagation. 

> Event bubbling vs. Event Capture

*Best Practice:*
    Never ID HTML = its a window

Summary: Event propagation occurs on the DOM element such as a click and the browser follows the process call event propagation that has two phases of event propagation: event capture which is the process the event from the root to the element. Event bubble the browser process the target element back to the roo of the DOM tree. 
    

Exercise:

1. Event bubbling: 
    Answer: Child > Parent
2. Event capture: 
    Answer: Parent to Child

        step 1: Click
        stetp 2: capture
        step 3: capture = default = false

        if you change to ture it start @ parent by default addeventlistneer by default is event bubbling.

3. In the event if a child element is click explain the event process? 

        window
            <body>
                <ol>
                    <li>
                    <li>
                    <li>
                </ol>
            </body>
        window
    Answer: Top > down (capture) and then back up (bubble) again like a circle. first click =(grandparent to parent to child) and going back up the parent element becomes true when bubbling up = (child to parent to grandparent return true)



Execute vs Event

Execute: run a function, a block of code or a statement console.log()

## What is a function definition? 


A function definition in JavaScript is a block of code that specifies the behavior of a function. It includes the function's name, parameters (if any), and the statements that define what the function does when it is called.

        function greet(name) {
        return "Hello, " + name + "!";
    }


1. Does a function need to be executed or does it need to do something first? 
    Answer: All callback functions are fnction definition

## What is arrow function? 

() => is a anonymous function. It is a function definition

## What is a callback function? 


Callback function is used in event handling to execute specific code when an event occurs



## Console for browser vs Window Command Prompt

Browser

using function definition, arrow function and return

Command Prompt Programs
Each programs has special *keyword* for git for VS = code




