---
title: 'Are HTML tags case sensitive?'
date: 2020-08-20
author: avic
layout: post
permalink: /are-html-tags-case-sensitive/
--- 

No. HTML tags are not case sensitive. You can write all HTML tags in lowercase or uppercase and they will be correctly rendered on a browser. This means that `<h1>lowercase</h1> and <H1>UPPERCASE</H1>` will work on any browser.

## Does case matter in HTML?

It does not matter if you use uppercase or lowercase in HTML. However there are a few exceptions.

**WHATWG** a body that works on improving the current version of HTML states:

' Many strings in the HTML syntax (e.g. the names of elements and their attributes) **are case-insensitive, but only for ASCII upper alphas and ASCII lower alphas**. For convenience, in this section this is just referred to as "case-insensitive".'

Some of the places where case matters is some HTML entities that are used to display non-keyboard characters. e.g. 
To display uppercase Ñ  you need to use the entity with an uppercase:  `&Ntilde;` and a lowercase ñ you use lowercase entity `&ntilde;`. 

It is generally recommended that you use lowercase in HTML. I think its also easier to write HTML in lowercase as long as you are typing your sentences in lowercase.

Source: 
1. [HTML entities - DevPractical](https://devpractical.com/display-html-tags-as-plain-text/)
2. [HTML case - WHATWG](https://html.spec.whatwg.org/multipage/syntax.html)


