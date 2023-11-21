# Learn to Code with JavaScript &amp; Python

The ultimate guide to learning to code in the world's two most popular languages!
By JOG

We need to decide about exercises/challenges for the end of each chapter - could actually be at the end of each section instead?
Or maybe have mini challenges at the end of each chapter (Code Wars style with links to more Code Wars as well?) and then a bigger project at the end of each section?
Also should there be a big project that builds up throughout the book or just exercises to do? I think I prefer exercises rather than a big challenge
I also think it might be a god idea to link to Code Wars challenges that are suitable at various stages

# Section 1: Introduction, Syntax and Key Features

## Intro, programming, pseudocode

##  Python vs Js 
technical, general use, development - for work/jobs

Both a multi-paradigm language - however Python is more suited to imperative and OOP ... and data processing?, where as JS (after the ES6 updates) is more suited to imperative and functional (OOP in JS is widely avoided). React has really popularised functional programming in JS, they had classes to start with then ditched them.

They are the two most popular languages in the world (add stats), which is why it's very useful to be familiar with both.

Both have low barriers to entry - JS can be coded in the browser using CodePen. Python is pretty easy to set up and use - Linux and Mac come with it already installed (I think!)

They are both very powerful languages, however they differ in their specialisms.

JavaScript is an event based language which is why it is the main language used for frontend web development. Vanilla JS will only run in the browser and therefore on the client. However, advances in JavaScript, such as nodejs (and Dino and Bun) mean that server side processing (backend development) can be written in JavaScript as well. Meaning a whole full-stack application can be written in JS.

Whilst Python can be used for web development, it doesn't really specialise in this. Predominantly used in more scientific scenarios such as data science, data analysis and graph modelling. This is due to its powerful mathematical libraries. Python is sometimes used for backend development as well, e.g. Flask.

A lot of people tend to have Python as the language they learn first, and have JavaScript as their second. This is due to it's easy syntax (very much like english). A lot of schools likewise begin with Python. And uni courses also tend to emphasise Python as a first language and JS as second. However, as people progress into careers, Python tends to fade out and JavaScript is what is most predominantly asked for. 

Therefore, learn them both together!

## First program 
Hello World - console.log vs print

## Variables 
variable declaration, data types, blocks of code, comments, semi-colon, operators, indentation (matters?)

