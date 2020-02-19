# Images
 - Images should...
   - Be relevant
   - Convey information
   - Convey the right mood
   - Be instantly recognisable
   - Fit the color palette
***If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.***
**Adding Images**
  - `<img stc="URL" alt="text description of the image which describes the image if you cannot see it." title="provide additional information about the image" height="" width="" /> empty element`
  - Where to Place Images in Your Code 
    - 1: before a paragraph
    - 2: inside the start of a paragraph
    - 3: in the middle of a paragraph 
  - Three Rules for Creating Images
    - 1. Save images in the right format
    - 2. Save images at the right size
    - 3. Use the correct resolution
  **Use GIF or PNG format when saving images with few colors or large areas of the same color.**
  **Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations**
  - Transparency
    - web involves selecting one of two formats:
      - Transparent GIF
      - PNG
## HTML 5: Figure and Figure Caption
  - `<figure> contain images and their caption so that the two are associated.</figure>`
  - `<figcaption> to add a caption to an image </figcaption>`

*Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.*

# Color
  - Color
    - rgb values
    - hex codes : preceded by a pound or hash #
    - color names
## Foreground Color
  - background-color
  - Opacity
**Color not only brings your site to life, but also helps convey the mood and evokes reactions.**
**CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.**
  - CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.


# Text
## Typeface Terminology 
  - Serif
   - fonts have extra details on the ends of the main strokes of the letters.
  - Sans-Serif
   - Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.
  - Monospace
   - Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.)

**Specifying Typefaces**
  - font-family
  - font-size
    - pixels
    - percentages
    - ems : is equivalent to the width of a letter m.
**text-transform:**
  - uppercase
  - lowercase
  - capitalize

**text-decoration:**
  - none
  - underline
  - overline
  - line-through
  - blink
**Leading**
   - line-height
 - letter-spacing, word-spacing
**Alignment**
  - text-align 
    - left
    - right
    - center
    - justify
  - vertical-align
**text-indent**
  - allows you to indent the first line of text within an element.
**text-shadow**
  - property has become commonly used despite lacking support in all browsers

 - :first-letter, :first-line
 - :link
   - allows you to set styles for links that have not yet been visited.
 - :visited 
   - allows you to set styles for links that have been clicked on.
- :hover
  - applied when a user hovers over an element with a pointing device such as a mouse.
- :active
  - applied when an element is being activated by a user;
- :focus
  - applied when an element has focus

**Attribute Selectors**
  - Exist ence 
    - [] - Matches a specific attribute (whatever its value)
  - Equality
    - [=] - Matches a specific attribute with a specific value
  - Space
    - [~=] - Matches a specific attribute whose value appears in a spaceseparated list of words
  - Prefix
    - [^=] -  Matches a specific attribute whose value begins with a specific string
  - SubString
    - [*=] - Matches a specific attribute whose value contains a specific substring 
  - Suffix
    - [$=] - Matches a specific attribute whose value ends with a specific string