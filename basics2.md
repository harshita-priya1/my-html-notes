# BDO stands for Bi-Directional Override.
The HTML <bdo> tag is used to override the current text direction
# <!-- Write your comments here -->
# HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
# HTML supports 140 standard color names.
# An RGBA color value is an extension of RGB with an Alpha channel (opacity).
# Tip: The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!
# HTML links are hyperlinks. it can also image etc
# for link tag : The target attribute specifies where to open the linked document.
The target attribute can have one of the following values:
 - _self - Default. Opens the document in the same window/tab as it was clicked
 - _blank - Opens the document in a new window or tab
 - _parent - Opens the document in the parent frame
 - _top - Opens the document in the full body of the window
# mailto: in href to open users email program
# button as a link : <button onclick="document.location='default.asp'">HTML Tutorial</button> 
# <style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>
 # Using bookmark in html link:<!DOCTYPE html>
<html>
<body>

<p><a href="#C4">Jump to Chapter 4</a></p>
<p><a href="#C10">Jump to Chapter 10</a></p>

<h2>Chapter 1</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 2</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 3</h2>
<p>This chapter explains ba bla bla</p>

<h2 id="C4">Chapter 4</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 5</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 6</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 7</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 8</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 9</h2>
<p>This chapter explains ba bla bla</p>

<h2 id="C10">Chapter 10</h2>
<p>This chapter explains ba bla bla</p>

</body>
</html>