Python: variables don't require key words to declare variables
JS: does require key words, let (for variables that will be reassigned) and const (for variables that won't be reassigned ... arrays and objects can still change/mutate)

Both of them don't have the concept of constants in the purest sense.

Neither Python or JS require you to declare the type of each variable, they can infer this behind the scenes. Version of JS (TypeScript where you can). 

Python comments are indicated by #
JS comments are indicated by //

Code pracitces:
- Python, requires you to have correct indentation (otherwise has a fat meltdown). Pretty much the only language to do this ... surely there must be others?? Although thining about it I don't think I've used any
- JS, like a lot of languages (apparently this is C-style) it is pretty common practice to indicate a new line by ending the last with a semi-colon. However, these aren't essential as a lot of compilers will add these for you behind the scenes. Tbh up to you.
- Most people find that having indentation in any language makes it much clearer read and easier for others to read. Therefore you will probably see most people adhering to indentation rules.


## Data structures
strings, arrays, objects/dictionaries, tuples, lists

Neither Python or JS actually have an array property and simply use their list properties to mimic this [] - need to check this ... JS seems to refer to arrays not lists. Could do with looking up if there is any discernable difference between an array and a list.
Objects in Python usually get referred to as instanciated classes in OOP, whereas an object in JS is the same as a dictionary in Python: a data structure that is made up of key-value pairs. JS ... object literals. It kind of uses these in a weird way to fake OOP as well.

String manipulation (pretty much same for both), methods eg slice (python shortcut of [:]), splice (sehr bad), indexing, split, regular expressions?
Regular expressions would be hard to do but maybe do some of the basics
List manipulation (similar), indexing, push, pop, append etc

# Section 2 - Making your programs more advanced

## Logic 
if statements, AND OR NOT gates, binary logic, one if statements, nested if statments, swich statments - ternaries

Python one liners: 'what to do if true' if statement else 'what it do if false'
JS one liners: ternary  if statement ? what to do if true : what to do if false

## Loops 
for - counting and using 'in', while, do

Python: x in data structure; x in range(start, end)
JS: really weird 'of' thingy; declare variable x and increment...very similar to a lot of other languages
JS has for in and for of and they are both really weird

while same for both

do: always executed at least once

## Functions
Difference between procedure and function ... stress this a lot

Include arrow functions? Only arrow functions? Mention Python lamdas as well?

begin with function machine

input -> magic -> output ... love this, can use a lot of the OG Coders article here

Python: use key word def (define) functionName (parameters)
JS: use key word function functionName (parameters){

}

Parameters are the input, known as arguments when they have actual values
Multiple parameters
Default parameters

All functions have a return statement which is a single line for our output. Returns a value

JS can also write as an arrow function - with implicit return statement


## DOM/Event listeners? 
Do we find python equivalent? Or just do we just do programming and ignore this part completely?
Think we defintely need to discuss events and event listeners and handlers since JS is an event based language and the event loop is crucial to Node

# Section 3 - making your programs more advanced, improving efficiency and more specialist tricks

## Data structure methods
map, filter, reduce etc

Python: NO INDEX!!!!! SO BAD!!!! It also returns an object!!!! SO BAD!!! so you have to turn it back into a list... what the actual flip??

JS: MUCH BETTER!! SO GOOD!!

Reduce, Python takes first two values of the list and creates the running total from that
JS makes you define a running total.

In JS these are list methods, in Python they are inbuilt top level functions.

## Times/Dates
Date objects
setTimeout and setInterval
Could mention async programming here possibly

Not sure what Python has for this sort of stuff

# Section 4 - Programming Paradigms
Even though both languages are multi-paradigm, the recent updates to JS mean that JS can now support functional programming much better than Python. OOP in JS has always been very dodgy, barely used at all. However, OOP in Python (normally where people first learn OOP) has always been popular.

Therefore, having both languages under your belt mean that you will have a very solid grounding in the three main programming paradigms (Imperative, Functional and Object-Oriented)

## Functional Programming
mainly JS
Closures, Pure functions, Higher order functions, currying
Recursion needs covering here
Many functional languages don't have any concept of a for loop

There's the [article we wrote about functional programming](https://www.sitepoint.com/make-javascript-functional/) as well

When/why is functional used + comparison to imperative/OOP


Advantages of functional programming:
Pure functions are easier to test
Code is more predictable
Don't get side effects
More modular - can reuse functions
Can run in parallel much easier

## OOP
mainly python

What is OOP?

Create data structures called objects that describe a real-life 'thing' (find a better word), such as pet, car, animal, house, etc. Comprised of attributes and methods. An attribute is a property of the 'thing', e.g hair colour, and a method is a function/procedure that is used to update or access the current attributes.

Inheritance, Encapsulation and Polymorphism

When/why is OOP used + comparison to imperative/functional.

# Section 5 - using JS and Python in the real world

## Async programming
Await and promises

## Becoming a Developer
Using GitHub and deployment, testing, linting, using VS Code, version control, software development methodologies.
Would be good to show how to get a website or web app on Netlify and how to use github pages here

## Using libraries/frameworks
Even though everyone begins by learning the main language in either Python or JS, most developer jobs (web or software) will typically as you to have familiarity with certain language libraries and frameworks. This is because the frameworks and libraries have been designed to make coding much more efficient. 

What is a framework? This would be quite hard to define and find examples of ...

What is a library?

How do they work?

JS: React, Angular, Svelte, jQuery (frameworks ... this would be seen as controversial, React says it's a library) ... not sure if we should even mention jQuery that much. I mean it gets used still, so would need to know of it, but could look to see what are the important libraries peope need for JS these days

Surely this is a god place to introduce JOG.List ... plugs a lot of the gaps in JS, making it even more functional

Comparison.

Python: Django, Flask
Django is a full stack framework, not sure if JS has any
Flask is very similar to Express and can be paired with front end libraries like React

Python also makes use of mathematical libraries numpy and matplotlib, for modelling data, very important for careers in AI or research etc.
This would be a very god section, especially with what you were saying yesterday about how it deals with data so efficiently

## Interacting with the server
JS: using node, JSON data and rest API. Build your first app in node.
Python: using flask.

Should probably avoid databases here though and just point in the direction of further reading
Maybe just get to the point of building a single entity web app similar to the programming app

## Using apis
Processing JSON data
Linking to backend server stuff
