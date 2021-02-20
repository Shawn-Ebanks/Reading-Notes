# Read 05 notes

## Duckett: HTML & CSS, Chapter 10: Introducing CSS

CSS allows the developer to add many different styles to the structure of the HTML content.

To understand CSS, think about how each element is within a box. CSS will be able to modify the style and properties of each block.

CSS rules contain two parts, a `selector` and a `declaration`.

Selectors indicate which element the rule  declaration applies to.

Declarations indicate how the elements in the selector should be styled. Declarations are inside curly braces.

Properties are what you want to change of the element, like color, font, width , height and border.

Value is the actual specification you have selected like 10px , red, border.

External CSS must be linked using the `<link>` tag.
Eg. `<link href="css/styles.css" type="text/css" rel="stylesheet" />`

Internal CSS within HTML is used with the `<Style>` element along with the type attribute.
Example below:

`<style type="text/css">` 

`body` `{`

`font-family: arial;`

`background-color: red;}`

`h1` `{`
`color: blue;}`

`</style>`


## Types of selectors :

- `*` {}- applies to all elements in a document
- `.name` {} - class selector applies to specified class
- `#name` {}- ID selector applies to unique ID
- `li>a` {} - child selector - applies to any `<a>` elements that are children of an `<li>` element (but not other `<a>` elements in the page.
- `p a` {} - Descendant selector - Targets any `<a>` elements that sit inside a `<p>` element, even if there are other elements nested between them
- `h1+p` {} - Adjacent sibling selector - Targets the first `<p>` element after any `<h1>` element (but not other `<p>` elements
- `h1~p` {} - General sibling selector - if you had two `<p>` elements that are siblings of an `<h1>` element, this rule would apply to both

Last Rule : If selector is duplicated the last one will be applied.
Specificity: If one selector is more specific than the others, the more specific rule will take precedence over more general ones
Inheritance: Font-family and color properties on the `<body>` element will be inherited by the child elements.

# Duckett: HTML & CSS, Chapter 11: Color

There are three ways to specify colors in CSS: RGB values, hex codes, and color names.

It is important to ensure the contrast between text and background color is appropriate.

CSS comments :Anything between the `/_` symbols and the `_/` symbols will not be interpreted by the browser. Eg. - `/_` color name `_/`

CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).

Margin - property that controls the spacing between the boxes
Padding - controls the space between the box and contents within the box.

- [Return to main page](https://shawn-ebanks.github.io/Reading-Notes/)
