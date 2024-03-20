## HTML Document Structure

An HTML document is built using a specific structure that separates content and presentation. Here's a breakdown of the key parts:

**1. Document Type Declaration (DOCTYPE)**

* Not strictly an HTML element, but a crucial first line.
* Specifies the document type (usually HTML5).
* Example: `<!DOCTYPE html>`

**2. Root Element (<html>)**

* Encloses the entire HTML document.
* Acts as the container for all other elements.
* Optional `lang` attribute specifies the document's language.

**3. Head (<head>)**

* Contains meta information about the document, not directly visible on the webpage.
* Important elements within `<head>` include:
    * **Title (<title>)** - Defines the title displayed in the browser tab and search engine results.
    * **Meta Tags** - Provide additional information about the document (charset encoding, author, description, etc.).
    * **Links** - Reference external resources like stylesheets (`<link rel="stylesheet" href="style.css">`) or favicons (`<link rel="icon" href="favicon.ico">`).
    * **Scripts** - Embed JavaScript code for dynamic behavior (`<script src="script.js"></script>`).

**4. Body (<body>)**

* Contains the content displayed on the webpage.
* All visible elements like headings, paragraphs, images, lists, forms, etc., reside here.
* Structured using a variety of HTML elements.

**Here's an example of a basic HTML document structure:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>My Webpage</title>
  <meta charset="UTF-8">
</head>
<body>
  <h1>Welcome to my webpage!</h1>
  <p>This is some content.</p>
</body>
</html>
```

This structure provides a foundation for creating well-organized and informative webpages. By understanding these components, you can effectively build the framework for your web content.
