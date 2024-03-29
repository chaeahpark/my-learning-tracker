# 5th July 2019
## Things covered
1. Read Eloquent Javascript (Javascript and the browser)
2. Built a book list with a [Traversy Media tutorial](https://www.youtube.com/watch?v=JaMCxVWtW58)
3. Created My Leaning Tracker repo. It was inspired from [the article by Syk Houdeib](https://www.freecodecamp.org/news/how-i-switched-careers-and-got-a-developer-job-in-10-months-a-true-story-b8895e855a8b/)

## Things need to touch again
1. There are several syntax which were new to me. I will cover them tomorrow.
- createTextNode()
- insertBefore()
- getItem()
- setItem()
- splice()
- JSON.stringify()

2. Go through the code of the book list project and try to tweak and improve it.

3. [Architecting Web Apps](https://www.youtube.com/watch?v=Vg60lf92EkM)
___

# 7th July 2019
Q) : Question
<br> N) : Note

## Things covered
1. Reviewing the codes for the Book List project
- [static method in Class](https://www.youtube.com/watch?v=8gWvJx-NP-w&t=342s)
<br> Q) Why is it used and when do we use it?
- JSON
<br> N) I studied this part in Eloquent JS. But I need to master why, how, and what of this.

## Things need to touch again
1. Storage & localStorage: This is my first time to see the two syntax. They will be covered in Eloquent Javascript which is on p326.
2. Question: How a developer build a web app from scratch.
___

# 8th July 2019
## Things covered
1. The Document Object Model(DOM) through Eloquent JS
- The difference between getElementByTagName (live) and querySelector (x live).
2. Review the code of the Book List project.
- [Element.classList](https://www.youtube.com/watch?v=xd_Nip09pzo):
<br> Element.classList.add() / Element.classList.remove()/Element.classList.remove()   
<br>
N) I can use it in order to control CSS depending on input from users.
3. [Syntax parse, Lexical Environment, and Execution context](https://hackernoon.com/javascript-execution-context-and-lexical-environment-explained-528351703922)

___
# 9th July 2019
## Things covered
1. Handling Events through Eloquent JS
- [web worker](https://www.youtube.com/watch?v=EiPytIxrZtU)
- [Debouncing](https://www.youtube.com/watch?v=QvJx9nXWmKc) & Throttiling
2. Array.from() : it creates a new array instance from an array-like or iterable objects.

3. The global environment and global object:
- When JS is run, execution context is created.
- Then global object (window) and 'this' are created.
  <br> Q1) What is _'this'_?
  <br> Q2) What is _'window'_?
  <br> Q3) Are they same?
  <br> Q4) Is _"window"_ different than _'Window'_?
  <br> Q5) What is _'Window'_?

  <br> Answers : ![testing window and this](/img/201900709_globalObject.png)
4. Kicked off **"Weather App"** project.
- fetch API

## Things need to touch again
1. the concept of closure

___

# 10th July 2019
## Things covered
1. Working with <canvas>
2. closures :
- "when an inner function has access to members of the outer function even when executing outside the scope of the outer function." by [Paul Upendo](https://scotch.io/tutorials/understanding-javascript-closures-a-practical-approach)
- IIFE (immediately invoked function)
3. Weather project:
- face with 505 error
- what is CORS?
4. Execution context: creation and hoisting

## Things to touch again
1. [scope, environments and closures](http://speakingjs.com/es5/ch16.html)
2. [CORS](https://www.html5rocks.com/en/tutorials/cors/#toc-cross-domain-from-chrome-extensions)
___

# 11th July 2019
## Things covered
1. interact with forms using JS
2. [closure, scope, hoisting, global execution, execution context](https://www.youtube.com/watch?v=Nt-qa_LlUH0)
* A great tool: https://tylermcginnis.com/javascript-visualizer/
* Article: https://blog.bitsrc.io/understanding-scope-and-scope-chain-in-javascript-f6637978cf53

___
# 13th July 2019
## Things covered
1. [Node JS](https://www.youtube.com/watch?v=TlB_eWDSMt4) & NPM

___
# 14th July 2019
## Things covered
1. Node JS

## Things to touch again
1. Node - EventEmitter
___
# 16th July 2019
## Things covered
1. Forced directed graph (from Eloquent JS book)
2. [Understanding ECMA script 6](https://leanpub.com/understandinges6/read/?fbclid=IwAR0VOEwAYqzzMQAb1aJSiGM27eknlRB6fHcCZPlJ1UIXp30Ppc8Z5IEHXOo#leanpub-auto-about-this-book)
3. 'undefined'
4. execution context, execution stack
5. Meditation App project

(html)
* data-: https://www.w3schools.com/tags/att_data-.asp
<br><br> example:
<br>![html data attribute and interact with JS](/img/20190716_data-attribute.png)
* loop: https://www.w3schools.com/tags/att_loop.asp

(CSS)
* pointer-events:
<br>https://www.youtube.com/watch?v=3zkvVwOV3oQ
* transitions: https://www.w3schools.com/css/css3_transitions.asp
* transform
* :nth-child():
<br>https://www.w3schools.com/cssref/sel_nth-child.asp

## Things to touch again
1. review the meditation app

## A thing to start from tomorrow
1. Go through [Understanding ECMAScript 6](https://bit.ly/2XYS4VZ)

___
# 17th July 2019
## Things covered
1. review the code of the meditation app built yesterday.
(HTML & CSS)
* it is hard to get what pointer-events do and how it can be used.
* transition:
<br> https://www.w3schools.com/css/tryit.asp?filename=trycss3_transition1
<br> https://www.w3schools.com/css/css3_transitions.asp
* :nth-child()
* stroke-dasharray (in svg):
<br>
<br>

(JS)
* getTotalLength():
<br>https://developer.mozilla.org/en-US/docs/Web/API/SVGPathElement/getTotalLength
* ontimeupdate (DOM Event):
<br>https://www.w3schools.com/jsref/event_ontimeupdate.asp

## Things to touch again
1. pointer-events

___
# 18th July 2019
## Things covered
1. Review Eloquent JS Chapter 1
- operators: they are special FUNCTIONS
- Unary operators: operators that take one value.
- type coersion
- Boolean: null, undefined, " " and 0 are regarded as false.
- setting default values:
<br><br> ![](/img/20190718-defaultData.png)
- strict equality(===) and strict inequality(!==)

___
# 19th July 2019
## Things covered
1. Understanding JS engine (V8)

## Things to touch again
1. what are parser, compiler and runtime?

___
# 23rd July 2019
## Things covered
1. Working for the shopping cart project.
Those are the things that I get to know further
In CSS,
- position: sticky (for nav bar)
- grid template columns: auto fit and

<br><br>In JS
- working with local json file when using "fetch" syntax. There was an ERROR showing the message below on the console.
<br> app.js:20 Fetch API cannot load file URL scheme must be "http" or "https" for CORS request.

When it comes to using fetch, it requires to have server where the data is. In order to solve the problem temporarily, I installed a live server plugin on my text editor.

2. Optimizing my text editor.
It is bit messy to work with my text editor. I regard to change my text editor into another one.
