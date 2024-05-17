# Difference between Window and Document Object

### *Window object*:
The `window` object in JavaScript is a global object that represents the browser window or tab in which a web page is displayed. It acts as the global scope for all JavaScript code running in the browser, meaning that any global variables or functions are properties of the `window` object. It provides numerous properties and methods to control the browser environment, such as manipulating the size and position of the window, handling navigation and location changes, and managing browser history.

### *Document objects*:
The `document` object in JavaScript is a property of the `window` object and serves as the entry point to the web page's content, representing the Document Object Model (DOM). It provides a structured representation of the HTML or XML document loaded in the browser, allowing developers to access and manipulate its elements and structure programmatically. It also provides metadata about the document, like its title (`title`) and the full URL of the page (`URL`). Overall, the `document` object is crucial for dynamic and interactive web applications, enabling the modification and interaction with the document's content and structure.

### *Difference*

|Feature            |    Window Object                                  |    Document Object                       |
|-------------------|---------------------------------------------------|------------------------------------------|
| Scope               | Represents the entire browser window or tab; global object. | Represents the HTML or XML content within the browser window; property of `window`. |
| Hierarchy           | Top-level object.                            | Child of the `window` object (`window.document`). |
| Functionality       | Controls the browser window (open, resize, navigate). | Interacts with and manipulates the DOM (select, create, modify elements). |
| Event Handling      | Handles browser window events (load, resize, scroll). | Handles page content events (click, keypress, DOMContentLoaded). |
| Properties          | Includes properties like `innerHeight`, `location`, `history`. | Includes properties like `body`, `title`, `URL`. |
| Global Context      | Acts as the global scope; global variables and functions are properties of `window`. | Provides access to and manipulation of the document content. |
| Navigation          | Manages navigation through `window.location`. | Provides structure and metadata of the document. |
| Element Creation    | Not used for creating or manipulating page elements. | Used for creating and manipulating elements (`createElement`, `appendChild`). |
| Focus               | Manages the overall browser environment.     | Manages the content and structure of the web page. |

