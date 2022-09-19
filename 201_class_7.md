# Code 201 - Class 7 reading

## [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

### Questions

**1. Explain why we need domain modeling.**

- "A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams." - CF Repo

## [HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

**1. Why should tables not be used for page layout?**

- Reduces accessibility for people using screen readers.
- Results in a more complex markup structure that's harder to understand.
- Tables are not automatically responsive on different platforms.

**2. List ad describe 3 different semantic elements used in an HTML table.**

- `<tr>` -> table row elements, define where rows start and end and hold table data elements
- `<td>` -> table data elements, make table cells and hold data.
- `<th>` -> table header elements, "cells that go at the start of a row or column and define the type of data that row or column contains " (MDN docs)

## [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

**1. What is a constructor and what are some advantages of using it?**

- A constructor is a function for creating new objects. It allows you to create multiple new objects with different data from the same basic structure.

**2. How does the term this differ when used in an object literal vs in a constructor?**

- When `this` is used in an object literal, it's not as useful because it's just used for that one object definition. When `this` is used in a constructor, it's as useful because it allows each attribute to be given a diffrent value for each new instantion of an object from the constructor function.

## [Object prototypes using constructors](https://ui.dev/beginners-guide-to-javascript-prototype)

**1. Explain prototypes and inheritance via an analogy from your previous work experience.**

- In my previous jobs as a microbiologist (and in the Navy for that matter), we had standard operating procedures (SOPs) for different basic tasks in the lab. Sometimes these tasks would require us to record important information. Instead of making a new form or way of recording this information, we would print out a form from the SOP. This is sort of like class inheritance.

Sometimes the SOP would tell us to prepare something 'according to manufacturer's instructions' which in essence could mean 'just follow the instructions on the box'. This would save us from printing out the instructions again, similar to how using prototypes saves computer memory instead of writing the same method instructions in different memory locations.
