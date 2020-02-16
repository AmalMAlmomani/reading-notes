# Text 

### Headings
   - HTML has six "levels" of headings
### Paragraphs
   - `<p>...</p>`
### Bold & Italic
   - `<b> characters appear bold </b>`
   - `<i> characters appear italic </i>`
### Superscript
   - `<sup> suffixes of dates or mathematical concepts like raising a number to a power </sup>`
### Subscript
   
   - `<sub> commonly used with foot notes or chemical formulas</sub>`
### White Space
   - white space collapsing: two or more spaces next to each other

### Line Breaks 
   - `<br />`
### Horizontal Rules
   - `<hr />`

## Semantic Markup
   - some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages
### Strong 
   - `<strong> `  
### Emphasis
   - `<em>` element indicates emphasis that subtly changes the meaning of a sentence.

### Quotations
   - `<blockquote>`used for longer quotes that take up an entire paragraph.
   - `<q>`
### Abbreviations 
   - `<abbr>`
### Citations 
   - `<cite>` referencing a piece of work such as a book, film or research paper
### Definitions
   - `<dfn>`
### Auth or Details
   - `<address>` to contain contact details for the author of the page.
### Changes to Content
   - `<ins>` underlined
   - `<del>` usually has a line through it
   - `<s>` usually be displayed with a line through the center.

 **HTML elements are used to describe the structure of the page.**

 # Introducing CSS
**Selectors: indicate which element the rule applies to.**
**Declarations indicate how the elements referred to in the selector should be styled.**
**Properties indicate the aspects of the element you want to change.**
**Values specify the settings you want to use for the chosen properties.**

### 1.Using External CSS
   - `<link>`
     - `href`
     - `type`
     - `rel`
### 2.Using Internal CSS
   - `<style>`
   - CSS Selectors
    - Universal Selector `* {}`
      - Targets all elements on the page
    - Type Selector `h1, h2, h3 {}`
      - Targets the <h1>, <h2> and <h3> elements
    - Class Selector `.note {}`
      - Targets any element whose class attribute has a value of note
    - ID Selector `#introduction {}`
      - Targets the element whose id attribute has a value of introduction
    - Child Selector `li>a {}`
      - Targets any `<a>` elements that are children of an `<li>` element (but not other `<a>` elements in the page)
    - Descendant Selector `p a {}`
      - Targets any `<a>` elements that sit inside a `<p>` element, even if there are other elements nested between them
    - Adjacent Sibling Selector `h1+p {}`
      - Targets the first `<p>` element after any `<h1>` element (but not other `<p>` elements)
    - General Sibling Selector `h1~p {}`
      - If you had two `<p>` elements that are siblings of an `<h1>`If you had two <p> elements that



# Basic JavaScript Instructions

**surrounded by curly braces these are known as** *code blocks*
**A script will have to temporarily store the bits of information it needs to do its job. It can store this data in** *variables*
 
### DATA TYPES
   - NUMERIC DATA TYPE `0.75`
   - STRING DATA TYPE `'Hi , 123'` 
   - BOOLEAN DATA TYPE `true`

***An array is a special type of variable. It doesn't just store one value; it stores a list of values.***

### operators
   - ASSIGNMENT OPERATORS
   - ARITHMETIC OPERATORS
   - STRING OPERATORS
    - Programmers call the process of joining together two or more strings to create one new string *concatenation*
   - LOGICAL OPERATORS
   - COMPARISON OPERATORS

# Decisions and Loops
**There are two components to a decision:
  - 1. An expression is evaluated, which returns a value
  - 2. Aconditional statement says what to do in a given situation

- **IF Statements**
- **IF..Else Statements**

  