---
title: 'How to create internal links to a section on the same page in HTML'
date: 2020-09-26
layout: post
description: 'You can create a link to a specific section or element on a the same webpage in two steps: 1. Assign the section/ element an id. <p id="section-1">The link jumps to this paragraph</p> 2. Add the id value to the link.<a href="#section-1">section-1</a>'
permalink: /internal-links-same-page/
---
You can create a **link to a specific section** or element on a the **same webpage** in two steps:
1. [Assign the section/ element an id.](#create-same-page-internal-links-assign-an-id-to-the-section-element) ```<p id="section-1">The link jumps to this paragraph</p>```
2. [Add the id value to the link.](#create-same-page-internal-links-add-the-id-value-to-the-link) ```<a href="#section-1">Jump to section 1</a>```
3. Linking to a section on different webpage.
4. Create link to element of a different website.

You can try it out by clicking on any of the four links above.

## Where and Why you should use Jump links to specific parts of a webpage.
- **On long articles:** If you have a really long articles, its makes it easy for your users to navigate your website. 
- **A specific call to action on a webpage:** Jump links are perfect you want your readers to subscribe, or contact or any other action located lower in the page.
- **One page website:** If you own a one page website, you know that your users can easily go to the different sections of your webpage just by clicking the navigation links at the top.

## Create same page internal links: Assign an id to the section/ Element
In HTML, you use an id attribute to identify one specific element on a webpage. Just like each person has an unique Identification number, the id value you create and assign to your HTML element should be unique on that specific webpage.
### Rules for creating ids
- Each of your **ids must be unique** on that one web page.
- Each of your **ids must not have spaces** in the name. If you want to seperate words and numbers, use hyphens and underscores instead of spaces.

in my case, I want to be able to jump to my subheadings so this is how my id's will look like:

```
<h2 id="assign-id">Create same page internal links: Assign an id to the section/ Element</h2>
<h2 id="add-link">Create same page internal links: Add the id value to the link</h2>
```

If you are using markdown, headings are automatically converted to their lowercase id equivalent seperated by hyphen with no special characters. If you inspect my headings, this is what you will see. See what I mean.
<img src="" alt="screenshot of my heading's id">


## Create same page internal links: Add the id value to the link
Normally, you use links to point to different webpages and website. To make your link to point to the current webpage, you use a ```href="/" ``` or the full url of the current webpage ``` href="devpractical.com/same-page-internal-link"```
 
 To point to a specific part of a web page, you add a pound sign followed by the id name at the end of the url ie. ```href="/#assign-id" ``` or	``` href="devpractical.com/same-page-internal-link/#add-link" ``` 

 If you click on the navigation items at the top, you will be able to jump to specific parts of the web page.
 <img src="" alt="Gif of jump link effects on a webpage">

## Create a link to an element on a different web page.
For you to add a link to a different page, you will need the url of that page and the id value of that section you want to link to.
You will then use the full url of the web page and then add the id value at the end of the url. Example:

I want to link to the books section a different page on this website. The url is https://devpractical.com/resources/ and the heading is books. I can create a link as follows:

Code:
``` 
<a href="https://devpractical.com/resources/#books">HTML and CSS books</a>
```

Result:
<a href="https://devpractical.com/resources/#books" target="_blank">HTML and CSS books</a> 

## Create a link to a section of another website.
If you are linking to a different website, you will have to find out if the website has assigned ids to the section you want to link to. You can do this by:
- Inspect Q element.
- Use the select tool.
- Check the html code for id value.

 If the element does not have an id value, you cannot link to that section. If it does then you can just add the pound sign and id to the url of the website and you are good to go.

Code:
``` 
<a href="https://avicndugu.github.io/cricket-eating/#which">Which insects do people eat</a>
```

 Result: 
<a href="https://avicndugu.github.io/cricket-eating/#which" target="_blank">Which insects do people eat</a>


 ## Create a link that jumps to the top and bottom of a web page.
### Link to top of your website
- Choose the top most part of your website. Which is the logo.
- Get it id value.
- For me its the website's logo with the id "logo".

So the link to go to the top will become: 

Code:
``` <a href="https://avicndugu.github.io/cricket-eating/#logo">Top</a> ```

Result:
<a href="https://avicndugu.github.io/cricket-eating/#logo"  target="_blank">Top</a>

### Link to bottom of your website
- Choose the bottom most part of your website.
- Get it id value.
- For me its the footer with the id "footer-style"
- So the link to go to the bottom will become:

Code:
```<a href="https://avicndugu.github.io/cricket-eating/#footer-style">Go to bottom</a>```

Result:
<a href="https://avicndugu.github.io/cricket-eating/#footer-style"  target="_blank">Go to bottom</a>
