 # Emmet Abbreviations and Shortcuts in VS Code

This README provides a quick reference guide for using Emmet abbreviations and shortcuts in Visual Studio Code to streamline HTML coding.



## 1. Basic HTML5 Boilerplate (!)
- *Usage*: Type ! and press Tab or Enter to generate a basic HTML5 boilerplate.
- *Result*:
  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Document</title>
  </head>
  <body>
      
  </body>
  </html>

  ```

  

## 2. '+' : Create Sibling Elements

Use the + symbol to create sibling elements.

Example: div+span

Result:
```html
<div></div>
<span></span>

```

## 3. '>' - Create Child Elements

Use the > symbol to create child elements.

Example: ul>li

Result:
```html
<ul>
  <li></li>
</ul>

```
## 4. '*' - Create Multiple Elements

Use the * symbol to create multiple instances of an element.

Example: ul>li*3

Result:
```html
<ul>
  <li></li>
  <li></li>
  <li></li>
</ul>

```

## 5.  Elements with IDs and Classes
### '#' : Element with an ID

Use the # symbol to create an element with an ID.

Example: div#container

Result:
```html
<div id="container"></div>

```


### 
### ' . ' - Element with a Class

Use the `.` symbol to create an element with a class.

Example: `div.className`

Result:
```html
<div class="className"></div>

```

## 6. '$' : Numbering Elements


Use the $ symbol to create numbered elements.

Example: ul>li.item$*3

Result:
```html
<ul>
  <li class="item1"></li>
  <li class="item2"></li>
  <li class="item3"></li>
</ul>

```

## 7. 'a{}' : Basic Anchor Tag with Text

Use the a{} syntax to create a basic anchor tag with text.

Example: a{Click here}

Result:
```html
<a href="">Click here</a>

```
