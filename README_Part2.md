# How to Write an HTML Boilerplate  

![coding on a laptop](https://images.unsplash.com/photo-1587620962725-abab7fe55159?q=80&w=1931&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

An HTML boilerplate is the basic structure of an HTML document. It sets up the foundation for a web page and ensures that it displays correctly across different browsers and devices. Here's a brief tutorial on writing a basic HTML boilerplate.  

---

### 1. Basic Structure  

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```

- **`<!DOCTYPE html>`**: Declares the document type and version as HTML5.  
- **`<html lang="en">`**: The root element of the HTML document, with a language attribute to specify the language.  
- **`<head>`**: Contains metadata, links to stylesheets, and other head elements.  
- **`<meta charset="UTF-8">`**: Sets the character encoding for the document, ensuring proper display of text.  
- **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ensures the webpage is responsive on all devices.  
- **`<title>`**: Displays the title in the browser tab.  
- **`<body>`**: Contains the content visible to the user, like text, images, and other elements.  

---

### 2. Linking CSS and JavaScript  
To make your webpage interactive and styled, you can link external CSS and JavaScript files.  

**Example:**  

```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <script src="script.js"></script>
</body>
```

- `<link rel="stylesheet" href="styles.css">`: Connects an external CSS file to style the webpage.  
- `<script src="script.js"></script>`: Links an external JavaScript file for dynamic functionality.  
---

### 3. Example of Complete Boilerplate

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>Welcome to My Page</h1>
    <p>This is a simple HTML boilerplate example.</p>
    <script src="script.js"></script>
  </body>
</html>
```

>Tip: Keeping your CSS and JavaScript in separate files helps in organizing and maintaining the code effectively.

For more information on HTML boilerplates and best practices, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax)