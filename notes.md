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
1. The HTML <table> tag defines an HTML table.
2. Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.
3. To add a border to the table, use the border attribute in css.
4. To maintain the table layout, add the width attribute to the <table> element.
5. To maintain the row layout, add the height attribute to the <tr> element.
6. 
