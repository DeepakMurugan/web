# Assignment - 7

## HTML

### 1. WHAT IS HTML
HTML (HyperText Markup Language) is the standard language used to create and design web pages. It structures the web content by using tags and elements.

---

### 2. WHY HTML IS USED
HTML is used to create the structure of web pages. It helps in embedding text, images, links, videos, and other elements on a website. It provides the basic layout and structure of the web pages.

---

### 3. WHAT IS EMMET & LIST 5 EMMET
**Emmet** is a plugin for text editors that speeds up the development process by allowing developers to use shortcuts to generate HTML and CSS code quickly.

**5 Emmet Shortcuts:**
1. `!` or `html:5` - Generates the basic HTML5 boilerplate.
2. `ul>li*5` - Creates an unordered list with 5 list items.
3. `div.container` - Creates a div element with class="container".
4. `p{Hello World}` - Creates a paragraph with text "Hello World".
5. `input:text` - Creates an input element of type text.

---

### 4. SHORT CUT CREATE OF EMMET BOILER PLATE OF HTML
The shortcut to create an HTML boilerplate in Emmet is `!` or `html:5` and then press **Enter**.

---

### 5. WHAT STRUCTURE OF HTML
The basic structure of an HTML document is:
```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>
  <h1>Hello World</h1>
</body>
</html>
```

---

### 6. WHAT IS HEAD TAG
The `<head>` tag contains metadata, title, links to CSS files, scripts, and other information that is not displayed on the web page.

Example:
```html
<head>
  <title>My Website</title>
  <link rel="stylesheet" href="style.css">
</head>
```

---

### 7. WHAT IS BODY TAG
The `<body>` tag contains the main content of the web page that is visible to users, such as text, images, videos, forms, and other elements.

Example:
```html
<body>
  <h1>Welcome to My Website</h1>
</body>
```

---

### 8. IMPORTANT 3 ELEMENTS OR TAGS
1. `<h1>` - Heading Tag
2. `<p>` - Paragraph Tag
3. `<a>` - Anchor Tag (for hyperlinks)

---

### 9. WHAT IS DIFFERENT B/W ELEMENTS & TAGS IN HTML
- **Tag:** A tag is a part of HTML code that defines the beginning and end of an element (e.g., `<p>` and `</p>`).
- **Element:** An element consists of a start tag, content, and an end tag.

Example:
```html
<p>This is a paragraph.</p>
```
In the above example:
- `<p>` and `</p>` are tags.
- The entire line `<p>This is a paragraph.</p>` is an element.

---

## CSS

### 1. WHAT IS CSS
CSS (Cascading Style Sheets) is a stylesheet language used to design the layout and appearance of web pages. It controls the design, color, fonts, and overall look of a website.

---

### 2. WHY IS CSS
CSS is used to style HTML elements to make web pages attractive and responsive. It helps in:
- Changing text color, background color, and fonts.
- Adjusting layout and positioning.
- Making websites responsive on different devices.

---

### 3. HOW TO CONNECT HTML & CSS, TELL THE EMMET SHORTCUT
There are three ways to connect CSS with HTML:
1. **Inline CSS:** Using the `style` attribute inside an HTML tag.
```html
<p style="color: red;">This is a paragraph.</p>
```
2. **Internal CSS:** Using `<style>` tag inside the `<head>` section.
```html
<style>
p {
  color: red;
}
</style>
```
3. **External CSS:** Linking an external CSS file.
```html
<link rel="stylesheet" href="style.css">
```
**Emmet Shortcut:** `link:css` then press **Enter**.

---

### 4. HOW TO GET FONT & COLOR, IMAGE, CDN
- **Font:** Use Google Fonts (https://fonts.google.com/)
- **Color:** Use Color Palettes (https://colorhunt.co/)
- **Image:** Use Free Image Sources (https://unsplash.com/)
- **CDN:** Use a CDN link for libraries like Bootstrap, Tailwind, etc.

Example:
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
```

---

### 5. BASIC CSS FAMILY : TEXT FAMILY, COLOR & BACKGROUND FAMILY, BOX MODEL
1. **Text Family:** Includes font size, font family, text alignment, etc.
```css
p {
  font-family: Arial;
  font-size: 16px;
  text-align: center;
}
```
2. **Color & Background Family:** Includes text color, background color, background image, etc.
```css
body {
  background-color: lightblue;
}
```
3. **Box Model:** Includes margin, padding, border, width, height, etc.
```css
div {
  margin: 10px;
  padding: 15px;
  border: 1px solid black;
}
```

---

### 6. WHEN TO USE BACKGROUND IMG VS IMG TAG
- **Background Image:** Used when you want the image as a background of a section or a div.
```css
body {
  background-image: url('image.jpg');
}
```
- **Image Tag:** Used when you want to insert an image as content in the document.
```html
<img src="image.jpg" alt="Image">
```

---

### 7. WHAT IS LAYOUT & EXPLAIN ABOUT FLEXBOX PROPERTIES
- **Layout:** Refers to the arrangement of elements on a web page.
- **Flexbox:** A layout model that makes it easier to align and distribute space within a container.

**Flexbox Properties:**
1. `display: flex;` - Enables flexbox.
2. `justify-content:` - Aligns items horizontally.
3. `align-items:` - Aligns items vertically.
4. `flex-wrap:` - Wraps items when they exceed the container.
5. `gap:` - Adds space between items.

Example:
```css
div {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

---

### 8. WHAT IS TAILWIND CSS & WHY IS IT USED
- **Tailwind CSS:** A utility-first CSS framework used to create modern and responsive designs quickly.
- **Why Use It:**
  - It provides predefined classes.
  - Faster development process.
  - Easy to customize.

eg:
```html
<div class="bg-blue-500 text-white p-4">Hello Tailwind</div>
``
