# The Past, Present, and Future of Local Storage for Web Applications

## Persistent local storage:
  - is one of the areas where native client applications have held an advantage over web applications.

- **What we really want is**
  - a lot of storage space
  - on the client
  - that persists beyond a page refresh
  - and isn’t transmitted to the server

# A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5
  -  DHTML Behaviors
  - userData
    - *allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.*
  - Google launched **Gears**, an open source browser plugin aimed at providing additional capabilities in browsers.
    - provides an *API to an embedded SQL database* based on *SQLite*.

# INTRODUCING HTML5 STORAGE
  -  a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons.
   - HTML5 Storage is based on named key/value pairs. 

# TRACKING CHANGES TO THE HTML5 STORAGE AREA
  - `setItem()`, `removeItem()`, or `clear()` is called and actually changes something 
  - The *storage event* is not cancelable.

- **persistence.js, an “asynchronous JavaScript ORM” built on top of Web SQL Database and Gears**