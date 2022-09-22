# Code 201 - Class 9 reading

## [HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

- [how to structure a web form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

### Questions

**1. Why are forms so important in web development?**

- Web forms are one of the main ways for users to interact with a website.

**2. When designing a form, what are some key things to keep in mind when it comes to user experience?**

- The bigger the form, the more risk that users will give up before finishing using it.
- Keep forms simple and only ask for the input you really need. (MDN docs)

**3. List 5 form elements and explain their importance.**

- `<form>` -> the container element for web forms, can set attributes to decide where to send data.
- `<label>` -> defines the caption a user will actually see for a form input.
- `<input>` -> used to create interactive controls for the form.
- `<textarea>` -> multi-line text editing control for when you want to let users input a large amount of free-form text.
- `<button>` -> lets the user indicate that they are done with the form and want to submit.

## [Learn JS - Intro to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

**1. How would you describe events to a non-technical friend?**

- Events are anything that happens in the web browser / site programming.

**2. When using the addEventListener() method, what 2 arguments will you need to provide?**

- We have to indicate the type of event we are interested in and the function that should run when the event occurs.

**3. Describe the event object. Why is the target within the event object useful?**

- The event object is the collection of properties and methods that can be referred to when an event occurs. The target property refers to the html element that was interacted with to create the event.

**4. What is the difference between event bubbling and event capturing?**

- Bubbling refers to how events are handled in order of most immediate target element, to parent element, to further parent and so on. Capturing is the inverse - when an event occurs, the browser checks if the outermost parent element has an event handler for this event and runs it, then moves inwards and so on.