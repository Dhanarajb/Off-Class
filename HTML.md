# Introduction to HTML

## What is HTML?
HTML stands for **HyperText Markup Language**. It is the standard language used to create and design web pages. Think of HTML as the structure or skeleton of a webpage, defining elements like headings, paragraphs, links, images, and more.

### Breaking Down the Words:

#### **HyperText**
- "Hyper" means "beyond" or "extended." In the context of HTML, it refers to the ability to go beyond static text by linking to other resources, such as webpages, documents, videos, or images.
- "Text" refers to the content that is readable by humans and displayed on the webpage. HyperText allows users to navigate between related pieces of information through links.
- Example: When you click on a hyperlink in a webpage, it takes you to another location (e.g., another webpage or a specific section).

#### **Markup**
- "Markup" refers to the system of annotating text so that it can be distinguished and processed by a computer. In HTML, this is done using "tags."
- Tags are special keywords enclosed in angle brackets (`< >`) that define the type of content or its purpose.
- Example: The `<p>` tag is used to mark a paragraph, and the `<a>` tag is used for hyperlinks.

#### **Language**
- "Language" implies that HTML follows a set of rules and syntax that computers can understand.
- It provides a standardized way to create and structure web content, making it consistent and accessible across different devices and browsers.
- Example: The consistent use of `<h1>` for main headings ensures that browsers render it in a specific way, such as larger and bold text.

### Why Combine These Words?
When combined, **HyperText Markup Language** (HTML) represents a tool that:
1. Links content together (HyperText).
2. Uses tags to structure and label content (Markup).
3. Follows specific rules to ensure that content is displayed consistently (Language).

---

## Why is HTML Important?
1. **Foundation of Web Development**: All websites are built using HTML as the base.
2. **Works With Other Technologies**: HTML works alongside CSS (for styling) and JavaScript (for interactivity).
3. **Universal Compatibility**: All browsers understand and render HTML.

---

## Basic Structure of an HTML Document
Here’s the simplest HTML document:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First HTML Page</title>
  </head>
  <body>
    <h1>Welcome to HTML</h1>
    <p>This is my first webpage.</p>
  </body>
</html>
```

### Explanation of Each Part:
1. `<!DOCTYPE html>`: This tells the browser that the document is written in HTML5.
2. `<html>`: The root element of an HTML document. All content goes inside this tag.
3. `<head>`: Contains metadata about the webpage (like the title, character set, etc.).
4. `<title>`: Sets the title of the webpage, shown in the browser tab.
5. `<body>`: Contains all the visible content of the webpage, such as headings, paragraphs, images, etc.

---

## Common HTML Elements

### 1. Headings
Headings are used to structure content. HTML provides six levels of headings:
```html
<h1>This is a level 1 heading</h1>
<h2>This is a level 2 heading</h2>
<h3>This is a level 3 heading</h3>
```
- `<h1>` is the largest and most important heading.
- `<h6>` is the smallest and least important heading.

### 2. Paragraphs
Use `<p>` for paragraphs:
```html
<p>This is a paragraph of text.</p>
```

### 3. Links
Links are created using the `<a>` tag:
```html
<a href="https://www.example.com">Visit Example</a>
```
- The `href` attribute specifies the URL the link points to.

### 4. Images
Display images using the `<img>` tag:
```html
<img src="image.jpg" alt="Description of the image">
```
- `src` specifies the image file's location.
- `alt` provides alternative text for accessibility.

### 5. Lists
- **Ordered List**:
```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```
- **Unordered List**:
```html
<ul>
  <li>Item one</li>
  <li>Item two</li>
</ul>
```

### 6. Tables
Create tables using `<table>`, `<tr>` (row), and `<td>` (cell):
```html
<table>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>
```

### 7. Forms
Forms collect user input:
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>
```
- `action` specifies where the form data is sent.
- `method` specifies the HTTP method (e.g., GET or POST).

---

## Attributes
HTML elements can have attributes that provide additional information. Example:
```html
<img src="image.jpg" alt="A description" width="300" height="200">
```
- `src`, `alt`, `width`, and `height` are attributes of the `<img>` tag.

### Common Attributes:
1. **id**: Gives a unique identifier to an element.
2. **class**: Groups multiple elements for styling or scripting.
3. **style**: Adds inline CSS styles.
4. **href**: Specifies links for `<a>`.

---

## Semantic HTML
Semantic HTML uses meaningful tags to structure content. Examples:
- `<header>`: Defines the header section.
- `<footer>`: Defines the footer section.
- `<article>`: Represents an independent piece of content.
- `<nav>`: Defines navigation links.
- `<section>`: Groups related content.

Example:
```html
<header>
  <h1>My Website</h1>
</header>
<nav>
  <a href="/home">Home</a>
  <a href="/about">About</a>
</nav>
<section>
  <h2>Introduction</h2>
  <p>Welcome to my website.</p>
</section>
<footer>
  <p>&copy; 2025 My Website</p>
</footer>
```

---

## Best Practices
1. **Use Semantic HTML** for better accessibility and SEO.
2. **Close All Tags** properly.
3. **Indent Your Code** for readability.
4. **Use Meaningful Attribute Names** like `id` and `class`.
5. **Keep Content Organized** using headings, paragraphs, and sections.

---

## Exercise
### Task 1: Create Your First HTML Page
1. Open a text editor (like VSCode or Notepad++).
2. Copy this code:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>This is my first webpage created using HTML.</p>
  </body>
</html>
```
3. Save the file as `index.html`.
4. Open the file in a web browser.

### Task 2: Add More Elements
- Add a heading, an image, and a link to your HTML page.
- Use both ordered and unordered lists.

---

## Conclusion
HTML is the backbone of web development. Once you understand its structure and elements, you can create simple webpages and then enhance them with CSS and JavaScript for styling and interactivity. Keep practicing to master HTML!

