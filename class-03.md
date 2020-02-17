# Lists
### There are lots of occasions when we need to use lists. HTML provides us with three different types:
    - 1. Ordered lists
      - use numbers
      - `<ol>`
      - `<li>`
    - 2. Unordered lists
      - use bullets
      - `<ul>`
      - `<li>`
    - 3. Definition lists
      - used to define terminology
      - `<dl>` consists of a series of terms and their definitions.
      - `<dt>` contain the term being defined (the definition term).
      - `<dd>` used to contain the definition.

    **Lists can be nested inside one another.**

# Boxes 
### Box Dimensions
   - 1. Width
     - Limiting width 
       - win-width 
       - max-width
   - 2. Height
     - Limiting height
       - min-height
       - max-height

**Overflowing Content**
  - overflow: property tells the browser what to do if the content contained within a box is larger than the box itself.
    - It can have one of two values:
     - 1. hidden
       - hides any extra content that does not fit in the box.
     - 2. scroll
       - property adds a scrollbar to the box so that users can scroll to see the missing content.
**Every box has three available properties that can be adjusted to control its appearance:**
  - Border
  - Margin
    - sit outside the edge of the border
  - Padding
    - space between the border of a box and any content contained within it.

**display:** property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page.
  - inline 
    - block-level element to act like an inline element.
  - block
    - inline element to act like a block-level element.
  - inline-block
    - block-level element to flow like an inline element, while retaining other features of a block-level element.
  - none
    - This hides an element from the page.

**visibility**
  - property allows you to hide boxes from users but It leaves a space where the element would have been.

**border-image**
  - 1. The URL of the image
  - 2. Where to slice the image
  - 3. What to do with the straight edges
    - stretch stretches the image
    - repeat repeats the image
    - round like repeat but if the tiles do not fit exactly

**box-shadow**
  - Horizontal offset
    - Negative values position the shadow to the left of the box.
 - Vertical offset
    - Negative values position the shadow to the top of the box.
 - Blur distance
    - If omitted, the shadow is a solid line like a border.
 - Spread of shadow
    - If used, a positive value will cause the shadow to expand in all directions, and a negative value will make it contract.
**border-radius**
 - border-top-right-radius
 - border-bottom-right-radius
 - border-bottom-left-radius
 - border-top-left-radius

 *You can use CSS to control the dimensions of a box.*
 *It is possible to hide elements using the display and visibility properties.*
 *Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.*


 # Decisions and Loops
**SWITCH STATEMENTS**

*type coercion* : JavaScript can convert data types behind the scenes to complete an operation.
*unary operator* : returns a result with just one operand

### Loops 
   - for
   - while
   - do while

**if ... else statements allow you to run one set of code if a condition is true, and another if it is false.**