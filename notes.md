- [Day 01- Learning Basic Html](#day-01--learning-basic-html)
  - [What is HTML?](#what-is-html)
  - [Points to remember:](#points-to-remember)
    - [1. Header basics](#1-header-basics)
    - [2. Texts basics](#2-texts-basics)
    - [3. Lists](#3-lists)
- [Day 02- Learning Basic HTML](#day-02--learning-basic-html)
  - [Points to remember:](#points-to-remember-1)
    - [1.Html Quotations](#1html-quotations)
    - [2. HTML Links](#2-html-links)
    - [3. HTML Images](#3-html-images)
    - [4. HTML Tables](#4-html-tables)
- [Day 03- Learning Basic HTML](#day-03--learning-basic-html)
  - [Points to remember:](#points-to-remember-2)
    - [1. HTML Block and Inline Elements](#1-html-block-and-inline-elements)
    - [2. The \<div\> element](#2-the-div-element)
    - [3. The \<span\> element](#3-the-span-element)
- [Day 04- Learning Basic HTML](#day-04--learning-basic-html)
  - [Points to remember:](#points-to-remember-3)
    - [1. Diving deep into the div element](#1-diving-deep-into-the-div-element)
    - [2. HTML class attribute](#2-html-class-attribute)
    - [3. HTML id attribute](#3-html-id-attribute)
    - [4.ID vs Class](#4id-vs-class)
    - [5. HTML iframe](#5-html-iframe)
    - [6. HTML file paths](#6-html-file-paths)
    - [7. Responsive Web Design](#7-responsive-web-design)
    - [8. HTML Semmantic Elements](#8-html-semmantic-elements)
    - [9. HTML Forms](#9-html-forms)
    - [10. HTML Video and Audio](#10-html-video-and-audio)


# Day 01- Learning Basic Html

## What is HTML?
HTML stands for HyperText Markup Language. It is used on the frontend and gives the structure to the webpage which you can style using CSS and make interactive using JavaScript.

## Points to remember:
### 1. Header basics
 1. ‎`<header>` tag is used to define the header section of a webpage or a section.
 2. It usually contains introductory content like the website logo, title, or navigation links.
 3. You can use multiple ‎`<header>` tags on a single page (for the whole page and for individual sections or articles).
 4. The ‎`<header>` tag helps organize the structure of the page and improves accessibility.
 5. It is a semantic element, meaning it gives meaning to the content inside it for browsers and assistive technologies.
 6. The ‎`<header>` tag is different from the ‎`<head>` tag, which is used for metadata and not visible on the page.
 7. Common elements inside a ‎`<header>` are ‎`<h1>`–‎`<h6>`, ‎`<nav>`, logo images, and sometimes search forms.
 8. The ‎`<header>` tag does not add any default styling; you use CSS to style it.

### 2. Texts basics
1. em tag is used to highlight the text.
2. strong tag is used to bold the text.
3. hr tag is used to draw a horizontal line.
4. br tag is used to break the line.
5. html enttity is used to display special characters.
 a. it starts with & and ends with ;
6. <abbr title = Hover text> </abbr> tag is used to display the abbreviation of the word, like a hover text
7. addres tag is used to display the address or location.

### 3. Lists
1. there are 3 types of lists: ordered list, unordered list, and description list.
2.ordered list is used to display the list of items in a sequential order. Syntax: <ol> <li> </li> </ol>
3.unordered list is used to display the list of items in a random order. syntax: <ul> <li> </li> </ul>
4.description list is used to display the list of items with a description. Syntax: <dl> <dt> </dt> <dd> </dd> </dl>
5.list items are displayed using the li tag.

# Day 02- Learning Basic HTML
## Points to remember:
### 1.Html Quotations
1. The HTML <blockquote> element defines a section that is quoted from another source.
2. The HTML <q> element defines a short inline quotation.
3. Quotations are usually displayed with indentation.

### 2. HTML Links
1. The HTML <a> tag defines a hyperlink.
2. The most important attribute of the <a> element is the href attribute, which indicates the link's destination.
3. By default, links will open in the same tab as the user was in before clicking the link.4. To change this, you must specify another target for the <a> tag.
   - The target attribute specifies where to open the linked document.
   - To open the linked document in a new window or tab, use the target="_blank" attribute.
5. The links discussed above are absolute URLS. i.e. the urls of a full web address.
6. If you want to link to a page within your own website, you can use relative URLS.
7. You can also use image as a link using the img tG inside the href tag.
8. You can also directly link to mail using the mailto: tag.
9. You can have a hover text over the link using the title attribute.
10. To bookmark a link, you can use the id attribute, then link to it using the href attribute.

### 3. HTML Images
1. The HTML <img> tag is used to embed an image in an HTML page.
2. The <img> tag has two required attributes:
  - src - Specifies the path to the image
  - alt - Specifies an alternate text for the image
3. You can also add animated stuff like gif using the same methods.
4. You can also add a link to the image using the a tag.
5. To make the image float, you can use the float attribute.
6. You can also add backgorund image to a specific paragraph or even the whole page.

### 4. HTML Tables
1. The HTML table> tag defines an HTML table.
2. Each table row is defined with a tr> tag. Each table header is defined with a th> tag. Each table data/cell is defined with a td> tag.
3. To add a border to the table, use the border attribute in css.
4. To maintain the table layout, add the width attribute to the table> element.
5. To maintain the row layout, add the height attribute to the tr> element.
6. To have a single table header span over multiple columns, use the colspan attribute on the th> element.
7. To have a single table header span over multiple rows, use the rowspan attribute on the th> element.
8. To have a zebra-striped table, use the :nth-child() selector and add a background-color to all even (or odd) table rows.

# Day 03- Learning Basic HTML
## Points to remember:
### 1. HTML Block and Inline Elements
1. HTML elements are either inline or block.
2. Block-level elements always start on a new line and take up the full width available (stretches out to the left and right as far as it can).
3. Inline elements do not start on a new line and only takes up as much width as necessary.

### 2. The &lt;div&gt; element
1. The <div> element is often used as a container for other HTML elements.
2. It defines a block level section in a document.
3. The <div> element has no required attributes, but style, class and id are common.
4. When used together with CSS, the <div> element can be used to style blocks of content:
5. The <div> element is easily styled by using the class or id attribute.
6. Any type of content can be put inside the <div> element!
   
### 3. The &lt;span&gt; element
1. The <span> element is an inline container used to mark up a part of a text, or a part of a document.
2. The <span> element has no required attributes, but style, class and id are common.
3. When used together with CSS, the <span> element can be used to style parts of the text:
4. The <span> element is easily styled by using the class or id attribute.
5. Any type of content can be put inside the <span> element!
6. The <span> element is an inline element, and cannot contain block elements such as <div>.

# Day 04- Learning Basic HTML
## Points to remember:
### 1. Diving deep into the div element
1. To align multiple divs in a row, you can use the float property.
2. To align multiple divs in a column, you can use the flex property.

### 2. HTML class attribute
1. The HTML class attribute is used to specify a class for an HTML element.
2. Multiple HTML elements can share the same class.
3. The class attribute is often used to point to a class name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.
4. Syntax for class attribute:
  - &lt;tagname class="classname"&gt;
  - in css: .classname{styling rules}
  - in js: document.getElementsByClassName("classname")

### 3. HTML id attribute
1. The HTML id attribute is used to specify a unique id for an HTML element.
2. You cannot have more than one element with the same id in an HTML document.
3. The value of the id attribute must be unique within the HTML document.
4. The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.
5. Syntax for id attribute:
   - &lt;tagname id="idname"&gt;
   - in css: #idname{styling rules}
   - in js: document.getElementById("idname")
6. The id name is case sensitive.
7. ID is also used to bookmark a specific section in a webpage.

### 4.ID vs Class
1. The id attribute specifies a unique id for an HTML element.
1. The class attribute specifies one or more class names for an HTML element.
2. The class name can be used by multiple HTML elements, while the id name must only be used by one HTML element within the page.

### 5. HTML iframe
1. The HTML <iframe> tag specifies an inline frame.
2. An inline frame is used to embed another document within the current HTML document.
3. The <iframe> tag was introduced in HTML 4.
4. The ‎"<iframe>" tag was not supported in the first versions of HTML.
5. For example, you can use the <iframe> tag to embed a Google Map or a Youtube video in a web page:

### 6. HTML file paths
1. The path to a file is the location of the file on your computer.
2. There are two ways to specify the path to a file:
   - An absolute URL - points to another web site (URL - Universal Resource Locator)
   - A relative URL - points to a file within a web site.
   - The most common way to specify a path is to use the following syntax:
   - path/filename
   - For example:
     - /html/default.
  
### 7. Responsive Web Design
1. Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones).
2. Set the viewport to make your website look good on all devices:
3. The viewport is the user's visible area of a web page. It varies with the device, and will be smaller on a mobile phone than on a computer screen.
4. Responsive Images:
   - Responsive images are images that scale nicely to fit any browser size.
   - If the CSS width property is set to 100%, the image will be responsive and scale up and down
   - If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size.
   - Using the picture element, you can display different images for different device sizes.
5. Responsive Text Size:
   -To make the texts responsive, set them with a "vw" unit.
   - 1vw = 1% of viewport width.
   - If the viewport is 50cm wide, 1vw is 0.5cm.
   - If the viewport is 500cm wide, 1vw is 5cm.

### 8. HTML Semmantic Elements
1. Semantic elements = elements with a meaning.
2. A semantic element clearly describes its meaning to both the browser and the developer.
3. Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.
4. Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.

### 9. HTML Forms
1. The HTML <form> element is used to create an HTML form for user input:
2. The <form> element can contain one or more of the following form elements:
   - input
   - textarea
   - button
   - select
   - fieldset
   - legend
   - label
   - output
3. The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.
4. The <input> element is the most important form element.
5. The <input> element can be displayed in many ways, depending on the type attribute.
6. Form attributes:
   - action - defines the action to be performed when the form is submitted
   - method - defines the HTTP method for sending data to the action URL
   - target - defines where to display the response that is received after submitting the form
   - autocomplete - defines whether the form should have autocomplete on or off
   - novalidate - defines that the form should not be validated when submitted
   - name attribute - defines the name of a form if ommitted, the value of the input field will not be sent at all
7. Form elements:
   - input - defines an input field where the user can enter data
   - textarea - defines a multiline input field (a text area)
   - button - defines a clickable button
   - label - defines a label for an input element

### 10. HTML Video and Audio
1. HTML5 <video> and <audio> elements make it easy to add video and audio to a web page.
2. Without the controls attribute, the browser will not display controls for the video/audio playback. Meaning you cannot play/pause the video/Audio etc.
3. The <video> and <audio> elements allow you to add media to a web page.
4. The <video> and <audio> elements require a source element to specify the media source.
5. The <source> element can be used to specify alternative video/audio files which the browser may choose from. The browser will use the first recognized format.
6. The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> element.
7. To add autoplay for the video, use the autoplay attribute:


   

