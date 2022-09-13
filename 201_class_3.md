# Code 201 - Class 03 notes

## Learn HTML

- [Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

### Topic 1 importance

Learning about ordered and unordered lists is important because they let us add another layer of structure to our site. This contributes to making it easier for a user to find information they are looking for.

### Topic 1 Questions

**1. When should you use an unordered list in your HTML document?**

When you are 'grouping a collection of items that do not have a numerical ordering'. (MDN docs)

**2.How do you change the bullet style of unordered list items?**

You can change the style using the `type` attribute.

**3.When should you use an ordered list vs an unorder list in your HTML document?**

When it is important for your list to have a numerical order, you should use an ordered list.

**4.Describe two ways you can change the numbers on list items provided by an ordered list?**

- You can use the `type` attribute to set the numbering system.
- You can use the `start` attribute to set the numerical start of the list.

## Learn CSS

-[The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

### Topic 2 importance

The box model is key to understanding how to position elements on the page.

### Topic 2 Questions

**1.Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**

- Imagine that the 'box' in the box model is a house. 
- The margin character is the person who wrote the ordinance on how close this house is allowed to be to other houses.
- The padding character is the very strict interior designer who decides how close furniture is allowed to be to the walls of the house.

**2.List and describe the four parts of an HTML elements box as referred to by the box model.**
  
- Content box
- Padding box
- Border box
- Margin box

## Learn JS

- [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- [operators, expresssions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

### Topic 3 importance

### Topic 3 Questions

**1.What data types can you store inside of an Array?**

- "strings, numbers, objects, and even other arrays" - MDN docs

**2.Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**

- Yes this is valid.
- You can access items in the array with brackets, like so: `people[1][2];`

**3.List five shorthand operators for assignment in javascript and describe what they do.**

- `+=` -> addition assignment -> returns original variable plus assigned value.
- `-=` -> subtraction assignment -> returns original variable minus assigned value.
- `*=` -> multiplication assignment -> returns original variable times assigned value.
- `/=` -> division assignment -> returns original variable divided by assigned value.
- `**=` -> exponentiation assignment -> returns original variable raised to the assigned value.

**4.Read the code below and evaluate the last expression and explain what the result would be and why.**

- This evaluates to '10dog'
- The part of the expression in the parenthese is evaluated first adding a truthy value to a false value and retturning the value 10. The next part of the expression type converts 10 to a string and concatenates it with 'dog'.

**5.Describe a real world example of when a conditional statement should be used in a JavaScript program.**

- A conditional statement could be used in a while loop on a user input to make sure the program doesn't proceed until the condition is true.

**6.Give an example of when a Loop is useful in JavaScript.**

- A loop would be useful for iterating through an array and performing an operation on each element.
