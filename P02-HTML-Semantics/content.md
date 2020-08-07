---
title: "HTML Semantics"
slug: html-semantics
---


In this Chapter we will be using:
	**HTML** and **CSS**

# What is HTML?

HTML is short for "HyperText Markup Language". That may sound scary, but it simply means it is a language for describing web-pages using ordinary text.

# What is an HTML tag? 

HTML tags are the hidden keywords within a web page that define how your web browser must format and display the content.

Most tags must have two parts, an opening and a closing part. For example, **```<html>```** is the opening tag and **```</html>```** is the closing tag. Note that the closing tag has the same text as the opening tag, but has an additional forward-slash ( / ) character.

# What are tag attributes?

Attributes allow you to customise a tag, and are defined within the opening tag, for example:
```<img src="image1.jpg">``` or ```<p align="center"> ... </p>```
Here for **img** tag, the attribute is **src**, which defines where the source file of the image is located. 
For the **p** tag the attribute **align** defines how the paragraph will align on the browser.
To learn more about HTML tags click on this link : [HTML tags](http://www.simplehtmlguide.com/whatishtml.php)


# Let’s start by making the landing (shopping) page for our website.

First, let’s have the basic outline/boilerplate for HTML. 

You can learn more about the outline here: [HTML template](https://www.sitepoint.com/a-basic-html5-template/)

```html
<!DOCTYPE html>
<html>
<head>
<title>Title of the document</title>
</head>

<body>
  The content of the document......
</body>
</html>
```

The first line, ```<!DOCTYPE>``` is called **Document Type Declaration**. It tells the browser what kind of document it’s looking at. In our case, it’s telling the browser that our document is an Html file. 

Next is the ```<html>``` tag which contains the head tag and body tag. 

The head tag contains the title of our page, ```<title>```. This is also the place where we would link up external Stylesheet (like bootstrap) or our own custom made stylesheet. (Which we will be doing later on in the upcoming chapters).

The ```<body>``` element contains all the contents of an HTML document, such as headings, paragraphs, **images**, **hyperlinks**, **tables**, **lists**, etc. We also link our **javascript** file here. 

# Displaying our 'Hello World'

Let’s start by displaying ‘Hello World’ in our browser.

> [action] Add a paragraph tag (```<p>```) inside the body tag. Inside the paragraph tag, write, Hello World!

```html
<p> Hello World </p>
 ```

> [action] open your file in the browser now.
You should see ‘Hello World’.

Congratulations!🎉 You just displayed a text in your browser. 

> [action] save and push your progress on github
```bash
git add .
git commit -m ‘displayed hello world’
git push
```