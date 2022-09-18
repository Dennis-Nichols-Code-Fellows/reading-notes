# Code 201 - Class 06 notes

## Object Basics

- [Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

### Topic 1 importance

Objects let us write more efficient code and improve reusability.

### Topic 1 Questions

**1. How would you describe an object to a non-technical friend you grew up with?**

- You could describe objects as similar to characters in a video game. They have can have attributes like name and size but also have abilities (methods) that accomplish certain tasks.

**2. What are some advantages to creating object literals?**

- It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name. (MDN docs)

**3. How do objects differ from arrays?**

- In an object the key:value mapping is from strings to values whereas in an array it is from numbers(an index) to values.

**4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**

If an object property name is defined at runtime then you can't use dot notation to access the value, but you can pass the name as a variable inside brackets (MDN docs).

**5.Evaluate the code below. What does the term this refer to and what is the advantage to using this?**

The this keyword refers to the current object the code is being written inside.
If you create more than one object (of the same class), this enables you to use the same method definition for every object you create.

## Intro to the DOM

-[Intro to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

### Topic 2 importance

The DOM is key to understanding how JS interacts with a web page.

### Topic 2 Questions

**1. What is the DOM?**

- The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.(MDN docs)

**2. Briefly describe the relationship between the DOM and JavaScript.**

- You can use Javascript to manipulate the elements/nodes of the DOM with scripts.

## Things I want to learn more about

- How to use constructors in JavaScript.
