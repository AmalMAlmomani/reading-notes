# Structure

## HTML pages are text documents.
**structure:**
```is very important in helping readers to understand the messages you are trying to convey and to navigate around the document.```

#### Elements : `are usually made up of two tags: an opening tag and a closing tag.(The closing tag has an extra forward slash in it.)`

**HTML Uses Elements to Describe the Structure of Pages**

**Attributes: provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of *two parts*: a name and a value, separated by an equals sign.**

**Anything written between the <title> tags will appear in the title bar (or tabs) at the top of the browser window, highlighted in orange here.**
**Anything written between the <body> tags will appear in the main browser window, highlighted in blue here.**


# Extra Markup
## Comments in HTML: `<!-- comment goes here -->`
**ID attribute:**
  - It is used to uniquely identify that element from other elements on the page.
  - As you will see when you come to look at CSS in the next section, giving an element a unique identity allows you to style it differently than any other instance of the same element on the page.
  - is known as a `global attribute` because it can be used on any element.
 
**Class Attribute:**
  - The class attribute on any element can share the same value.
  
**Block elements:**
  - Some elements will always appear to start on a new line in the browser window.
  - These are known as `block level` elements.
  - Examples of block elements are `<h1>, <p>, <ul>, and <li>`.
  
 **Inline elements:**
   - Some elements will always appear to continue on the same line as their neighbouring elements.
   - Examples of inline elements are `<a>, <b>, <em>, and <img>`.
   
 **Grouping text & Elements in a block:**
   - `<div>`:allows you to group a set of elements together in one block-level box.
   - `<span>`:
      - 1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
      - 2. Contain a number of inline elements
      - 3. The most common reason why people use `<span>` elements is so that they can control the appearance of the content of these elements using CSS.
  - `<iframe>`: 
    - is to embed a Google Map into a page.
    - There are a few attributes that you will need to know to use it:
      - src: The src attribute specifies the URL of the page to show in the frame.
      - height: The height attribute specifies the height of the iframe in pixels.
      - width: The width attribute specifies the width of the iframe in pixels.
      - scrolling: allow the user to move around the frame to see more content, not be supported in HTML5. In HTML 4 and XHTML
      - seamless: In HTML5,can be applied to an iframe where scrollbars are not desired.
      
  **Information About Your Pages:**
   - `<meta>` element is an empty element so it does not have a closing tag. It uses attributes to carry the information.
      - description: This contains a description of the page. This description is commonly used by search engines to understand what the page is about and should be a maximum of 155 characters.
      - pragma: This prevents the browser from caching the page.
      - Escape characters are used to include special characters in your pages such as `<, >, and ©`.
      
  # HTML5 Layout
  
  ## Headers & Footers:
   - The main header or footer that appears at the top or bottom of every page on the site.
   - A header or footer for an individual `<article>` or `<section>` within the page.
   - The `<header>` element used to contain the site name and the main navigation.
   - The `<footer>` element contains copyright information, along with links to the privacy policy and terms and conditions. 
 
 ## Navigation:
   - `<nav>`:
     - is used to contain the major navigational blocks on the site such as the primary site navigation.
     - use for the links that appear at the bottom of every page (links to things like privacy policy, terms and conditions and accessibility information).
     
 ## Articles:
  - `<article>`:
    - element acts as a container for any section of a page that could stand alone and potentially be syndicated.
    
 ## Asides
  - `<aside>`:
    - When the `<aside>` element is used inside an `<article>` element, it should contain information that is related to the article but not essential to its overall meaning.
    - When the `<aside>` element is used outside of an `<article>` element, it acts as a container for content that is related to the entire page.
      - it might contain links to other sections of the site, a list of recent posts, a search box, or recent tweets by the author.
   
 ## Sections
  - `<section>`:groups related content together, and typically each section would have its own heading.
  - if you have a page with a long article, the `<section>` element can be used to split the article up into separate sections.
  
## Figures
 - `<figure>`: 
   - Examples of usage include:
     - Images
     - Videos
     - Graphs
     - Diagrams
     - Code samples
     - Text that supports the main body of an article
   - should also contain a `<figcaption>` element which provides a text decription for the content of the `<figure>` element.
 
 ## Sectioning elements
  - `<div>`
  
## Linking Around Block-Level Elements
  - HTML5 allows web page authors to place an `<a>` element around a block level element that contains child elements. 
  - This allows you to turn an entire block into a link.
  
  
# Process & Design 

 - Target Audience: individuals
   - What is the age range of your target audience?
   - Will your site appeal to more women or men? What is the mix?
   - Which country do your visitors live in?
   - Do they live in urban or rural areas?
   - What is the average income of visitors?
   - What level of education do they have?
   - What is their marital or family status?
   - What is their occupation?
   - How many hours do they work per week?
   - How often do they use the web?
   - What kind of device do they use to access the web?
   
 - Target Audience: Companies
   - What is the size of the company or relevant department?
   - What is the position of people in the company who visit your site?
   - Will visitors be using the site for themselves or for someone else?
   - How large is the budget they control?
   
 ## Why People Visit YOUR Website?
  - Key Motivations
  - Specific Goals

  ## What Information Your Visitors Need ?
   - You know who is coming to your site and why they are coming, so now you need to work out what information they need in order to achieve their goals quickly and effectively.
   
 ## WireFrames:
   - is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.
   
# Java script
  ## How javascript makes web pages more interactive: 
   - ACCESS CONTENT: You can use JavaScript to select any element, attribute, or text from an HTML page.
   - MODIFY CONTENT: You can use JavaScript to add elements, attributes, and text to the page, or remove them.
   - PROGRAM RULES: You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page.
   - REACT TO EVENTS: You can specify that a script should run when a specific event has occurred.
   
 ### A script: is a series of instructions that a computer can follow to achieve a goal.
 **Vocabulary: The words that computers understand.**
 **Syntax: How you put those words together to create instructions computers can follow.**
 **Each time the script runs, it might only use a subset of all the instructions.**
 **To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).**
 **Programmers make these models using data. That is not as strange or as scary as it sounds because the data is all the computer needs in order to follow the instructions you give it to carry out its tasks.**
 
 **Methods:** represent things people need to do with objects. 
   - They canretrieve or update the values of an object's properties.
**Computers use data to create models of things in the real world.**
**Using the document object, you can access and change what content users see on the page and respond to how they interact with it.**

*Properties:* **describe characteristics of the current web page (such as the t itle of the page).**
*Methods:* **perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or adding new content).**
*Events:* **You can respond to events, such as a user clicking or tapping on an element.**

 ### How a browser see a web page?
    1: RECEIVE A PAGE AS HTML CODE
    2: CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY 
    3: USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN