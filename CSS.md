# Design web pages with CSS
As html doing it's part of the web document as structuring the content in the web page the css takes the part of styling the content. 
check out this Image
![HtmlvsCss](https://i.suar.me/gzZ9B/)

Css refers to cascade style sheet and it writen in selctors with brakets containing styles rules. The selctor specify the elements the rule applies to. Different types of selectors allow you to target your rules at different elements.Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. See the following code

```
body {
  font-family: 'Raleway', sans-serif;
  background-color: white;
  margin: 0;
}


/* navbar */

header {
  background-color:#feeeee;
}

header nav {
  margin: 0 70px;
}

header nav h1 {
  font-size: xx-large;
  display: inline-block;
  float: left;
  color: #b34592;
}
header nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #feeeee;
}
```

There is three ways that allow us to style a document
1. **Inline**: this means that we can include css in the html element it self
2. **Internal**: this means that we can add style tag on the head tag of html document.
3. **External**: this means that we put the style in external file with .css extention and link iit in the html document.



