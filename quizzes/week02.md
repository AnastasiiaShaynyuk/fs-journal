# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
Function is a block of code that can be defined once and then called or invoked multiple times. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID is a set of design principles that help you write better and more maintainable code.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
In this array string 'pineapple' is 2. You just count from 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if else
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i ++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model - it represents the page as a tree of objects that can be manipulated using code. When you load a web page in a browser, the HTML file containing the page's content is accessed first to construct the DOM tree, which is then used to render the page on the screen.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
String, number, boolean, null, undefined, object, function, symbol, bigInt
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is like a variable inside a function that will be used to do some work. When we define a function, we can specify what parameters it needs. An argument is the actual value that we pass to the function when we call it. So, when we call a function, we pass arguments to it that fill in the placeholders created by the parameters.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value is a value that is not an object and has no methods. A reference value is an object and can have methods.
```