
HTML Essentials
=====================

HTML is the language that powers the web. With HTML you can create your web pages/website. This course provides an in-depth look at the essentials: the syntax of HTML and best practices for writing and editing your code. Will learn HTML, Document structure, block and inline-level tags, floating images, controlling white space, phrase and font markup, list, links, and tables.

Topics include
=====================
1. [Introducing HTML](#section-1-introducing-html)
    - 1a. [Introducing XHTML](#section-1a-introducing-xhtml)
    - 1b. [Introducing HTML5](#section-1b-introducing-html5)

**`HTML (HyperText Markup Language) - Markup language, essential page structure/content, readable and convey structure to the user, text layout model, page mark-up, text, tags, data, details for pages, images, tables, anchor links, forms`**
    - HTML is an acronym that stands for `HyperText Markup Language` which is used for creating `web pages and web applications
    - HTML is not a programming language; it is a markup language that defines the structure of your content ie. document

> **Syntax & Example**:
```html
<html>

  <head>
    <title>02.01.intro.html</title>
  </head>

  <body>
    <h1>This is Intro HTML file</h1>
    This line will displayed on browser / web page.
  </body>

</html>
```
### 2.6 Building blocks of HTML (Tag Attribute Element)
An HTML document consist of its basic building blocks:

| Name / Item     | Description                             |
| ----------------|-----------------------------------------|
| Tags            | An HTML tag surrounds the content and applies meaning to it. It is written between `< and > brackets.`    |
| Attribute       | An attribute in HTML provides extra information about the element, and it is applied within the start tag. An HTML attribute contains two fields: `name & value / key & value`  |
| Elements        | An HTML element is an individual component of an HTML file. In an HTML file, everything `written within tags` is termed as HTML elements |

> **Syntax & Example**:
```html
<tag attribute="attribute value"> content: whole together is an element </tag >   
```

> **Syntax & Example**:
```html
<h1 align="right">Heading 1 aligned to right </h1>
```

### 2.7 Tag
- HTML tags are like keywords which defines that how web browser will format and display the content `<p>, <h1>, <table>, <strong>`
- HTML is a markup language and makes use of various tags to format the content 
- Tags are enclosed within angle braces `<Tag>`
- Except few tags, most of the tags have their corresponding closing tags. ```<Tag> </Tag> , <Tag />, <p> </p>, <h1> </h1>, <br />, <hr /> <link />```
- When a web browser reads an HTML document, browser reads it from top to bottom and left to right
- HTML tags are used to create HTML documents and render their properties

> **Syntax & Example**:
```html
<tag> content </tag >  
```

> **Syntax & Example**:
```html
<h1>HTML Tags: Various tags used to develope web page.</h1>
<h3>Heading: Welcome Welcome to HTML</h3>
<p>Paragraph: This is my first HTML page</p>
<hr /> Horizontal Rules 
<br /> Line Break
<strong> Bold Strong Text </strong>
<li> list item bulletted list </li>
```

### 2.8 Attribute
- HTML attributes are special words that `provide additional information about the elements` or attributes are the modifier of the HTML element
- Each element or tag can have attributes, which defines the `characteristics/behavior` of that element
- Attributes should always be applied with start-tag
- All attributes are made up of two parts − a name and a value, Attributes usually come in name/value pairs like `name="value"`
- Attribute names and attribute values are case-insensitive

> **Syntax & Example**:
```html
<tag attribute="attribute value"> content </tag >   
```

> **Syntax & Example**:
```html
<h1 class="headings" id="heading1"> Heading 1 </h1 >  
<p align="right"> Paragraphic text </p>
<hr size="20" width="500"/> Horizontal Rules 
<br /> Line Break
<strong style="color:red;"> Bold Strong Text </strong>
<center><h2 title="Title attribute: Heading 2">Heading 2: Hover Me</h2></center>
```

### 2.9 Element
- An HTML file is made of elements
- Elements are responsible for creating web pages and define content in that webpage
- An element in HTML usually consist of a `start tag <tagName>, close tag </tagName>` and content inserted between them 

> **Syntax & Example**:
```html
<tag attribute="attribute value"> content: whole together is an element </tag >
```

> **Syntax & Example**:
```html
<h1 align="right">Heading 1 aligned to right </h1>
```

### 2.10. HTML Syntax     
- HTML Syntax is very simple easy to learn
- HTML Contents/Documents ie files are nothing but a simple text files only with `.htm` or `.html` extention
- HTML page consists of `DTD & TAGS` for different visual aspects
- HTML uses `TAGS` to markup and identify page content
- `<start_tag> Some content here </end_tag>` **Example**: `<p> p is paragraph tag used to create paragraphics text.</p>`
- An HTML Element = `<tag attribute="attribute value"> content: whole together is an element </tag > `  
- We can create contents with `nested elements` like `<tag1><tag2>Some Content </tag2></tag1>` **Example**: `<p><strong>I am bold paragraphic text</strong></p>`

#### **Types of Attributes**
1. **Informative Attribute** - gives extra information about an element. **Example**: lang="en", class="header", id="container1"
2. **Functional Attribute** - very important who perform some activities. **Example**: href="index.html", src="script.js" 

### 2.11. State (Evolution of HTML)
The Web is changing very fast and so HTML
#### History of HTML

| Year          | History       |
| ------------- |---------------|
| 1990          | Specification Drafted in Mid 90s by Tim Berners Lee                                                   |
| 1991          | Tim Berners Lee published document called "HTML Tags"                                                 |
| 1995          | HTML 2.0 ('standard' HTML)                                                                                                        |
| 1997          | HTML 3.2 (proprietary browser companies developed many features)                          |
| 1999          | HTML 4.0 W3C Web standards support                                                                                        |
| 2000          | XHTML 1.0 (HTML move towards XML)-Extensible Markup Language                                  |
| 2001          | 2009 - XHTML 2.0                                                                                                                          |
| 2004          | WHATWG formed (Web HyperText Application Technology Working Group, they continued with development of HTML 5.0) |
| 2007          | 2008 - W3C adopts WHATWG's HTML5 Web Application 1.0 specification and drafts |
| 2009          | XHTML 2.0 drops/stops                                                                                                                 |
| 2014          | W3C Recommendation: HTML5                                                                                                         |

#### The Current State of HTML
**There are two specifications of HTML: (*Not much changes with syntax*)**
1. W3C (World Wide Web Consortium)
2. WHATWG (Web Hypertext Application Technology Working Group)
