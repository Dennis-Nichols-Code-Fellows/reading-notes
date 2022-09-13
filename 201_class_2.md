# Code 201 - Class 2 Reading Notes

## More introduction to HTML

- [HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- [HTMTL Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

### Topic 1 Importance

We are used to reading structured text in newspapers, magazines, textbooks, etc. By mimicing this structure in a website, we make the reading experience better for the user.

### Topic 1 Questions

**1. Why is it important to use semantic elements in our HTML?**

- Using semantic elements and structuring pages with headings, articles, sections, etc helps users quickly scan a page and find their desired content.
- Using semantic elements like headers helps search engines optimize their indexing of the page.
- These elements are helpful to people who use screen readers.

**2. How many levels of headings are there in HTML?**

- There are 6 levels of headings.

**3. What are some uses for the `<sup>` and `<sub>` elements?**

- These elements (superscript and subscript respectively) are useful for writing out chemical formulas and mathematical notation.

**4. When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?**

- You must use the title attribute to provide the full expansion of the term.

## [How CSS is structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

### Topic 2 Importance

It is important to understand how to efficiently structure your CSS and to understand the hierarchy of CSS declarations.

### Topic 2 Questions

**1. What are the ways we can apply CSS to our HTML?**

- We can use CSS inline with the style attribute within an HTML tag.
- We can apply CSS at the level of the page by using the style element within the head element.
- We can use an external CSS stylesheet and link it to the webpage using the `<link>` element.

**2. Why should we avoid using inline styles?**

- They can make our code more complicated to read.
- It takes more work to style things at the inline level.

**3. Questions on CSS selectors?**

- *What is representing the selector?* In this case, h2 is the selector; this will select all h2 elements on the page (that aren't selected by a more specific CSS selector).

- *Which components are the CSS declarations?* In this case, the declarations are the pairing of a property and a value. In the example, `color: black` is a declaration.

- *Which components are considered properties?* In this case, the properties are `color` and `padding`.

## Learn JS

### Topic 3 Importance

### JS Basics questions

**1. What data type is a sequence of text enclosed in single quotes?**

- This is a string.

**2. List 4 types of JavaScript operators.**

- Arithmetic, Assignment, Boolean, Logical

**3.Describe a real world Problem you could solve with a Function.**

-You could make a function that greets the user whenever they visit your site.

### Conditionals questions

**1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.**

- A condition; true

**2. What is the use of an else if?**

- Adds a subsequent condition to evaluate if the first `if` statement evaluates to false.

**3. List 3 different types of comparison operators.**

- Deeply/ strictly equal (===), greater than (>), less than (<)

**4. What is the difference between the logical operator && and ||?**

- The AND operator will only evaluate to true if both components statements evaluate to true.
- The OR operator will evaluate to true if either of the components statements evaluate to true.

## Things I want to know more about

-Different types of operators.
