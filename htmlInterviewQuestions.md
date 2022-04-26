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