# Learn to Code with JavaScript &amp; Python

The ultimate guide to learning to code in the world's two most popular languages!
By JOG

We need to decide about exercises/challenges for the end of each chapter
Also should there be a big project that builds up throughout the book or just exercises to do? I think I prefer exercises rather than a big challenge
I also think it might be a god idea to link to Code Wars challenges that are suitable at various stages

## Intro, programming, pseudocode

##  Python vs Js 
technical, general use, development - for work/jobs

Both a multi-paradigm language - however Python is more suited to imperative and OOP, where as JS (with the ES6 updates) is more suited to imperative and functional (OOP in JS is widely avoided).

They are the two most popular languages in the world (add stats), which is why it's very useful to be familiar with both.

They are both very powerful languages, however they differ in their specialisms.

JavaScript is an event based language which is why it is the main language used for frontend web development. Vanilla JS will only run in the browser and therefore on the client. However, advances in JavaScript, such as nodejs mean that server side processing (backend development) can be written in JavaScript as well. Meaning a whole application can be written in JS.

Whilst Python can be used for web development, it doesn't really specialise in this. Predominantly used in more scientific scenarios such as data science, data analysis and graph modelling. This is due to its powerful mathematical libraries. Python is sometimes used for backend development as well, e.g. Flask.

A lot of people tend to have Python as the language they learn first, and have JavaScript as their second. This is due to it's easy syntax (very much like english). A lot of schools likewise begin with Python. And uni courses also tend to emphasise Python as a first language and JS as second. However, as people progress into careers, Python tends to fade out and JavaScript is what is most predominantly asked for. 

Therefore, learn them both together!

## First program 
Hello World - console.log vs print

## Variables 
variable declaration, data types, blocks of code, comments, semi-colon, operators, indentation (matters?)

Python: variables don't require key words to declare variables
JS: does require key words, let (for variables that will change value) and const (for variables that will remain constants)

Neither Python or JS require you to declare the type of each variable, they can infer this behind the scenes. Version of JS (TypeScript where you can). 

Python comments are indicated by #
JS comments are indicated by //

Code pracitces:
- Python, requires you to have correct indentation (otherwise has a fat meltdown). Pretty much the only language to do this.
- JS, like a lot of languages it is pretty common practice to indicate a new line by ending the last with a semi-colon. However, these aren't essential as a lot of compilers will add these for you behind the scenes. Tbh up to you.
- Most people find that having indentation in any language makes it much clearer read and easier for others to read. Therefore you will probably see most people adhering to indentation rules.


## Data structures
strings, arrays, objects/dictionaries, tuples, lists

Neither Python or JS actually have an array property and simply use their list properties to mimic this []
Objects in Python usually get referred to as instanciated classes in OOP, whereas an object in JS is the same as a dictionary in Python: a data structure that is made up of key-value pairs.

String manipulation (pretty much same for both), methods eg slice (python shortcut of [:]), splice (sehr bad), indexing, split
List manipulation (similar), indexing 

## Logic 
if statements, AND OR NOT gates, binary logic, one if statements - ternaries

Python one liners: 'what to do if true' if statement else 'what it do if false'
JS one liners: ternary  if statement ? what to do if true : what to do if false

## Loops 
for - counting and using 'in', while, do

Python: x in data structure; x in range(start, end)
JS: really weird 'of' thingy; declare variable x and increment...very similar to a lot of other languages

while same for both

do: always executed at least once

## Functions
Include arrow functions? Onle arrow functions? Mention Python lamdas as well?

begin with function machine

input -> magic -> output

Python: use key word def (define) functionName (parameters)
JS: use key word function functionName (parameters){

}

Parameters are the input

All functions have a return statement which is a single line for our output.

JS can also write as an arrow function.


## DOM/Event listeners? 
Do we find python equivalent? Or just do we just do programming and ignore this part completely?

## Data structure methods
map, filter, reduce etc

Python: NO INDEX!!!!! SO BAD!!!! It also returns an object!!!! SO BAD!!! so you have to turn it back into a list...

JS: MUCH BETTER!! SO GOOD!!

Reduce, Python takes first two values of the list and creates the running total from that
JS makes you define a running total.

In JS these are list methods, in Python they are inbuilt functions.

## Functional Programming
mainly JS
Closures, Pure functions, Higher order functions, currying
There's the [article we wrote about functional programming](https://www.sitepoint.com/make-javascript-functional/) as well

## OOP
mainly python

## Times/Dates
Date objects
setTimeout and setInterval

## Async programming
Await and promises

## Becoming a Developer
Using GitHub and deployment, testing, linting, using VS Code

## Other Ideas
Using apis
Processing JSON data
Using Node JS/Flask (server stuff)
