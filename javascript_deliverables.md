##JS + JQUERY

### JAVASCRIPT FROM THE CONSOLE: STYLE AND BASICS

* SWBAT employ capitalization appropriately when naming variables, functions, and objects, according to JS best practices.

* SWBAT properly ident and format their code according to JS best practices.

* SWBAT recognize and write the syntax for both a single line and block comment in JS.

* SWBAT define and use the term 'corner case', and be able to identify and properly address them in their code.

#### Values, Variables, and Control Flow
* SWBAT identify and use the `var` keyword to assign to variables the six basic types of values in JS: numbers, strings, Booleans, objects, functions, and undefined values.

* SWBAT articulate the relationship between variables, their values, and the values as data in memory.

* SWBAT differentiate between statically and dynamically typed languages and explain the pros and cons of each.

* SWBAT perform basic arithmetic in simple JS programs and the JS console, using `+`, `-`, `*`, `/`, and `%`.

* SWBAT differentiate between the use of `'` and `"` for string values and be able to appropriately escape special characters using `\` when required.

* SWBAT manipulate string values by using the `split`, `charAt`, and `slice` methods.

* SWBAT identify and articulate the difference between unary and binary operators (e.g. `typeof "x"`, vs `10 > 2`).

* SWBAT use comparison operators to produce boolean values, and understand the assumptions Javascript makes for non-quantitative values (e.g. capital chars > lowercase chars).

* SWBAT define automatic type conversion in JS, identify those situations where it will occur, articualte the dangers of it, and employ the `===` and `!==` operators to avoid it.

* SWBAT articulate the difference between expressions and statements and describe their relationship in the context of a simple program.

* SWBAT define what a program's "environment" is, recognize the elements within a simple program that comprise its environment, and understand those events which can cause an environment to change.

* SWBAT use shorthand, e.g. `+=` or `++`, to succinctly update variable values.

* SWBAT employ the `if`, `while`, `do`, `for` and `switch` statements to conditionally control the flow of a simple javascript program.

* SWBAT understand how and when to employ the `break` keyword to escape a loop.

* SWBAT define and differnetiate 'local scope', 'global scope' and 'nested scope', and be able to employ this understanding to appropriately declare functions and variables in a simple javascript program.

* SWBAT identify the 'scope' of a variable, and use the location of a variable declaration to identify where that variable is accessible.

#### Functions

* SWBAT identify and write syntactically correct JS functions that are either named, or anonymous, which take parameters and return values.

* SWBAT call JS functions, either named or anonymous, that take parameters, and be able to reliably predict and use the return values.

* SWBAT employ the `prompt`, `confirm`, `alert` and `print` functions to create a simple console user interface.

* SWBAT articulate how 'definition order' implementation in javascript allows one to define functions anywhere in a simple javascript program.

* SWBAT articulate how the stack coordinates the execution of a program by saving the context a function is in when it is called so that it can return to the proper time/space during runtime.

* SWBAT explain how "everything in Javascript is a value", and the implications for how functions are implemented and should be employed.

* SWBAT define, recognize, and write a closure, while also being able to articulate why the structure exists.

* SWBAT identify side effects in their function definitions and be able to "purify" them whenever possible.

* SWBAT define recursion, write and recognize a recursive function, and be able to explain the pros and cons, particularly performace concerns, when using recursive functions in JS.

* SWBAT articulate the values and practices of functional programming and be able to refactor their code using higher-order functions, modifying functions, operator functions, partial application, and composition to improve the abstraction of their javascript.

#### Data Structures: Objects and Arrays

* SWBAT understand objects as collections of properties, and be able to write and read the syntax to define an object, add a property/value, delete a property/value, and check if a property exists in an object.

* SWBAT define the term 'mutability' and explain the relationship between the value of an object and a reference to it, as well the implications this has for comparing objects.

* SWBAT identify an Array as a special type of object, and be able to intelligently decide when and why to use an Array instead of an object.

* SWBAT manipulate an array employing the `pop`, `join`, and `push` methods.

* SWBAT to iterate over arrays and objects using previously learned control flow structures as well as `for ... in`.

* SWBAT identify which properties of an object are 'enumerable' and which are not, and be able to explain why this is the case and the implications of such.

* SWBAT define and use constructors to create objects from pre-existing JS classes.

#### Error Handling

* SWBAT approach error handling with the understanding that the program should fail as quickly as possible, in a way that makes it clear what went wrong.

* SWBAT differentiate between errors caused by programmer error and runtime errors and handle each appropriately according to JS best practices.

* SWBAT use the keywords `try`, `throw`, and `finally`, to catch exceptions in the context where/when an error occured, i.e. without unwinding the stack.

* SWBAT employ Error objects to provide a description of the exception they raise.

#### Object Orientation in Javascript

* SWBAT design objects with a limited, well-defined interface and be able to articulate the virtues of such.

* SWBAT attach functions to objects, or define functions within them, as well as call such methods using dot-notation, `apply`, and `call`.

* SWBAT articulate prototypical inheritance, including the process by which the search for a value travel up the ancestor tree from object to prototype to prototype of prototype, etc. 

* SWBAT differeniate between fetching and setting a value in an object as it relates to that object's position in the inheritance hierarchy.

* SWBAT explain when/if the modification of a prototype will modify an object of that type.

* SWBAT articulate the concept of `this` and explain how it is used implicitly and can be used explcitly in a simple javascript program.

* SWBAT employ polymorphism to create and refactor an interface and the objects it interacts with to decouple their code and create more maintainable javascript programs.

* SWBAT define and differentiate the terms 'constructor' and 'prototype', and use each accordingly.

* SWBAT define types for the purposes of using inheritance in 2 ways: 1) cloning the constructor and 2) cloning the prototype. They should also be able to explain the pros and cons of each technique.

* SWBAT use the `instanceOf` operator to determine whether an object is based on a certain prototype.

* SWBAT define multiple-inheritance and explain, at a high-level, explain how it might be implemented in a simple JS program, but why it is generally a bad practice.

* modules??

### JAVACSRIPT AND THE BROWSER/WEB

* SWBAT explain how a browser builds the DOM based on HTML received from an HTTP request.

* SWBAT articulate a definition of the Document Object Model, identify nodes and content, and navigate the heirarchy of objects by understanding the parent/child/sibling relationship of the objects it's composed of.

* SWBAT script a form in javascript.

* SWBAT explain how a form is able to produce parameters that can be appended to a URI, and why doing such a thing would be useful.

* SWBAT access DOM elements using `getElementById` and `getElementByTagName`, create elements and text nodes using `createElement` and `createTextNode`, and get and set attributes of elements using `getAttribute` and `setAttribute`.

* SWBAT manipulate elements by changing the values of the `className`, `style`, and `display` properties. 

* SWBAT articulate how events occur in the browser, what bubbling up (propagation) is, and how to normalize such events.

* SWBAT explain what it means to say javascript handles events in a 'single-threaded' way as opposed to 'multi-threaded'.

* SWBAT register an event handler by either 1) setting a property of a node corresponding to the event name (e.g. `onClick`), or 2) using `attachEvent`.

* SWBAT recognize and write handlers for basic mouse-related and keyboard events, including `mouseup/down`, `click`, `pageX/Y`, `mouseover`, `mouseout`, `scrollleft/top/etc`, `keyup/down/press`. 

* SWBAT create a simple request object in javascript that can handle HTML, XML, and JSON responses. 

### JQUERY

* SWBAT articulate the relationship between javascript and the jQuery and explain what the tradeoffs are for using each.

* SWBAT explain the difficulty of dealing with different browser's DOM interface and, at a high level, how jQuery alleviates this issue.

* SWBAT download jQuery, load it into their HTML pages, and employ it in an internal or external script.

* SWBAT use element, id, class, compound, descendent, and child CSS selectors to find elements in the DOM.

* SWBAT use CSS-like pseudo classes to select only specific elements that are returned by a any CSS selector.

* SWBAT use the `text` method to retrieve and update the content from/in text nodes.

* SWBAT properly handle the `$(document).ready()` event to have their javascript run only after the DOM is fully built by the broswer.

* SWBAT to explain the term 'traversing the DOM', break it down into its `selection` and `find` components, and explain the implementation and performance tradeoffs in using traversal vs selectors.

* SWBAT to explain `walking the DOM` traversals using the `next`, `prev`, `parent`, and `child\`children` methods.

* SWBAT create new DOM nodes and append them to the DOM using `append/prepend`, `after/before`, `appendTo/prependTo`, and `insertBefore/insertAfter` methods.

* SWBAT emply the `on` method to add an event handler to a DOM element.

* SWBAT refactor event handlers that use selectors by converting them to traversals using `this` and `closest` to make their code more specific and maintainable.

* SWBAT employ data tags to HTML elements to provide additional information about elements on a page and interact with them using the `data` method.



* add/remove/toggle class
* callbacks lmao

* change markup NOT css

### JAVASCRIPT LIBRARIES

* SWBAT search for, evaluate and employ javascript libraries intelligently, with an eye towards performance, code maintainability, and user experience.

* SWBAT articulate and intelligently engage with the current debate over progressive enhancement vs full frontend javascript framework usage.

* templating with mustache
* frontend MVCs
* d3 or hi charts?