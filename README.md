# Code Reference for CSS
## CSS Selectors
Assign style for all elements of a given class
The basic style of a CSS file looks as follows
```CSS
selector {
    property1: value1;
    property2: value2;
}
```
Example for customizing the paragraph class
```CSS
p {
  text-align: center;
  color: red;
}
```
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

