7# BDO stands for Bi-Directional Override.
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
# for one in anotherb page: <a href="html_demo.html#C4">Jump to Chapter 4</a>
# for img tag: The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).
# Use the CSS float property to let the image float to the right or to the left of a text
# image file formats supported: # apng,png,gif,ico,jpeg,svg
# Tag
Description
img->
Defines an image,
map->
Defines an image map,
area->
Defines a clickable area inside an image map,
picture->
Defines a container for multiple image resources

# The HTML <map> tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more <area> tags.
# <img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>
# You must define the shape of the clickable area, and you can choose one of these values:
 • rect - defines a rectangular region
 • circle - defines a circular region
 • poly - defines a polygonal region
 • default - defines the entire region
# <area shape="rect" coords="34, 44, 270, 350" href="computer.htm">
# ***background attachmnet for bgimg
# The HTML <picture> element gives web developers more flexibility in specifying image resources.
The <picture> element contains one or more <source> elements, each referring to different images through the srcset attribute. This way the browser can choose the image that best fits the current view and/or device.
Each <source> element has a media attribute that defines when the image is the most suitable.
# <picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>