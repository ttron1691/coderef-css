# Code Reference for CSS
## Include CSS file in HTML document
Within a HTML document we may include a corresponding CSS file "style.css" as follows
```HTML
<link rel="stylesheet" type="text/css" href="/style.css" />
```
In additional CSS can be included internally within a HTML component in the following way
```HTML
<style type="text/css">
div {
    color: #444;
}
</style>
```
Furthermore we may include styles inline
```HTML
<tag style="property: value"> </tag>
```
## CSS Selectors
Assign style for all elements of a given class
The basic style of a CSS file looks as follows
```CSS
selector {
    property1: value1;
    property2: value2;
}
```
### Universal Selector
The universal selector for all classes is given by
```CSS
* {
  property: value;
}
```
### Type selector
The type selector is sensitive to a given type.

For example, customizing the paragraph class reads
```CSS
p {
  text-align: center;
  color: red;
}
```
We can also define multiple types at the same Block
```CSS
h1, h2 {
  text-align: center;
  color: red;
}
```
### ID Selector
A style definition based on IDs of an element is given by
```CSS
#mystyle1 {
  text-align: center;
  color: red;
}
```
A given element with ID is affected as follows
```HTML
<p id="mystyle1">Hello World!</p>
```
### Class Selector
Elements of the same class are affected
```CSS
.center {
  text-align: center;
  color: red;
}
```
```HTML
<h1 class="center">Red and center-aligned heading</h1>
```
In this case only paragraph elements of the given class are affected
```CSS
p.center {
  text-align: center;
  color: red;
}
```
```HTML
<p class="center">This paragraph will be red and center-aligned.</p>
```
## Font properties
Typical types can be defined for font customization purposes

```CSS
.style1 {
  font-family: "Times New Roman", "sans-serif";
  font-weight: bold;
  font-size: 30px;
  color: #090;
  text-align: center;
  font-style: normal;
  font-variant: normal;
}
```
This can be applied as follows
```HTML
<div class="style1">Geeks for Geeks</div>
```
## Text Properties
We consider the following style properties of texts
```CSS
.style2 {
  color: red;
  text-align: center;
  text-decoration: underline;
  text-transform: lowercase;
  text-indent: 80px;
  letter-spacing: 4px;
  line-height: 40px;
  text-shadow: 3px 1px blue;
  word-spacing: 15px;
}
```


