# Module Pattern 

### Three old fashion way

Module pattern in Js is a design code that is reusable. It allows you to create private and public methods and variables

        var Module = (function() {
            // Private variables and functions
            var privateVar = 'I am private';

            function privateFunction() {
                console.log('This is a private function');
            }

            // Public interface
            return {
                publicVar: 'I am public',
                publicFunction: function() {
                    console.log('This is a public function');
                }
            };
        })();

        // Example usage
        console.log(Module.publicVar); // Output: I am public
        Module.publicFunction(); // Output: This is a public function

        // The following will not work
        console.log(Module.privateVar); // Output: undefined
        Module.privateFunction(); // Output: TypeError: Module.privateFunction is not a function


attribute called is = 
expanding-list"

### How do you make expanding list possible? 

HTML UL LIst

### Lifecycle callbacks

connect callback -invoke each time a custom element
Expanding list extends HTMLListElement 
    constructor() {}
    super() {}
        connectedCallback() 
        disconnectCallback()
        adoptedCallback()
        atrributeChanged

1. Connect callback() - our custom element is connected to the DOM
2. disconnectedCallback() - our elements is not connected
3. adoptcallback() - iframe has been move to another website page not page or tags
4. AttributeChangeCallback() - when user wants to change the attribute and this requires 3 parameter that is pass in. 
    1. the name = attribute
    2. previous value = old value
    3. new value = new value

Ex. 

attribute (the name, p.value, n.value)

attribute (description,helw)

chatgpt: 
The lifecycle for custom elements consists of several stages, each with its corresponding callback methods. These callback methods allow you to define behavior at different points in the element's lifecycle. The lifecycle stages and their corresponding callbacks are as follows:

### best practice for custom elements

Using data- attributes in custom elements is a best practice for several reasons, including readability, maintainability, and compatibility with HTML standards. When you create custom elements, using data- attributes helps ensure that your attributes do not conflict with standard HTML attributes and are easily identifiable as custom attributes.


*need to continue notes from book*

