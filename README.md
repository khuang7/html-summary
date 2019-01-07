# html_prac
These are basically some important notes from several sources about html/css. Just a brush up because I basically forgot about this stuff

**Brushing up on HTML, CSS and Javascript**

1. HTML Basics (Recap)
2. HTML HEAD
3. Tables
4. Forms
5. CSS Intro
6. CSS Basics


| Source        | Link          |
| ------------- |:-------------:|
| MDN           | [MDN/Learn](https://developer.mozilla.org/en-US/docs/Learn)|


## 1 HTML Basics
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started
#### NESTING ELEMENTS IS POSSIBLE (by putting <strong></strong> inside the tag in the word very)
<p> My cat is <strong>very</strong> grumpy. </p>

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
There are many types of 

## 6 Document and Website Structure

## 7 Debugging HTML

## 8 HTML Tables

## 9 HTML Forms
