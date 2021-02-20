# Read: 06a - Dynamic web pages with JavaScript

JavaScript file extenstion is `.js`

Its not good practice to run JavasScript internal `HTML`.Its always best to have the`.js` file external.

To link a JavaScript file use the **HTML** `<script>`element. and the `src` attribute will tell where is the file located.

`Internet Explorer` sometimes prevents JavaScript from running. Best to use other browsers.

JavaScript runs where it is found in the `HTML`.

When the browser comes across a `<script>` element its stops to load the script and checks to see of it needs to do anything else.

placement of the `<Script>` element is important to the structure content.

# JavaScript Intructions

Each step the computer executes is called a **statement**

- `Statements` should end with a `:`.
- Each one starts on a new line.

## Code blocks

Code blocks start and end with curly braces.

_Single Line comments_ start with `//` but does not close with it.

_Multi line Comments_ should be used for later reference. `/*comment*/`

## Variables

The programmer declares the variabale. (`var`)

Variables store temporary information for the script.

Result of variables are said to be _calculated_ or _computed_.

`var` is keyword but _variable name_ is what ever the programmer calls it.

If the `variable name` has more than one word it should be written in **camelCase**

After a variable is assigned next is the `value`. which can be `numeric date type` , `string data` and `boolean data`. or

- `numeric date type` numbers without `,`in them. decimals are normal.
- `string data` - 'Welcome' must be in single line and have matching quotes
- `boolean data` - "True" or "False"

Six rules for naming variables:

1. must not start with numbers. only `$` `_` or letters.
1. must not use `-` or `.`
1. must not use keywords and reserved words.
1. All variables are case sensitive.
1. Variable name must be relevant to the data being stored
1. use camelCase style for variable with more than one word.

[Return to main page](https://shawn-ebanks.github.io/Reading-Notes/)
