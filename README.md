# HTML Basics Guide

## Table of Contents

- [What is HTML?](#what-is-html)
- [HTML Tags & Attributes](#html-tags-and-attributes)
- [HTML Document Structure](#links)
- [Adding Images](#adding-images)
- [Text Formatting Tags](#text-formatting-tags)
- [Links](#links)
- [Bookmark Links](#bookmark-links)
- [Comments](#comments)
- [Lists](#lists)
- [Input Types](#input-types)
- [Tables](#tables)
- [Table Layouts](#table-layouts)
- [Videos](#videos)
- [Tooltips](#tooltips)

## What is HTML?

HTML (HyperText Markup Language) is the standard markup language used to create web pages. It provides the structure and content of websites using a system of elements and tags. HTML tells the browser how to display text, images, links, and other content on a webpage.

## Your First HTML Page

Here's a simple example of HTML content:

```html
<h1>Welcome to my webpage</h1>

<h2>HTML</h2>
<p>HTML stands for Hypertext Markup Language and is used to create web pages</p>
<button>Learn More</button>

<h2>CSS</h2>
<p>
  CSS stands for Cascading Style Sheets and is used to design web pages and make
  them responsive.
</p>
<button>Learn More</button>

<h2>JavaScript</h2>
<p>
  JavaScript is a programming language used to make web pages dynamic and
  interactive.
</p>
<button>Learn More</button>
```

This example demonstrates:

- **Headings** (`<h1>`, `<h2>`) for page titles and section headers
- **Paragraphs** (`<p>`) for text content
- **Buttons** (`<button>`) for interactive elements

## HTML Tags and Attributes

HTML uses **tags** to define elements and **attributes** to provide additional information about those elements.

### Basic Tags Example:

```html
<p>HTML stands for Hypertext Markup Language and is used to create web pages</p>
<p>
  CSS stands for Cascading Style Sheets and is used to design web pages and make
  them responsive.
</p>

<br /><br /><br /><br /><br /><br />

<p>
  JavaScript is a programming language used to make web pages dynamic and
  interactive.
</p>
<hr />

<input type="number" placeholder="Enter your age" />
```

**Key Elements:**

- `<p>` - Paragraph tag for text content
- `<br/>` - Line break (self-closing tag)
- `<hr/>` - Horizontal rule/line separator
- `<input>` - Form input with attributes:
  - `type="number"` - Specifies input type
  - `placeholder="Enter your age"` - Shows hint text

## HTML Document Structure

Every HTML document should have a proper structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>Welcome to my webpage</h1>
    <h2>HTML</h2>
    <p>
      HTML stands for Hypertext Markup Language and is used to create web pages
    </p>
    <button>Learn More</button>
    <h2>CSS</h2>
    <p>
      CSS stands for Cascading Style Sheets and is used to design web pages and
      make them responsive.
    </p>
    <button>Learn More</button>
    <h2>JavaScript</h2>
    <p>
      JavaScript is a programming language used to make web pages dynamic and
      interactive.
    </p>
    <button>Learn More</button>
  </body>
</html>
```

**Structure Breakdown:**

- `<!DOCTYPE html>` - Declares HTML5 document type
- `<html lang="en">` - Root element with language attribute
- `<head>` - Contains metadata (not visible on page)
  - `<meta charset="UTF-8">` - Character encoding
  - `<meta name="viewport"...>` - Responsive design settings
  - `<title>` - Page title shown in browser tab
- `<body>` - Contains all visible content

## Adding Images

### Basic Image:

```html
<img src="images/brandenburgertor.jpg" />
```

### Improved Image with Attributes:

```html
<img
  src="images/brandenburgertor.jpg"
  height="300"
  alt="An image of the Brandenburger Tor in Berlin"
/>
```

**Image Attributes:**

- `src` - Path to the image file
- `height` - Sets image height (width adjusts proportionally)
- `alt` - Alternative text for accessibility and SEO

## Text Formatting Tags

HTML provides various tags for formatting text:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formatting Tags</title>
  </head>
  <body>
    <p>
      <strong>This text is important (strong tag)</strong>
      <br /><br />
      <b>This text is bold (b tag)</b>
      <br /><br />
      <em>This text is emphasized (em tag)</em>
      <br /><br />
      <i>This text is italic (i tag)</i>
      <br /><br />
      <mark>This text is marked (mark tag)</mark>
      <br /><br />
      <del>This text is deleted or invalid (del tag)</del>
      <br /><br />
      <ins>This text is inserted (ins tag)</ins>
    </p>
  </body>
</html>
```

**Formatting Tags Explained:**

- `<strong>` - Important text (semantic emphasis, appears bold)
- `<b>` - Bold text (visual styling only)
- `<em>` - Emphasized text (semantic emphasis, appears italic)
- `<i>` - Italic text (visual styling only)
- `<mark>` - Highlighted/marked text
- `<del>` - Deleted/strikethrough text
- `<ins>` - Inserted/underlined text

## Key Concepts

### Semantic vs Visual Tags

- **Semantic tags** (`<strong>`, `<em>`) convey meaning and are better for accessibility
- **Visual tags** (`<b>`, `<i>`) only affect appearance

### Self-Closing Tags

Some tags don't need closing tags: `<br/>`, `<hr/>`, `<img/>`, `<input/>`

### Attributes

Provide additional information about elements and are written as `attribute="value"`

## Links

HTML links allow you to navigate between pages and websites using the `<a>` (anchor) tag.

### Basic Link Structure

**Homepage (index.html):**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Homepage</title>
  </head>
  <body>
    <h1>Homepage</h1>
    <a href="https://www.youtube.com">This is a link to YouTube</a>
    <br />
    <a href="about_us.html" target="_self">About Us</a>
  </body>
</html>
```

**About Us Page (about_us.html):**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>About Us</title>
  </head>
  <body>
    <h1>About Us</h1>
    <a href="index.html">Back to homepage</a>
  </body>
</html>
```

### Link Types:

- **External links**: `href="https://www.youtube.com"` - Links to other websites
- **Internal links**: `href="about_us.html"` - Links to other pages in your site
- **Target attribute**: `target="_self"` opens in same tab (default), `target="_blank"` opens in new tab

## Bookmark Links

Bookmark links allow you to jump to specific sections within the same page.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Homepage</title>
  </head>
  <body>
    <h1>Homepage</h1>
    <a href="https://www.youtube.com">This is a link to YouTube</a>
    <br />
    <a href="about_us.html" target="_self">About Us</a>
    <br />
    <a href="#my-example-heading">Bookmark Link</a>

    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit...</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit...</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit...</p>

    <h2 id="my-example-heading">Hello World</h2>
    <p>This section will be jumped to when the bookmark link is clicked.</p>
  </body>
</html>
```

**Key Points:**

- Use `href="#id-name"` to create bookmark links
- The target element must have a matching `id` attribute
- Great for navigation within long pages

## Comments

HTML comments allow you to add notes in your code that won't be displayed on the webpage.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Comments</title>
  </head>
  <body>
    <h1>HTML Comments</h1>

    <!-- TODO: Add login form-->

    <p>This is an example text</p>
    <p>This is another example Text</p>

    <button>Learn More</button>
  </body>
</html>
```

**Comment Syntax:**

- `<!-- Comment text here -->`
- Comments are invisible to users but visible in source code
- Useful for notes, reminders, and temporarily disabling code

## Lists

HTML provides two main types of lists: ordered (numbered) and unordered (bulleted).

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>About Me</title>
  </head>
  <body>
    <h1>Hello there, this is Fabian</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>

    <hr />
    <h2>My Top 3 Favourite Foods</h2>
    <ol>
      <li>Chicken with Rice and Broccoli</li>
      <li>English breakfast</li>
      <li>Chili con carne</li>
    </ol>

    <hr />
    <h2>Things I like to do in my free time</h2>
    <ul>
      <li>Working out in the gym</li>
      <li>Practicing the piano</li>
      <li>Playing table tennis and football</li>
    </ul>

    <hr />
    <h2>Learn more about my city</h2>
    <nav>
      <ul>
        <li><a href="https://www.berlin.de">Official Berlin website</a></li>
        <li>
          <a href="https://en.wikipedia.org/wiki/Berlin"
            >Wikipedia article about Berlin</a
          >
        </li>
        <li>
          <a href="https://pixabay.com/photos/search/berlin/"
            >Pixabay pictures of Berlin</a
          >
        </li>
      </ul>
    </nav>

    <img
      width="500px"
      src="https://cdn.pixabay.com/photo/2019/09/11/15/08/berlin-4468902_1280.jpg"
      alt="Brandenburger Tor in Berlin"
    />
  </body>
</html>
```

### List Types:

- **Ordered List (`<ol>`)**: Numbered list (1, 2, 3...)
- **Unordered List (`<ul>`)**: Bulleted list (•, •, •...)
- **List Items (`<li>`)**: Individual items in both list types
- **Navigation (`<nav>`)**: Semantic element often used with lists for navigation

## Input Types

HTML forms support various input types for different data collection needs.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Input Types</title>
  </head>
  <body>
    <form>
      <input type="text" maxlength="5" placeholder="text input field" />
      <br /><br />
      <input type="number" step="10" placeholder="numeric input field" />
      <br /><br />
      <input checked type="checkbox" />
      <br /><br />
      <input type="password" placeholder="password input field" />
      <br /><br />
      <input type="email" placeholder="email input field" />
      <br /><br />
      <input type="submit" />
      <br /><br />
      <input type="reset" />
      <br /><br />
      <label for="male">male</label>
      <input id="male" type="radio" name="gender" /><br />
      <label for="female">female</label>
      <input id="female" type="radio" name="gender" />
      <br /><br />
      <input type="date" />
      <br /><br />
      <input type="time" />
      <br /><br />
      <input type="color" />
      <br /><br />
      <input type="file" />
      <br /><br />
      <input type="search" placeholder="search input field" />
    </form>
  </body>
</html>
```

### Input Types Explained:

- **text**: Basic text input with `maxlength` attribute
- **number**: Numeric input with `step` attribute for increments
- **checkbox**: Can be `checked` by default
- **password**: Hides input text
- **email**: Validates email format
- **submit/reset**: Form control buttons
- **radio**: Grouped by `name` attribute, only one selectable per group
- **date/time**: Date and time pickers
- **color**: Color picker
- **file**: File upload
- **search**: Search input field

## Tables

HTML tables organize data in rows and columns.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tables</title>
  </head>
  <body>
    <h1>Tables</h1>
    <table>
      <thead>
        <tr>
          <th>firstname</th>
          <th>lastname</th>
          <th>gender</th>
          <th>year of birth</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Albert</td>
          <td>Einstein</td>
          <td>male</td>
          <td>1879</td>
        </tr>
        <tr>
          <td>Stephen</td>
          <td>Hawking</td>
          <td>male</td>
          <td>1942</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

### Table Structure:

- **`<table>`**: Container for the entire table
- **`<thead>`**: Table header section
- **`<tbody>`**: Table body section
- **`<tr>`**: Table row
- **`<th>`**: Table header cell
- **`<td>`**: Table data cell

## Table Layouts

**Note**: While tables can be used for layout, modern CSS Grid and Flexbox are preferred for webpage layouts.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tables for Layouting</title>
  </head>
  <body>
    <table cellspacing="20">
      <tr>
        <td>
          <img
            height="200px"
            width="300px"
            src="brandenburgertor.jpg"
            alt="Brandenburger Tor"
          />
        </td>
        <td>
          <h1>Brandenburger Tor</h1>
          <p>Pariser Platz, 10117 Berlin</p>
          <p>
            See location on
            <a href="https://www.google.com/maps/...">Google Maps</a>
          </p>
        </td>
      </tr>
    </table>
  </body>
</html>
```

### Layout Attributes:

- **`cellspacing`**: Space between table cells
- **`cellpadding`**: Space inside table cells
- **`width/height`**: Dimensions for images and elements

## Videos

### HTML5 Video Element

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4" />
  <source src="movie.ogg" type="video/ogg" />
  Your browser does not support the video tag.
</video>
```

### Embedding YouTube Videos

```html
<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/VIDEO_ID"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen
>
</iframe>
```

**Key Points:**

- Use HTML5 `<video>` for self-hosted videos
- Use `<iframe>` for embedded videos from platforms like YouTube
- Always provide fallback text for unsupported browsers

## Tooltips

HTML tooltips provide additional information when hovering over elements.

```html
<p title="This is a tooltip">Hover over this text to see a tooltip</p>

<img src="image.jpg" alt="Description" title="This tooltip appears on hover" />

<a href="https://example.com" title="Click to visit Example.com"
  >Link with tooltip</a
>
```

### Tooltip Implementation:

- **`title` attribute**: Built-in HTML tooltip functionality
- **Hover behavior**: Tooltips appear when mouse hovers over element
- **Accessibility**: Provides additional context for screen readers

## Next Steps

1. Learn CSS for styling your HTML elements
2. Study JavaScript for adding interactivity
3. Explore HTML5 semantic elements (`<article>`, `<section>`, `<aside>`)
4. Practice form validation and accessibility features
5. Learn about responsive design principles

## Resources

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Validator](https://validator.w3.org/)
- [WebAIM Accessibility Guidelines](https://webaim.org/)
