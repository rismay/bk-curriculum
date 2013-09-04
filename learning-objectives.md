### NYC WEB DEVELOPMENT FELLOWSHIP
# LEARNING OBJECTIVES: Fall 2013

 - 4 weeks - prework
 - 14 weeks - content work
 - 4 weeks - project work
 
** SWBAT == Students Will Be Able To

##GIT + COMMAND LINE + ENV

##THE INTERNET

* SWBAT explain what the client and the server are, and their role in serving a simple website. 
* SWBAT recognize and identify the specific tasks of frontend and backend developers, and be able to confidently discuss the languages, frameworks, and tools unique to each discipline.

* SWBAT rehearse a brief history of web browsers, and in doing so, identify why the evolution of the browser is relevant to web development. 

* SWBAT explain what web standards are, how they are defined, and their relationship to browsers, working groups, and standards bodies.

* SWBAT explain the significance of html5 and css3 and identify the subsequent implications for the future of web standards.

* SWBAT explain what the word, "semantic", means in relation to web development and articulate its role in the evolution of web standards, programming styles, and best practices.

* SWBAT articulate why performance is a particular concern in web development, as well as a high level understanding of best practices for improving the performance of any website or web app.

* SWBAT employ browser developer tools to effectively investigate and debug both local and remote websites and apps.

## MARKUP AND STYLES 

###HTML AND CSS

* SWBAT identify the roles of HTML (content), CSS (styles), and JS (interaction), in the creation of a website and recognize and remedy classic antipatterns that demonstrate a conflation of these roles.

* SWBAT write and recognize the syntax of element, id, class, and compound selectors and understand the DOM elements they apply to.

* SWBAT employ specificity and location to properly control the cascade of their style declarations, and articulate this by employing a strategy that quantifies the priority of a selector based on its composition.

* SWBAT position elements using both the float and position attributes, and be able to properly articulate the relationship positioned elements now have with other elements in the DOM.

* SWBAT articulate historical attempts at clear solutions, identify them as anti-patterns, and successfully refactor them to properly implement the semantic cross-browser friendly clear fix. 
* SWBAT employ an understanding of the box model attributes (content, padding, border, margin) to successfully space elements and predict element width and height.

* SWBAT refactor (or DRY up) stylesheets by using inheritance, combining selectors, employing selector abstraction, and using display types.

* SWBAT properly use and identify style shorthand, and be able to articulate when and why to use it.

* SWBAT identify the default display type of any common html and element and be able to explain how and why to use the display attribute to change an elements display type.

* SWBAT center any html element, and be able to articulate why and how the centering technique differs for block vs inline elements.

* SWBAT recognize good vs bad online frontend development resources, and be able to query such resources appropriately to find relevant help.

* SWBAT apply twitter bootstrap, HTML5 boilerplate, and CSS resets to expedite their frontend design experience, while also being able to articulate the tradeoffs these tools introduce.

###WEB DESIGN

* SWBAT define the terms 'progressive enhancement' and 'graceful degradation' and articulate, at a high level, the best practices that compose these guiding principles.

* SWBAT identify responsive web design patterns (fluid grid, @media queries, collapsing navbars) and have a high-level understanding of their implementation.

* SWBAT articulate the specific and unique concerns introduced by designing for mobile devices (screen dimensions, character encoding, performance) and have a high-level understanding of their implementation (user agent sniffing, offline caching).

###SASS

* SWBAT employ SASS as a tool to create maintainable, modular stylesheets by using the variable and mixin features.

* SWBAT write and recognize SASS nested selector syntax and be able to articulate the performance vs readabiliy tradeoffs such a feature allows.

* SWBAT refactor (DRY up) their stylesheets by employing SASS selector inheritance.

* SWBAT architect a directory structure and run the SASS command from the terminal to successfully compile SASS/SCSS to CSS.

* SWBAT architect a Sinatra web application to use SASS and COMPASS to produce CSS.

* SWBAT architect a Rails web application to use SASS and COMPASS to produce CSS.

* SWBAT creating custom SASS helpers

###ERB, HAML, and MARKDOWN

* SWBAT write, read, edit, and debug, basic ERB syntax, including loops, iteration, method calls, and interpolation.

* SWBAT write, read, edit, and debug, basic HAML syntax, including loops, iteration, method calls, and interpolation.

* SWBAT write, read, edit, and debug, basic Markdown syntax, including headings, lists, nested lists, code blocks, and inline code.

* SWBAT employ filters while using HAML to address specific content markup needs.

##JS + JQUERY

* SWBAT articulate the relationship between javascript and the jQuery and explain what the tradeoffs are for using each.

* SWBAT search for, evaluate and employ javascript libraries intelligently, with an eye towards performance, code maintainability, and user experience.

* SWBAT articulate and intelligently engage with the current debate over progressive enhancement vs javascript MVC usage.

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

#### Functional and Object-Oriented Styles and Best Practices

* SWBAT articulate the values and practices of functional programming and be able to refactor their code using higher-order functions, modifying functions, operator functions, partial application, and composition to improve the abstraction of their javascript.


* searching
* modularity
* side effects

### JAVACSRIPT AND THE BROWSER/WEB
* web programming
* wtf is the DOM
* browser events
* review HTTP requests

* JSON

### JQUERY

* jquery is terrible. long live jquery.
* when to use jquery and why.
* review css selector syntax
* parent/child ancestor/descendant relationship (review)
* add/remove/toggle class
* append prepend before after
* browser events in jquery
* callbacks lmao

* change markup NOT css

### JAVASCRIPT LIBRARIES
* templating with mustache
* frontend MVCs
* d3 or hi charts?


##RUBY

### ENVIRONMENT
* rspec, guard, irb, ruby keyword, installation

### PROGRAMMING BASICS, DATA STRUCTURES and ITERATION
* variables
* what does dynamic typing mean?
* arrays and hashes
* iteration + enumerable methods
* negotiating complex data structures

### METHODS
* methods + parameters + return values
* chaining
* control flow structures

### OBJECTS
* classes + objects + modules
* instance variables and methods
* class variables and constants
* inheritance

### RUBYGEMS
* rubygems - what are they
* oauth
* nokogiri

### PROGRAMMING STYLE AND BEST PRACTICES
* functional vs oo ruby
* object interfaces
* refactoring anti patterns
* metaprogramming (method_missing<- mention when talking about inheritance)

##TESTING

##RACK + SINATRA

* web applications: server side? client side?
* ruby server side applications
* web dev is fancy string concatenation
* single page app with rack
* why the url and routes are so goddamn important
* sinatra routing
* sinatra app architecture
* separation of concerns - keeping your logic out of your views
* using partials
* sinatra models + concerns
* rubygems with bundler
* sinatra and datamapper
* sinatra and active record

##DATABASES + SQL + DATA MODELING

##RAILS - BEGINNER

##RAILS - ADVANCED



