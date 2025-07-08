# HTML Notes

## Basic Structure

An HTML document consists of the following basic structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```

HTML uses elements (specific character between the bracket `<p/>`) to describe the struct of the pages
Bellow is more information about elements in HTML5

- `<!DOCTYPE html>`: Defines the document type as HTML5.
- `<html>`: The root element of an HTML page.
- `<head>`: Contains meta-information about the HTML page, such as the title, character set, and linked stylesheets.
- `<title>`: Specifies a title for the HTML page (which is shown in the browser's title bar or tab).
- `<body>`: Defines the document's body, and contains all the content (text, images, videos, etc.).
- `<h1>` to `<h6>`: Define HTML headings. `<h1>` is the most important heading, and `<h6>` is the least important.
- `<p>`: Defines a paragraph.

## Common HTML Elements

- **Headings:** `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
- **Paragraphs:** `<p>`
- **Links:** `<a>`
  ```html
  <a href="https://www.example.com">Visit Example</a>
  ```
- **Images:** `<img>`
  ```html
  <img src="image.jpg" alt="Description of the image" />
  ```
- **Lists:**

  - Unordered list `<ul>`
  - Ordered list `<ol>`
  - List item `<li>`

  ```html
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
  </ul>

  <ol>
    <li>First item</li>
    <li>Second item</li>
  </ol>
  ```

- **Forms:** `<form>`, `<input>`, `<textarea>`, `<button>`, `<select>`
- **Tables:** `<table>`, `<tr>`, `<td>`, `<th>`

## Attributes

HTML elements can have attributes that provide additional information about elements or setting the element.

- `src`: Specifies the URL of an image (for `<img>`).
- `href`: Specifies the URL of a link (for `<a>`).
- `alt`: Specifies an alternate text for an image (for `<img>`).
- `class`: Specifies a class name for an element (used by CSS and JavaScript).
- `id`: Specifies a unique id for an element.
- `style`: Specifies inline styles for an element.

## Semantic HTML

Using semantic HTML elements improves accessibility and SEO.
In Web browser we have some stuff call ScreenReader and using sematic elements help this improve the experience of other user who are visually impaired, illiterate, or have a learning disability

- `<article>`: Represents a self-contained composition in a document, page, application, or site.
- `<aside>`: Represents a portion of a document whose content is only indirectly related to the document's main content.
- `<nav>`: Represents a section of a page that links to other pages or to parts within the page.
- `<header>`: Represents introductory content, typically a group of introductory or navigational aids.
- `<footer>`: Represents a footer for a document or section.

This is a basic overview of HTML. Further topics include HTML5 APIs, web storage, and more advanced form handling.
