---
id: 201
title: How to display html tags as plain text
date: 2019-04-02T10:59:31+00:00
author: avic
layout: post
guid: https://learn.avicndugu.com/?p=201
permalink: /display-html-tags-as-plain-text/
categories:
  - HTML
---
* * *

<img class="aligncenter wp-image-214 size-full" src="https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code.png" alt="Show HTML tags on browser I using HTML entities" width="784" height="418" srcset="https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code.png 784w, https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code-300x160.png 300w, https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code-768x409.png 768w" sizes="(max-width: 784px) 100vw, 784px" /> 

Ordinarily, HTML tags are not visible to the reader on the browser. They are there but you cannot see them.

<!--more-->

However, through **HTML entities** you can display the HTML tags that are part of the HTML markup code that could have never be seen on a browser.

To do this, you need to replace `<` with  ` &lt;`  or  `&60;` and   `>`   with ` &gt;` or  `&62;`.

**Example**  
So if you want to display: `<p> This is a paragraph </p>` on the browser, you write it as:  `&lt;p&gt;` This is a paragraph <p&gt.

## How to show HTML tags: HTML entities

HTML has some characters that make up the language they are the reserved character. The **reserved characters** in HTML are < , > , &#8221; and &. The browser will never display them since they have some meaning in HTML.  
HTML entities are pieces of text used to **display reserved characters**, invisible characters(like space) and other non-keyboard characters.

Entities begin with the ‘&’ followed by ‘entity name’ or ‘entity number’ and end with the ‘;’ ie. &entity-name; or &entity-number;

<h4 style="text-align: center;">
  Reserved characters in HTML
</h4>

<img class="aligncenter wp-image-208 size-full" src="https://learn.avicndugu.com/wp-content/uploads/2019/04/special-characters-html.png" alt="Reserved characters in HTML" width="604" height="309" srcset="https://learn.avicndugu.com/wp-content/uploads/2019/04/special-characters-html.png 604w, https://learn.avicndugu.com/wp-content/uploads/2019/04/special-characters-html-300x153.png 300w" sizes="(max-width: 604px) 100vw, 604px" /> 

<h4 style="text-align: center;">
  List of HTML entities
</h4>

<img class="aligncenter wp-image-207 size-full" src="https://learn.avicndugu.com/wp-content/uploads/2019/04/other-html-entities.png" alt="Commonly used HTML entities" width="540" height="660" srcset="https://learn.avicndugu.com/wp-content/uploads/2019/04/other-html-entities.png 540w, https://learn.avicndugu.com/wp-content/uploads/2019/04/other-html-entities-245x300.png 245w" sizes="(max-width: 540px) 100vw, 540px" /> 

View the complete lists of HTML entities.

  1. The complete [list of HTML entities](https://www.freeformatter.com/html-entities.html) with their numbers and names.
  2. [Character Entity Reference Chart](https://dev.w3.org/html5/html-author/charref).
  3. [HTML entities list](https://developer.mozilla.org/en-US/docs/Glossary/Entity)

## How to replace lots of < and > fast

The quickest way that I know of is to use the search and replace feature. This feature is available in all text editors.

<img class="aligncenter size-full wp-image-211" src="https://learn.avicndugu.com/wp-content/uploads/2019/04/mass-change-entities.png" alt="" width="640" height="510" srcset="https://learn.avicndugu.com/wp-content/uploads/2019/04/mass-change-entities.png 640w, https://learn.avicndugu.com/wp-content/uploads/2019/04/mass-change-entities-300x239.png 300w" sizes="(max-width: 640px) 100vw, 640px" /> 

To use this feature use &#8216;CTRL + H&#8217; or click on &#8216;FIND&#8217; on the menu bar and then click on replace. Add the symbol you want to replace and the entity you want to replace with.

Then, click on replace or replace all.

I hope by now you can be able to display the  HTML code on the web browser.

## How to preserve the code formatting/ indentation

As by now, you have noted that the indentation on your HTML code has disappeared.  
However, you can preserve the indentation by using the pre HTML tags.  
So wrap the code that you want to display online using the

<pre>&lt;pre &gt;
  Your HTML code goes in here.
    And can be indented.
&lt;/pre&gt;</pre>

HTML tags.

Example.

<img class="aligncenter size-full wp-image-214" src="https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code.png" alt="" width="784" height="418" srcset="https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code.png 784w, https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code-300x160.png 300w, https://learn.avicndugu.com/wp-content/uploads/2019/04/display-code-768x409.png 768w" sizes="(max-width: 784px) 100vw, 784px" /> 

Now go out there and share the code. If you have any question in HTML, ask in the comments below.

You can read more on [HTML tags](https://learn.avicndugu.com/tutorials/).