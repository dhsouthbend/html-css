[<<<Back](filter.md) | [Next>>>](selectors.md)

# Classes and IDs

Classes and IDs enable more fine-grained styling by allowing you to define your own selectors. The difference between classes and IDs is that IDs are unique, used to identify one specific element or part of an element, whereas classes are used to identify multiple instances of the same type of element.

Basically, if you're styling a part of your page that is unique, such as the navbar or footer, use an ID. If you're styling something that recurs in different places, like an info box or form field, use a class.

Incorporating classes and IDs into the styling of your document includes two steps:

1. Some HTML code that CSS selectors can refer back to must be added to your HTML document.
2. CSS rules that select that code must be added to your style sheet.

The code for classes and IDs is different in both CSS and HTML.

## HTML code

In HTML, classes and ids are added to the first part of a tag. Here's an example of what HTML code with classes and ids looks like:

```html
<ul id="navbar">
  <li>Home</li>
  <li>About</li>
</ul>
<h1 class="football">Football teams</h1>
  <ul>
    <li class="football" id="colts">Indianapolis Colts</li>
    <li class="football" id="packers">Green Bay Packers</li>
  </ul>
<h1 class="baseball">Baseball teams</h1>
  <p>American League teams</p>
    <ul>
      <li class="baseball american" id="twins">Minnesota Twins</li>
      <li class="baseball american" id="tigers">Detroit Tigers</li>
    </ul>
  <p>National League teams</p>
    <ul>
      <li class="baseball national" id="dodgers">Los Angeles Dodgers</li>
      <li class="baseball national" id="mets">New York Mets</li>
    </ul>
```
Note that it's possible to assign more than one class to an element — just leave a blank space between the two classes, as in the baseball examples above.

## CSS selectors

### Class selectors

Class selectors in CSS are denoted with a period in front of the class name you're selecting. They look like this:

```css
#navbar {
  background-color: red;
  color: white;
}
.football {
    font-family: arial;
    background-color: lightgrey;
    color: blue;
}
.baseball {
  font-weight: bold;
  color: green;
}
.american {
  background-color: yellow;
}
```

### ID selectors 

...look like this in the CSS — the name of the selector preceeded by a hashmark (`#`) (also known as a pound sign or octothorpe):

```css
#twins {
    background-color: pink;
    color: blue;
}
```


## Tip
*If you run into an error, be sure to check your punctuation. Often times the problem is a typo, or overlooking a semi-colon, etc.* See the [Troubleshooting](troubleshooting.md) section for more information on common issues.

[<<<Back](filter.md) | [Next>>>](selectors.md)
