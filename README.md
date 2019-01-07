# html_prac
These are basically some important notes from several sources about html/css. Just a brush up because I basically forgot about this stuff. 

**Brushing up on HTML, CSS and Javascript**
THE AIM: Brushing up on HTML and CSS then working on a project via Javascript


|TABLE OF CONTENTS|
| ------------- |
|1 HTML Basics|
|2 HTML HEAD|
|3 HTML Text Fundamentals|
|4 Hyperlinks|
|5 Advanced Text Formatting|
|6 Document and Website Structure|
|7 Debugging HTML|
|8 HTML Tables|
|9 HTML Forms|

Important Sources to Consider
- [ ] [MDN/Learn](https://developer.mozilla.org/en-US/docs/Learn)
- [ ] [ilovecoding] (https://ilovecoding.org/courses/htmlcss)
- [ ] [codeacademy] (https://www.codecademy.com/)

## 1 HTML Basics

#### Nesting
<element> My cat is <element1>very</element1> grumpy. </element>

#### Block-level elements AND Inline elements
Block line elements form a visible block on the page. Appears on a new line before or after
Inline elements are those that are contained within block-level elements. Surround on small parts of the document contents
[ REFER TO CODE ]

#### Empty Elements
Some elements follow the open then close tags, but some only need one tag
such as <img> tag

#### Attributes
Elements can have attributes (extra information)
for example 
href="the website" is an example of an attribute
title = "this pops up when hovered over"
class = "css thing"
Anchor < a> will make a piece of text it wraps into a hyperlink.

## 2 HTML Head
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML
Basically contains metadata of the html page (such as the character encoding and title)

## 3 HTML Text Fundamentals
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals
THis is a summary of paragraphs and headings
p and h1,h2,h3...
Basically these are subtitles

#### Semantics
Important to use the correct elements to maintain meaning (heading is the thing that means top level of your page) and by default the browser gives it a larger font). CONSISTENCY is key

#### Lists
The tag ul, and li is used for list. We can have
Ordered lists, nested lists...

#### Emphasis and Importance
em tag is used to stress certain words by putting ITALICS
strong is used to bold text

HTML5 now uses b, i and u tags. Which sort of have a semantic meaning behind each one. Specifics are in the link. 

## 4 Hyperlinks
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks
As mentioned before ahref is used to make a hyperlink
We can wrap a link inside an <a> tag and give it a href attribute
  
You can also turn BLOCK LEVEL elements into a link. And put the image between <a> tags

#### Best practices for links
A summary of good practices
- Make link accessible to all readers
- Don't repeat URLs
- Keep labels short
- Omit redundant 'click here'
- Use relative links over absolute links
- Use the download attribute when linking to a download

#### Navigation Menu
[ REFER TO CODE ] 
A simple navigation on each page is useful to give the impression that user is in the same place

#### Email Link
Not that important for me right now

## 5 Advanced Text Formatting
There are many types of elements that html has. The following are some useful ones, but when deciding what to use we should just refer to the documentation. We don't really have to memorise all these, just have a vague idea of what the possibilities are
* Description Lists
* Quotations - Outline and Inline
* Citations
* Abbreviations
* Address (contact details)
* Subscript and superscript
* Representing code 
* Times and Dates

## 6 Document and Website Structure
There are several components that are similar in most websites
* Header
* Nav Bar
* Main Content
* Side Bar
* Footer

## 7 Debugging HTML
TO DO LATER

## 8 HTML Tables
Only use tables for storing structured set of data. The article heavily emphasises not to use it for structuring a webpage which is strangely common back in the day. Generally CSS is needed to style the tables as well.
An example of html table is in table.html.
There are many ways to style tables as shown in the link

#### Advanced tables
Extra info on manipulating tables. Refer to link if needed

## 9 HTML Forms
An interaction between user and website application. Allows user to give data to the website. 
Usually comes in the form of textfields, boxes, buttons, checkboxes...
Most of the time the data collected by the form is sent to a web server.

```html
<form action="/my-handling-form-page" method="post">
</form>
```
The action attribute defines the location where the form's data should be sent
The method attribute defines which HTTP method to send the data with (GET or POST)

#### Sending form data to web server
One of the trickiest parts is to handle form data on the server side. 
From before we see that we need action and method. But we also need a NAME ATTRIBUTE which helps the server side 

#### Form Structure
Up to here -> https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/How_to_structure_an_HTML_form
