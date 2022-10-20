# Code 301 - Class 03

## [React Forms](https://reactjs.org/docs/forms.html)

1. What is a ‘Controlled Component’?
It's when we take an element that might usually maintain its own state and put it inside a react component and have that component control the element's state.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
We should update it along the way because it gives us more flexibility in responding to the input such as with handler functions.

3. How do we target what the user is entering if we have an event handler on an input field?
We use event.target.value.

## [Ternary Operator](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

1. Why would we use a ternary operator?
This makes it possible to shorten a simple if else block to one line.

2. Rewrite the following statement using a ternary statement:

  ```js
  if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

```js
x===y ? console.log(true) : console.log(false );
```
