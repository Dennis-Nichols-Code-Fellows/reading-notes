# Class 5 - Design web pages with CSS

## [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

**CSS** stands for Cascading Style Sheets - it's the special sauce that takes basic HTML websites and transforms them into sleekly formatted, modern pages.

CSS can be used for very basic document text styling — for example, for changing the color and size of headings and links. It can be used to create a layout — for example, turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation.

### CSS syntax

CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

For example, you can apply one style to h1 tags, another to h2, another to paragraphs, and so on.

Here is an example of a CSS rule:

    p {
        color: blue;
        font-size: 5px;
    }

In this example, the rule starts with the *selector* - the HTML element we are trying to style - in this case all paragraphs.

It continues with a set of curly braces, and within those a set of declarations in the form of property and value pairs.

This example rule would set all paragraph text to be blue and 5px in size.

### CSS Specifications

The standards for the CSS language are set by the CSS Working Group within the W3C organization. This group develops new features to suit functionality desired by users.

## [How to add CSS](https://www.w3schools.com/css/css_howto.asp)

### External CSS

By using a separate file from your HTML site called a **stylesheet** you can change the look of your site without jumbling up your html code.

For this to work, the stylesheet must be given the .css extension and there must be a link to it from within your html document. Like so:

    <link rel='stylesheet' href='mystyle.css'>

### Internal CSS

The stylesheet may instead be embedded within the html `<head>` section if you only want to style that particular page:

    <head>
    <style>
        body {
                background-color: linen;
                }

        h1 {
                color: maroon;
                margin-left: 40px;
                }
    </style>
    </head>

### Inline CSS

Inline CSS can be used within an html tag to give a unique style to one particular element.

### Cascading order

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default.

## [CSS color](https://www.w3schools.com/cssref/pr_text_color.asp)

The `color` property sets the color of text.
It can do this in various ways:

- with a word designation such as *blue*
- with a 3 or 6 digit hexadecimal code -> #ffffff or #fff
- with rgb values like so: `color: rgb(12,12,230);`

Note rgb can also be given an alpha (transparency) value which is some decimal between 0 and 1 inclusive -> rgba(30,30,200,0.5)
