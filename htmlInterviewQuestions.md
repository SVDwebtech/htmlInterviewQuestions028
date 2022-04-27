# HTML Interview Questions

## What is HTML?
* HTML is an acronym;
* HTML stands for Hypertext Markup Language;
* Text that has a link within it is called hypertext.  Whenever you click on a link which brings you to a new web page, you have clicked on hypertext.  Hypertext is a way to link two or more web pages (HTML documents) with each other on the World Wide Web;
* Markup language is used for developing web pages and applications by structuring and displaying content on the web browser;
* Markup language applies layout and formatting conventions to a text document which makes the text more interactive and dynamic.  It includes animations, audio, images and text, amoung many other things;
* A web page is a document which is commonly written in HTML and translated by a web browser.  A web page can be identified by entering a URL (Uniform Resource Locator);
* An HTML document is made of many different HTML tags, each of which contains different content.  The HTML tags format the content for proper display on web pages;
* HTML pages are saved by adding the .html extention after the name of the document.

## Is an HTML tag and element the same thing?  What are they?
* Tags are pieces of HTML code used to define the structure of an HTML page;
* Content is placed in between HTML tags in order to properly format it;
* There are single HTML tags that do not need a closing tag;
* Examples are:
    ```html
        <!-- image tag -->
        <img> 
        <!-- line break tag -->
        <br> /* - tag */
    ```
* HTML elements are defined by a starting tag, may contain some content and a closing tag;  
* For example:
    ```html
        <!-- an example of an html element -->
        <h1>Heading 1</h> 

        <!-- by itself: a starting tag -->
        <h1>

        <!-- by itself: a closing tag -->
        </h1>
    ```
* When a web browser reads an HTML document, the browser reads it from top to bottom and left to right.  HTML tags are used to create HTML documents and render their properties;
* There are more than 100 tags in HTML5, with each one serving a unique purpose, such as positioning text or supporting audio;
* In their most basic form, most web pages will need around four tags to get started.  These are:
    ```html
        <html> 
        <head>
        <title>
        <body>
    ```

## What are attributes in HTML?
* Attributes are special properties or characteristics.  It is used within an element to modify its behaviour.  It is special words used inside the opening tag and provides additional information about the element.  For example, attributes can be used to specify the dimensions or positioning values of an image;
* Attributes are defined directly after the tag name, inside the angular brackets.  Attributes appear in opening tags.  It can never appear in closin tags.  For example, you can define an attribute for the 
  ```html
    <input> 
   ```
    tag, such as text field, checkbox, radio button, or many more ways.  Attributes usually come in name/value pairs like: name = "value";
* An attribute either modifies the default functionality of an element type.  Or provides functionality to certain element types unable to function correctly without them.  It changes the behaviour and provides metadata;
* We can modify the value of attributes by using JavaScript.  Below is the unput element whose attribute will be modified from text to password, JS code to modify the attribute value:  
    ```html
        <input type = "text" id = "inputField">
    ```
    ```js
        document.getElementById("inputField").attr("type","password");
    ```  
* You may see attributes without the equals sign or a value.  That is a shorthand for providing the empty string in HTML, or the attribute's name in XML. 
  
## Describe and explain HTML layout structure, and name the most important HTML5 structure elements.
* HTML layout structure specifies the way in which a web page is arranged.
* Every website has a specific layout and structure, and displays content in a specific manner. 
* However, there are a few things which may be considered as standard practice on how to structure a web page.
* HTML5 structure elements are used for HTML layout structure.
* The most important HTML5 structure elements are:
  
    ```html
        <header></header>: 
    ```
* The header html element defines the head section of the document or more simply put, the top of the page. Then it is no surprise that a header section always sticks at the top of the document. It is used to define a header for a document or a section.

    ```html
        <nav></nav>: 
    ```
* The nav html element represents a section of a page which provides navigation links to other sections within the current document or to other documents. It is used to define a container for navigation links.  Examples of navigation sections are: menus, tables of contents, and indexes.

    ```html
        <main></main>: 
    ```
* The main html element defines the main section in the document and contains the main content of the document.  It defines the primary section in the document related to the central content of a document.

    ```html
        <section></section>: 
    ```  
* The section html element defines a generic standalone section in the document, such as a header, footer or in other sections of the document. It is used to define the structure of the document.  This particular section of the document doesn’t have a more specific semantic element to represent it.  And a section should always have a heading.

    ```html
        <article></article>: 
    ``` 
* The article html element represents an independent or self-contained part of the content of a document.  It is intended to be independently distributable or reusable. Examples are: a forum post, a magazine or newspaper article, or an interactive widget.

    ```html
        <aside></aside>: 
    ```
* The aside html element defines some content aside from the content it is placed in, and it contains secondary content.  It represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.

    ```html
        <footer></footer> 
    ```
* The footer html element defines the footer section of the document. It contains information such as copyright or the author’s information, or navigational elements pertaining to the contents of the parent element, or links to related documents.  A footer section always sticks at the bottom of the document.
