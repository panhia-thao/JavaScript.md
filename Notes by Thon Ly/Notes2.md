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



## Console for browser vs Window Command Prompt

Browser

using function definition, arrow function and return

Command Prompt Programs
Each programs has special *keyword* for git for VS = code




