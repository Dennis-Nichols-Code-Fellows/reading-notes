# Class 4 - Structure Web Pages with HTML

## [Wireframe and Design](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)

### Intro to wireframing
**Wireframing** is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product.
When designing for the screen you need to know where all the information is going to go in plain black and white diagrams before building anything with code.
Without the distractions of colors, typeface choices or text, wireframing lets you plan the layout and interaction of your interface. *A commonly-used argument for wireframing is that if a user doesn’t know where to go on a plain hand-drawn diagram of your site page, then it is irrelevant what colors or fancy text eventually get used.*

#### Tips for beginners

1. Start wireframing with paper and pencil - fast and easy to change.
2. Once the high level ideas are set on paper, move to software to keep track of details.
3. The extensiveness of the design process should depend on the level of the task.

#### Tools to consider

-[UXPin](https://www.uxpin.com/)
-[Invision](https://www.invisionapp.com/)

### 6 steps to make a wireframe

1. Do your research
2. Prepare your research for quick reference
3. Make sure your user flow is mapped out (have a sound understanding of the information architecture)
4. Draft, don't draw. Sketch, don't illustrate.
*A good, thick marker pen is a handy tool for this stage of wireframing. Why? Because it prevents you from drowning yourself in detail. You’ll focus on delineating the functional blocks that form the skeleton of your design.*
5. Add some detail and get testing.
6. Start turning your wireframes into prototypes.

### 3 principles of good wireframe design

1. Clarity
2. Confidence
3. Simplicity is key

## [Mozilla HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

**HTML** (HyperText Markup Language) is the code that is used to structure a web page and its content. For example, content could be structured within a set of paragraphs, a list of bulleted points, or using images and data tables.
HTML is a *markup* language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on.

### Anatomy of an HTML element

![HTML element schema](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

Within the opening tag, there can be attributes that modify the element as shown below:

![attributes](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-attribute-small.png)

Attributes contain extra information about the element that you don't want to appear in the actual content. Here, class is the attribute name and editor-note is the attribute value.

Attributes should always have:

* A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
* The attribute name followed by an equal sign.
* The attribute value wrapped by opening and closing quotation marks.

### Nesting elements

You can put elements inside other elements too — this is called nesting. 
It is important that the elements have their tags in the right order to be properly nested. The code below demonstrates the correct order.
`<p>My cat is <strong>very</strong> grumpy.</p>`

### Self-closing / empty elements

Some elements have no content and are called empty elements. `<img>` elements are a common example. This contains attributes, but there is no closing </img> tag and no inner content. This is because an image element doesn't wrap content to affect it. Its purpose is to embed an image in the HTML page in the place it appears.



