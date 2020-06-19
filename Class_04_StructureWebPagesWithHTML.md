- [Return to Home Page](/README.md)

The following is a summary outline of what I learned from Jon Duckett's book _*HTML & CSS Design and Build Websites*_

# Chapter 18
## Process and Design
* consider the audience, meet their needs
   - why they visit
   - who are they? (create personas)
   -  what is their goal
   -  what info is needed
   -  how often they come

* Use a site map to plan the structure

* Make a wireframe for each page to layout its appearance

Use a Visual Heirachy (helps steer the audience)
* size
* color
* style

Simplify using grouping and similarity

# Chapter 1
## Structure
This was review of DeltaV 101.

HTML = text editor that uses tags

tags = elements with attributes

attributes have a *name* and a *value*

# Chapter 17
## HTML 5 Layout
HTML5 elements are helpful alternatives to  `<div>`

i.e. `<article>` instead of `<div class="artcle">`

Older browsers will treat HTML5 as inline elements (instead of block), so do the following in order to render correctly in older browsers:

CSS
   - header{display: block;}
   - section{display: block;}
   - footer{display: block;}
   - aside{display: block;}
   - nav{display: block;}
   - article{display: block;}
   - figure{display: block;}
   - figcaption{display: block;}

HTML

      `<!--[if lt IE 9]>`
          `<script scc="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>`
      `<![endif]-->`

# Chapter 8
## Extra Markup
* specifying different versions of HTML 
   put this in the first line of code:
   <!DOCTYPE html>
* comments
   <!-- comment goes here -->
* global attributes including class and id
   values must start with a letter or underscore
* grouping elements
   <div></div> or <span></span>
* `<meta> ` 
      data about the content
* iframes
   page within a page