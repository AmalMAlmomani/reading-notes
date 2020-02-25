# Forms 
- The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

- **There are several types of form controls:**
  - ADDING TEXT:
    - Text input (single-line)
    - Password input
    - Text area (multi-line)
  - Making Choices:
    - Radio buttons
    - Checkboxes
    - Drop-down boxes
  - Submitting Forms:
    - Submit buttons
    - Image buttons
      - ` <input type="image"> `
  - Uploading Files:
    - File upload

- **Form Structure:**
  - `<form>`
    - action
    - method

- **Labelling Form Controls**
  - *can be used in two ways.It can:*
    - 1. Wrap around both the text description and the form input (as shown on the first line of the example to your right).
    - 2. Be kept separate from the form control and use the for attribute to indicate which form control it is a label for (as shown with the radio buttons).
    - **for : attribute states which form control the label belongs to.**

- **Grouping Form Elements**
  - `<fieldset>`
    - You can group related form controls together inside the `<fieldset>` element. This is particularly helpful for longer forms.
  - `<legend>`
    - can come directly after the opening `<fieldset>` tag and contains a caption which helps identify the purpose of that group of form  controls.

- You have probably seen forms on the web that give users messages if the form control has not been filled in correctly; this is known as form **validation**.

- HTML 5: Date Input
   - `<input>`
     - `type="date,emal,url,search,"`
     - *placeholder:* whose value is text that will be shown in the text box until the user clicks in that area.

# Lists, Tables & Forms 

- **Bullet point styles:**
  - allows you to control the shape or style of a bullet point (also known as a *marker*).
    - It can be used on rules that pply to the `<ol>, <ul>, and <li>` elements.

- **Images for Bullets:**
  - list-style-image

- **Positionning the marker:**
  - list-style-position

- **List Shorthand:**
  - list-style

- **Border on empty cells:**
  - empty-cells

- **Gaps Between Cells:**
  - border-spacing, border-collapse
   
# Chapter 6: Events (pp.243-292)

- there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as **event handling**.
   - 1. Select t he element node(s) you want the script to respond to.
   - 2. Indicate which event on the selected node(s) will trigger the response. 
   - 3. State the code you want to run when the event occurs. 

   - **The mouse events:** are fired when the mouse is moved and also when its buttons are clicked.
   - **The keyboard events:** are fired when a user interacts with the keyboard (they fire on any kind of device with a keyboard).

- Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).

- Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
- When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
- You can use event delegation to monitor for events that happen on all of the children of an element.
- The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.