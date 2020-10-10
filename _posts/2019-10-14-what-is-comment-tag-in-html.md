---
title: What is comment tag in HTML?
date: 2020-10-10T10:11:14+00:00
author: avic
layout: post
permalink: /make-singleline-and-multiline-comments-html/
categories:
  - HTML
---
<img src="/public/2020/single-multi-line-comments-html.png" alt="image showing single-line and multiline comments in HTML">
You can create a single line comment by putting &lt;!-- at the start and --&gt; at the end of your comment.

You can also make a multi-line comment in HTML by adding &lt;!-- at the beginning of your comment and --&gt; at the end of your multi-line comment. 

## Comments tags in HTML
&lt;!-- Signify the beginning of your comment and --&gt; indicate the end of your comment. So it is important to ensure that your HTML comment does not contain &lt;!-- and --&gt; inside it. If they happen to be inside the comment, your comment might break and stop becoming a comment.

A comment tag is a HTML tag that is used to add comments to a HTML page. A HTML comment tag must have:

<li style="list-style-type: none;">
  <ol>
    <li>
      <!&#8211; at the beginning of the comment.
    </li>
    <li>
      Text or HTML markup in between.
    </li>
    <li>
      &#8211;> at the end of the comment.
    </li>
  </ol>
</li>

## Single line comments in HTML
<img src="repos/hyde/public/2020/single-line-html-comment.png" alt="single line comment example">

An example of a single-line HTML comment tag is:

<pre>&lt;!-- This is a single line HTML comment --&gt;</pre>


## Multi-lines comments in HTML
<img src="repos/hyde/public/2020/multi-line-html-comment.png" alt="multiline comment example">

If you want to comment out a whole HTML section, you can use a multi-line HTML comment as shown below:

<pre>&lt;!-- This is a multi-line HTML comment
  It contains a lot of HTML content inside it.
  &lt;div id="header"&gt;
    &lt;h1 id="my-logo" class="title"&gt;Picture learner&lt;/h1&gt;
 --&gt;
    &lt;h2 class="subtitle"&gt;Learn through pictures and sounds&lt;/h2&gt;
  &lt;/div&gt;</pre>

Any text inside the comment tag is not visible to the reader on the browser. You can view the comments when you click:  &#8220;view page source&#8221; on a browser.

You can use the comment tags to:

<li style="list-style-type: none;">
  <ul>
    <li>
      insert comments in the source code
    </li>
  </ul>
</li>

When you are writing the HTML code, you can use the comment to explain what each section of the code is doing.

<li style="list-style-type: none;">
  <ul>
    <li>
      hide part of a webpage from being displayed.
    </li>
  </ul>
</li>

You can use HTML comment tag to comment out HTML code. If you have a part of a webpage that you want to hide it but not delete it, then HTML comment tag is your best bet. This way, you can hide a whole section of a HTML page from being viewed on the browser.

You can use comments to explain your code, which can help you when you edit the source code at a later date. This is especially useful if you have a lot of code.