# Links
**Writing Links**
 - `<a herf=""> Links are created </a>`

### Relative Link Type:
  - Same Folder
    - To link to a file in the same folder, just use the file name.
  - Child Folder
    - use the name of the child folder, followed by a forward slash, then the file name.
  - Grandchild Folder
    - Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash then the file name.
  - Parent Folder
    - Use ../ to indicate the folder above the current one, then follow it with the file name.
  - GrandParent Folder
    - Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name.

**Email Links**
  - `<a href="mailto:jon@example org">Email Jon</a>`

**Opening Links in a New Window**
  - `<a href="http://www.ex.com" target="_blank"></a>`

**Linking to a Specific Part of the Same Page**
  - `<a href="#ex">ex</a>`

*If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.*

# layout

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

# 6 Reasons for Pair Programming

## pair programming :
  - is the practice of two developers sharing a single workstation to interactively tackle a coding task together.

## How does pair programming work?
  - 1. The Driver: is the programmer who is typing and the only one whose hands are on the keyboard.
  - 2. The Navigator: uses their words to guide the Driver but does not provide any direct input to the computer.

## Why pair program? 
  - 1. Greater efficiency
  - 2. Engaged collaboration
  - 3. Learning from fellow students
  - 4. Social skills
  - 5. Job interview readiness


### Pair programming touches on all four skills:
  - 1. developers explain out loud what the code should do
  - 2. listen to others’ guidance
  - 3. read code that others have written
  - 4. write code themselves