# Code 201 - Class 1 Reading Notes

## Getting Started

- [How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

- [Website design and process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

- [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

### Topic 1 Importance

An introduction to the structure of the modern web is important to understanding how the code we write interacts with and is mediated by infrastructure, protocols, and conventions. The initial readings on website design and JS syntax give us a taster of the decisions to be made and the tools available to implement these decisions once we start building websites.

### Topic 1 questions

1. **Compose a short poem describing how HTTP sends data between computers.**

    >Hey client, I just met you, and this is crazy  
    But here's my packets, so ping me, maybe  
    It's hard to look right at you, baby  
    But I’m a server, HTTP, maybe  
    Hey client, I just met you, and this is crazy  
    But here's my packets, so ping me, maybe  
    And all the other clients try to chase me  
    But here's my number, 200 OK, maybe.  
    -- *By Carly Rae and Tim Berners-Lee...probably, 1989*

2. **Describe how HTML, CSS, and JS files are “parsed” in the browser**

    When the client (browser) receives an HTML file from the browser it begins to read it and may encounter `link` elements that reference external CSS files and `script` elements that reference external JS files. Next the browser sends back a request to the server for these CSS and JS files - when it receives them, it reads these as well. Next the browser builds the structure of the website (DOM) from the HTML file, builds a similar structure of CSS styles from the CSS stylesheet (so the JS script can access them) and compiles/executes the JS script. Finally, as the CSS styles are applied to the html structure and the JS script runs, the website is 'painted' to the screen.
    -- *Adapted from the MDN webdocs*

3. **How can you find images to add to a Website?**

    You can use *Google Images* to search for appropriate images, but you need to be sure to adjust the settings of the search so that you are only accessing images under *creative commons licenses* and not copyright-protected materials.

4. **How do you create a *String* vs a *Number* in JavaScript?**

    When, for example, you create a variable in JS, you distinguish a string from a number by using quotation marks.

    Strings are represented between quotation marks:

        ```js
        const shakespeare = 'roses are red';
        ```
    Numbers are simply created by typing them as normal, without quotation marks:

        ```js
        const speedLimit = 70;
        ```
5. **What is a *Variable* and why are they important in JavaScript?**
    Variables are 'containers that store values'. -*MDN web docs*

    Varibales are important in JavaScript because they allow are code to be reusable, flexible, and more readable.

## Introduction to HTML

- [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

- [HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

- [Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

### Topic 2 Importance

HTML is the language in which we write the basic structure (or skeleton) of websites. This structure is the very first thing we have to build and thus it makes sense to start here when learning about web design.

### Topic 2 questions

1. **What is an HTML attribute?**
    
    HTML attributes are settings that we can use to modfy the effect of an HTML element. They are usually located within the opening tag of the element, with the exception of self-closing tags. Sometimes attributes can be optionally set, sometimes they have to be present for the element to work properly. As an example, within an anchor element, we set the href (hypertext reference) attribute to tell the hyperlink where to direct the user once it is clicked.

2. **Describe the Anatomy of an HTMl element.**

    - Opening tag -> Tells the browser where the element begins and includes any attributes.
    - Content -> The text that the HTML element is 'marking up'. E.g. this would be the text of a heading within an `<h1>` element.
    - Closing tag -> Tells the browser where the element ends.

3. **What is the Difference between `<article>` and `<section>` element tags?**

    An `<article>` element is higher in the semantic hierarchy than `<section>` elements. An `<article>` element can contain multiple `<section>` elements. Articles are meant to be capable of being used independently from the webpage. As the MDN docs example goes, an `<article>` might be a blog post on a page that contains multiple blog posts. Each of these blog posts might have multiple sections which you wouldn't necessarily distribute independently.

4. **What Elements does a “typical” website include?**

    - Header -> `<header>`
    - Nav bar -> `<nav>`
    - Sidebar -> `<aside>`
    - Main content -> `<main>`
    - Footer -> `<footer>`

5. **How does metadata influence Search Engine Optimization?**

    - The language you specify allows the page to be appropriately indexed
    - Key words used in the description can make the page be indexed more highly for the right searches.

6. **How is the `<meta>` HTML tag used when specifying metadata?**

    - In some cases such as specifying the page character set, there is a special attribute for the function.
    - In many other cases, you first set a `name` attribute to specify what type of metadata you are encoding and then use the `content` attribute to actually write the metadata.

## Miscellaneous

- [How to start to design a website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

1. **What is the first step to designing a website?**

    - You need to define what your goals are for the website.

2. **What is the most important question to answer when designining a website?**

    -What do I want to accomplish?

- [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

1. **Why should your use an `<h1>` element over a `<span>` element to display a top level heading?**

    - Using a semantic tag like `<h1>` improves search engine optimization and improves the function of screen readers which are used by the visually-impaired. It is also just easier than styling the text yourself using a span element.

2. **What are the benefits of using semantic tags in our HTML?**

    - They improve search engine optimization and the function of screen readers which are used by the visually-impaired.
    - They make our code more readable and using them as developers can help us think more about what content we want and how to structure it on the page.

- [What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

1. **Describe 2 things that require JavaScript in the browser?**

    - Responding to user interaction.
    - Storing data which we get from users in variables.

2. **How can you add JavaScript to an HTML document?**

    - We can write JavaScript inside of `<script>` elements which themselves are within the HTML document **OR** we can use the `src` attribute of the `<script>` element to link to an external JS script file.

## Things I want to know more about

- [Supercharging our website](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics#supercharging_our_example_website)
