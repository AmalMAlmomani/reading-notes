# Object Literals

**WHAT IS AN OBJECT?**
  - group together a set of variables and functions to create a model of a something you would recognize from the real world.

- If a *variable* is part of an object, it is called a **property**.
- If a *function* is part of an object, it is called a **method**.
- In an *object*, that name is called a **key**.
- you access the properties or method of an object using *dot notation*. 
- you can also access properties using *square brackets*. 

  
# Document Object Model
 
- **The Document Object Model (DOM):** specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

- **Application Programming Interface (API):** User interfaces let humans interact with programs.
- **The dom tree:** is a model of a web page.

##  Each node is an object with methods and properties.

- Method that find elements in the DOM tree are called *DOM queries*.
- **When you need to work with an element more than once, you should use a variable to store the result of this query.**
- DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.
 ### METHODS THAT RETURN A SINGLE ELEMENT NODE:
    - getElementByld('id')
    - querySelector('css selector')

### METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):
    - getElementsByClassName('class')
    - getElementsByTagName('tagName')
    - querySelectorAll ('css selector')

**NODELISTS:** DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT
  - **live Nodelist:** when your script updates the page, the Nodelist is updated at the same time.
  - **static Nodelist:** when your script updates the page, the NodeList is not updated to reflect the changes made by the script.

**There are two ways to select an element from a Nodelist:**
  - The item() method and array syntax.
  - Both require the index number of the element you want.

  page 215
  