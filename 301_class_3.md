# Code 301 - Class 3

## [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does `.map()` return?
A new array where each element has been modified by some function.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
Put the output of the loop function into a new variable then put that variable in curly braces within the render function.

3. Each list item needs a uniqe...**key**.

4. What is the purpose of a key in React?
The purpose of a key is to let React keep track of which items have been modified or deleted.

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. What is the spread operator?
"A useful and quick syntax for adding items to arrays, combining arrays together, and spreading an array out into a function's arguments." - Coding at Dawn

2. List 4 things the spread operator can do?
The article more lists tasks where it is useful:
- Copying an array
- Concating an array
- Using an array as arguments
- Adding to state in React

3. Give an example of using the spread operator to combine two arrays.

```js
const arr1 = [1, 2, 3];
const arr2 = [4,5,6];

const result = [...arr1, ...arr2];
```

4. Give an example of using the spread operator to add a new item to an array.

```js
new_item = 1;
const arr3 = [...arr1, new_item];
```

5. Give an example of using the spread operator to combine two objects into one.

```js
const obj1 = {[1, 2, 3]};
const obj2 = {[4,5,6]};

const result = {...obj1, ...obj2};
```

## [How to Pass functions between components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?
They write a new function in the parent component.

2. In your own words, what does the increment function do?
Takes the target name of the button that was clicked and loops through the people array to find the matching name then increments the associated count.

3. How can you pass a method from a parent component into a child component?
Pass it as a prop.

4. How does the child component invoke a method that was passed to it from a parent component?
Invoke it with `this.props`.
