# Code Reference for CSS
## CSS Selectors
Assign style for all elements of a given class
The basic style of a CSS file looks as follows
```CSS
selector {
    property1: value1;
    property2: value2;
}
### Universal Selector
The universal selector for all classes is given by
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
## Font styling
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

```HTML
<div class="style1">Geeks for Geeks</div>
```


