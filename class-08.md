
# Layout


## Key Concepts in Positioning Elements:
 - Block-level elements start on a new line
   - Examples include: `<h1> <p> <ul> <li>`
   - To separate boxes, you can use borders, margins, padding, and background colors.
   - You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too).
   - A box may be nested inside several other block-level elements. The containing element is always the direct parent of that element.
 - Inline elements flow in between surrounding text
   - Examples include: `<img> <b> <i>`


## Controll ing the Position of Element:
 - positioning schemes :allow you to control the layout of a page
   - Normal flow
   - Relative Positioning
   - Absolute positioning

  - box offset: properties to tell the browser how far from the top or bottom and left or right it should be placed.
    - Fixed Positioning
      - The heading has been placed in the center of the page and 25% from the top of the screen. (The rest appears in normal flow.)
    - Floating Elements
      - The heading has been floated to the left, allowing the paragraphs of text to flow around it.

**When you move any element from normal flow, boxes can overlap. The z-index property allows you to control which box appears on top.**


# Functions, Methods, and Objects
*Functions:* let you group a series of statements together to perform a specific task.
  - function declaration creates a function that you can call later in your code.
  - A function with no name is called an **anonymous function**.
  - the function is stored in avariable called **area**.

## Summary 
- **`<div>` elements are often used as containing elements to group together sections of a page.**

- **Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.**

- **The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)**

- **Pages can be fixed width or liquid (stretchy) layouts.**

- **Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).**

- **Grids help create professional and flexible designs.**

- **CSS Frameworks provide rules for common tasks.**

- **You can include multiple CSS files in one page.**