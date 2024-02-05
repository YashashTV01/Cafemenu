# Cafe Menu Webpage

## HTML Structure:

### Document Type Declaration:

```html
<!DOCTYPE html>
```

Specifies that the document is an HTML5 document.

### HTML Document:

```html
<html lang="en">
```

The root element of the HTML document, indicating the language as English.

### Head Section:

```html
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cafe Menu</title>
  <link href="style.css" rel="stylesheet"/>
</head>
```

Contains meta-information about the document, including character encoding, viewport properties, title, and a link to an external CSS stylesheet named "style.css."

### Body Section:

```html
<body>
  <div class="menu">
```

Contains the content of the webpage within a container div with the class "menu."

### Menu Content:

```html
<main>
  <h1>CAMPER CAFE</h1>
  <p class="established">Est. 2020</p>
  <hr>
  <!-- ... -->
</main>
```

The main content of the menu includes the cafe name, establishment year, and horizontal line for visual separation.

### Footer:

```html
<hr class="bottom-line">
<footer>
  <p>
    <a href="https://www.freecodecamp.org" target="_blank">Visit our website</a>
  </p>
  <p class="address">123 Free Code Camp Drive</p>
</footer>
```

The footer contains a horizontal line, a link to the FreeCodeCamp website, and the cafe address.

## Functionality:

- The webpage serves as a cafe menu, categorizing items into sections like Coffee and Desserts.
- Each menu item is represented by an `<article>` element, containing information about the flavor and price.
- The webpage is designed with a simple and clean layout, responsive to different screen sizes.
