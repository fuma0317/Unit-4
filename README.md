# Unit-4

## I will record all skills that are useful for webpage (HTML and CSS) ##

Contents
------------
1. [Basic skills for HTML](#HTML_basics)
1. [Basic skills for CSS](#CSS_basics)
1. [More tags for HTML](#HTML_advance)



HTML_basics
------------
**How to start the program**
```
<!DOCTYPE html>
<html>

</html>
```

**Simple page with title and some sentences**
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My poem</title>
   </head>
   <body>
    <h1>My heading<h2>
    <p>Example paragrapgh</p>
   </body>
<html>
```
```
<head> is used for ssetting language or name f the page. 
We have various sizes of titles from h1 to h6.
<h1> is the biggest.  
<p> is for writing paragraph with normal letters. 
<br> stands for "break" and it enables to start on a new line.
```
**Text emphasis**
```
<em>くぁwせdrftgyふじこlp</em>
```
This shows Italic words

```
<strong>くぁwせdrftgyふじこlp</strong>
```
This shows bold words and they can be combined.

**Lists**

![listinput](htmllist.JPG)
![listoutput](httmllist2.JPG)

**Images**
```
<img src="URL OF PIC" alt="food" width="200"
```
you write link of the pic and write src= with it.  alt is for blind people. The automatic reading system would say "food" instead of pic. And you can arrange the size of pic with "width" and "height" 

CSS_basics
-----------
**Changing color**
```
<head>
  <style>
    body {
    background-color: rgb(235, 130, 103                 );}
            p {
                color: rgb(245, 233, 245);}
   </style>
</head>
```
**Selecting by id**
id only can be used for one element. 
```
<h1 id="info-about-Japan">Info!</h1>
```
This is how we set the id for elements

```
<style>
  #info-about-Japan {
    color: purple;
    }
```
This is how we use the id

**Selecting by class**
class can be used for multiple elements
```
<p class="architecture">architecture is art</p>
```
This is how we set the class for elements

```
<style>
.architecture {
  color: rgb(0, 0, 0);
    }
</style>
```

HTML_advance
-----
**HTML links**
```
<a target="_blank" href="URL of webpage">Please click here!!</a>
```
```
With target="_blank", users get a choice if they open the new page or not by themselves. 
"href" stands for hyper reference. So you put a link there.
In between <a> and </a>, type the sentence that turns into click button for URL.
```
**HTML internal links**
```
<body>
  <ul>
    <li><a href="#history-Python"</a></li>
  <ul>
  
  <h2 id="history-Python">History of Python!!</h2>
 </body>
```
For internal link, you use id instead of URL
  
