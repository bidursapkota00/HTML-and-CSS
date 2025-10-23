# HTML / CSS Basics Guide

![Bidur Sapkota](https://www.bidursapkota.com.np/_next/image?url=%2Fimages%2Fprofile3.png&w=48&q=75 "Bidur Sapkota - Developer")&nbsp;[Bidur Sapkota](https://www.bidursapkota.com.np/)

![HTML, CSS with Portfolio Project Guide by Bidur Sapkota](/test.jpg "HTML, CSS with Portfolio Project Guide – Blog by Bidur Sapkota")

## Table of Contents

1. [What is HTML?](#what-is-html)
2. [HTML Tags & Attributes](#html-tags-and-attributes)
3. [HTML Document Structure](#html-document-structure)
4. [Adding Images](#adding-images)
5. [Text Formatting Tags](#text-formatting-tags)
6. [Links](#links)
7. [Bookmark Links](#bookmark-links)
8. [Comments](#comments)
9. [Lists](#lists)
10. [Input Types](#input-types)
11. [Tables](#tables)
12. [Table Layouts](#table-layouts)
13. [Videos](#videos)
14. [Tooltips](#tooltips)
15. [Adding CSS - Three Methods](#adding-css---three-methods)
16. [Classes and IDs](#classes-and-ids)
17. [Colors](#colors)
18. [Height and Width](#height-and-width)
19. [Borders](#borders)
20. [Margin](#margin)
21. [Padding](#padding)
22. [Box Sizing](#box-sizing)
23. [Universal Selector](#universal-selector)
24. [Block vs Inline Elements](#block-vs-inline-elements)
25. [Display Property](#display-property)
26. [Border Radius](#border-radius)
27. [Text Properties](#text-properties)
28. [Font Properties](#font-properties)
29. [Centering Elements](#centering-elements)
30. [Background Images](#background-images)
31. [RGBA and Opacity](#rgba-and-opacity)
32. [Gradients](#gradients)
33. [Shadows](#shadows)
34. [Combinators](#combinators)
35. [Attribute Selectors](#attribute-selectors)
36. [Pseudo Classes](#pseudo-classes)
37. [Transitions](#transitions)
38. [Positioning](#positioning)
39. [Pseudo Elements](#pseudo-elements)
40. [Popup/Modal Design](#popupmodal-design)
41. [Flexbox Layout](#flexbox-layout)
42. [Grid Layout](#grid-layout)
43. [Media Query Example Guide](#media-query-example-guide)
44. [CSS Variables and Theming Guide](#css-variables-and-theming-guide)
45. [Animation with Keyframes](#animation-with-keyframes)
46. [Multi Page Website Build Guide](#multi-page-website-build-guide)
47. [Portfolio Website](#portfolio-website)

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
<img src="images/building.jpg" />
```

### Improved Image with Attributes:

```html
<img
  src="images/building.jpg"
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

### Attributes of List Types:

```html
<ul type="square"></ul>
<ul type="disc"></ul>
<ul type="circle"></ul>

<ol type="1"></ol>
<ol type="I"></ol>
<ol type="i"></ol>
<ol type="A"></ol>
<ol type="a"></ol>
```

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
            src="building.jpg"
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
  allow="picture-in-picture"
  allowfullscreen
>
</iframe>
```

**Key Points:**

- Use HTML5 `<video>` for self-hosted videos
- Use `<iframe>` for embedded videos from platforms like YouTube
- Always provide fallback text for unsupported browsers
- src="https://www.youtube.com/embed/VIDEO_ID?autoplay=1&mute=1&controls=0&start=6&loop=1"

**Quick Method:**

- Go to the YouTube video
- Click the "Share" button below the video
- Click "Embed"
- Copy the provided iframe code
- Paste it into your HTML

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

## HTML Resources

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)

## Adding CSS - Three Methods

CSS (Cascading Style Sheets) can be added to HTML documents in three different ways. Each method has its own use cases and priority levels.

### The Three Methods:

1. **Inline CSS**: Applied directly to HTML elements using the `style` attribute
2. **Internal CSS**: Written within `<style>` tags in the HTML document's `<head>` section
3. **External CSS**: Written in separate `.css` files and linked to the HTML document

### Priority Order (Specificity):

Inline CSS > Internal CSS > External CSS

### Example Code:

**HTML File:**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inline, Internal & External CSS</title>
    <link rel="stylesheet" href="style.css" />
    <style>
      h2 {
        color: green;
        background-color: black;
      }
    </style>
  </head>
  <body>
    <h2>Lorem ipsum, dolor sit amet</h2>
    <h2 style="color: blue; background: yellow;">
      Lorem ipsum, dolor sit amet
    </h2>
    <h2>Lorem ipsum, dolor sit amet</h2>
  </body>
</html>
```

**External CSS File (style.css):**

```css
body {
  background-color: yellow;
}
```

### Explanation:

- The first and third `<h2>` elements will have green text on black background (internal CSS)
- The second `<h2>` will have blue text on yellow background (inline CSS overrides internal CSS)
- The body background will be yellow (external CSS)

---

## Classes and IDs

Classes and IDs are selectors that allow you to target specific HTML elements for styling.

### Key Differences:

- **IDs**: Unique identifiers (should only be used once per page), selected with `#`
- **Classes**: Reusable identifiers (can be used multiple times), selected with `.`
- **Priority**: ID selectors have higher specificity than class selectors

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Classes and Ids</title>
    <style>
      p {
        background-color: aquamarine;
        color: darkblue;
      }
      #red-paragraph {
        color: red;
      }
      .green-element {
        color: green;
      }
      .gray-background {
        background-color: gray;
      }
    </style>
  </head>
  <body>
    <p>This is a paragraph</p>
    <p id="red-paragraph" class="green-element">This is a paragraph</p>
    <p class="green-element">This is a paragraph</p>
    <p class="green-element gray-background">This is a paragraph</p>
  </body>
</html>
```

### Explanation:

- All `<p>` elements get aquamarine background and dark blue text by default
- The element with `id="red-paragraph"` will have red text (ID overrides class)
- Elements with `class="green-element"` will have green text
- The last paragraph combines two classes for green text and gray background
- You can apply multiple classes to a single element by separating them with spaces

---

## Colors

CSS offers multiple ways to define colors, giving you flexibility in how you specify color values.

### Color Methods:

1. **Named Colors**: Predefined color names (e.g., `red`, `blue`, `yellow`)
2. **Hexadecimal**: Using hex codes (e.g., `#ff5733`)
3. **RGB**: Using RGB values (e.g., `rgb(255, 87, 51)`)
4. **Other methods**: HSL, RGBA, HSLA (for transparency)

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Colors</title>
    <style>
      body {
        color: yellow;
        background-color: #ff5733;
        background-color: rgb(255, 87, 51);
      }
    </style>
  </head>
  <body>
    <h1>This is a heading</h1>
  </body>
</html>
```

### Explanation:

- `color: yellow` sets the text color using a named color
- `background-color: #ff5733` sets background using hexadecimal
- `background-color: rgb(255, 87, 51)` overrides the hex value with RGB
- The RGB value represents the same color as the hex code
- When multiple declarations exist for the same property, the last one takes precedence

---

## Height and Width

Height and width properties control the dimensions of elements. They can be set using various units including pixels, percentages, and other relative units.

### Key Concepts:

- **Pixels (px)**: Absolute unit
- **Percentages (%)**: Relative to parent element
- **Parent-Child Relationships**: Child elements inherit sizing context from parents

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Height And Width</title>
    <style>
      .parent-div {
        background-color: green;
        width: 50%;
        height: 200px;
      }
      .child-div {
        background-color: blue;
        height: 50%;
        width: 150px;
      }
      /* div{
      background-color: blue;
      width: 400px;
    } */
    </style>
  </head>
  <body>
    <div class="parent-div">
      <div class="child-div"></div>
    </div>
    <br />
    <!-- <div>Lorem ipsum dolor sit amet</div> -->
  </body>
</html>
```

### Explanation:

- Parent div takes 50% of the viewport width and has a fixed height of 200px
- Child div has a fixed width of 150px and takes 50% of parent's height (100px)
- Percentage heights require the parent to have a defined height
- Commented code shows alternative styling approach

---

## Borders

Borders add visual boundaries around elements. You can control their width, style, and color independently for each side.

### Border Properties:

- **border-width**: Thickness of the border
- **border-style**: Style of the border (solid, dashed, dotted, double, etc.)
- **border-color**: Color of the border
- **Individual sides**: Can be styled separately using directional properties

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Border</title>
    <style>
      .borderExercise {
        width: 400px;
        height: 400px;
        background: chocolate;

        border-width: 10px;
        border-left-style: dashed;
        border-top-style: dotted;
        border-right-style: solid;
        border-bottom-style: double;
        border-right-color: cornflowerblue;
      }
    </style>
  </head>
  <body>
    <div class="borderExercise"></div>
  </body>
</html>
```

### Explanation:

- All borders have 10px width
- Each side has a different style: left (dashed), top (dotted), right (solid), bottom (double)
- Right border has a custom color (cornflowerblue)
- Other borders use the default color (usually black)
- This demonstrates the flexibility of border customization

---

## Margin

Margin creates space outside an element, pushing other elements away. It's the outermost layer of the CSS box model.

### Margin Properties:

- **Individual sides**: `margin-top`, `margin-right`, `margin-bottom`, `margin-left`
- **Shorthand**: `margin` can take 1-4 values
  - 1 value: all sides
  - 2 values: top/bottom, left/right
  - 4 values: top, right, bottom, left (clockwise)

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Margin</title>
    <style>
      body {
        margin: 0;
      }
      .box {
        background-color: lightgreen;
        height: 50px;
        /* margin-top: 20px;
      margin-bottom: 50px;
      margin-left: 30px;
      margin-right: 30px; */
        margin: 30px 10px;
      }
    </style>
  </head>
  <body>
    <div class="box">This is a box with margin.</div>
    <div class="box">This is a box with margin.</div>
    <div class="box">This is a box with margin.</div>
  </body>
</html>
```

### Explanation:

- `body { margin: 0; }` removes default browser margins
- `margin: 30px 10px` applies 30px to top/bottom and 10px to left/right
- Commented code shows individual margin properties
- Margins create space between the boxes
- Adjacent vertical margins collapse (merge) in normal document flow

---

## Padding

Padding creates space inside an element, between the content and the border. It's part of the element's total size.

### Padding Properties:

- **Individual sides**: `padding-top`, `padding-right`, `padding-bottom`, `padding-left`
- **Shorthand**: `padding` follows the same pattern as margin
- **Effect**: Increases the element's total size (unless using `box-sizing: border-box`)

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Padding</title>
    <style>
      body {
        margin: 0;
      }
      .box {
        background-color: lightgreen;
        height: 50px;
        width: 300px;
        margin: 20px;
        padding-top: 100px;
        padding-left: 120px;
        padding-right: 90px;
        padding-bottom: 50px;
        border: 10px solid black;
      }
    </style>
  </head>
  <body>
    <div class="box">This is a box with padding.</div>
    <div class="box">This is a box with padding.</div>
    <div class="box">This is a box with padding.</div>
  </body>
</html>
```

### Explanation:

- Different padding values on each side push the content inward
- The background color extends through the padding area
- Total element width = width + padding-left + padding-right + border-left + border-right
- Total element height = height + padding-top + padding-bottom + border-top + border-bottom
- Content is positioned according to the padding values

---

## Box Sizing

Box-sizing determines how the total width and height of elements are calculated, affecting how padding and borders are included.

### Box Sizing Values:

- **Content-box** (default): Width/height applies only to content
- **Border-box**: Width/height includes content, padding, and border

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Boxsizing Borderbox</title>
    <style>
      div {
        width: 200px;
        height: 50px;
        margin: 10px;
        background-color: lightblue;
        padding: 20px;
        border: 10px solid black;
      }
      .contentBox {
        box-sizing: content-box;
      }
      .borderBox {
        box-sizing: border-box;
      }
    </style>
  </head>
  <body>
    <div class="contentBox">content-box</div>
    <div class="borderBox">border-box</div>
  </body>
</html>
```

### Explanation:

- **Content-box**: Total width = 200px + 40px (padding) + 20px (border) = 260px
- **Border-box**: Total width = 200px (padding and border included)
- Border-box makes sizing more predictable and is often preferred
- Common practice: Use `* { box-sizing: border-box; }` for all elements

---

## Universal Selector

The universal selector (`*`) targets all elements on a page. It's commonly used for CSS resets and applying global styles.

### Universal Selector Uses:

- **CSS Reset**: Remove default browser styles
- **Global Styles**: Apply consistent styling across all elements
- **Box-sizing**: Set border-box for all elements

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Universal Selector</title>
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      h1,
      h2,
      h3,
      h4,
      h5,
      h6,
      p,
      ul,
      ol {
        background-color: aquamarine;
      }
    </style>
  </head>
  <body>
    <h1>This is a h1 heading</h1>
    <h2>This is a h2 heading</h2>
    <h3>This is a h3 heading</h3>
    <h4>This is a h4 heading</h4>
    <h5>This is a h5 heading</h5>
    <h6>This is a h6 heading</h6>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
    <p>This is a paragraph</p>
    <ul>
      <li>test1</li>
      <li>test2</li>
      <li>test3</li>
    </ul>
    <ol>
      <li>test1</li>
      <li>test2</li>
      <li>test3</li>
    </ol>
  </body>
</html>
```

### Explanation:

- `* { margin: 0; padding: 0; }` removes all default margins and padding
- This creates a clean slate for custom styling
- Group selectors target multiple elements with the same styles
- Universal selector has low specificity, so it's easily overridden
- Common in CSS frameworks and reset stylesheets

---

## Block vs Inline Elements

HTML elements are categorized into two main display types: **Block** and **Inline** elements. Understanding this distinction is crucial for proper layout design.

### Block Elements

- Take up full width available
- Start on a new line
- Can have width and height set
- Examples: `<div>`, `<h1>-<h6>`, `<p>`, `<li>`, `<hr>`

### Inline Elements

- Only take up as much width as necessary
- Don't start on a new line
- Width and height properties are ignored
- Examples: `<a>`, `<span>`, `<strong>`

### Inline-Block Elements

- Only take up as much width as necessary but Width and height properties can be set
- Combines features of both block and inline elments
- Examples: `<img>`, `<button>`, `<input>`

### Example Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Block and Inline Elements</title>
    <style>
      h2 {
        background-color: lightblue;
        width: 400px;
      }
      a {
        background-color: aqua;
      }
    </style>
  </head>
  <body>
    <h2>Headings are Block Elements</h2>
    <h2>Headings are Block Elements</h2>
    <h2>Headings are Block Elements</h2>
    <div>Div elements are block elements</div>
    <p>Paragraphs elements are block elements</p>
    <li>List-Items are block elements</li>
    <hr />

    <a href="#">Inline Element</a>
    <a href="#">Inline Element</a>
    <a href="#">Inline Element</a>
    <button>Inline Element</button>
    <span>Inline Element</span>
    <strong>Inline Element</strong>
    <img src="image.jpg" width="50" />
  </body>
</html>
```

**Explanation**: Notice how block elements stack vertically and take full width, while inline elements flow horizontally next to each other.

---

## Display Property

The `display` property allows you to change the default behavior of elements. You can make block elements behave like inline elements and vice versa.

### Display Values

- `block`: Makes element behave as block element
- `inline`: Makes element behave as inline element
- `inline-block`: Combines features of both (flows inline but accepts width/height)
- `none`: Hides the element completely

### Example Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Display Property</title>
    <style>
      p {
        border: 3px solid blue;
        margin: 50px;
        padding: 10px;
        display: inline-block;
      }
      div {
        border: 3px solid blue;
        margin: 10px;
        padding: 10px;
        display: inline;
      }
      span {
        border: 3px solid blue;
        margin: 10px;
        padding: 10px;
        display: block;
      }
    </style>
  </head>
  <body>
    <div>Inline-Element</div>
    <div>Inline-Element</div>
    <span>Block-Element</span>
    <span>Block-Element</span>
    <p>Inline-Block</p>
    <p>Inline-Block</p>
  </body>
</html>
```

**Explanation**: The `div` elements now flow inline, `span` elements behave as blocks, and `p` elements combine both behaviors (inline flow with block properties).

---

## Border Radius

The `border-radius` property creates rounded corners on elements. It's essential for modern web design and can transform sharp rectangular elements into circles, ovals, or elements with custom rounded corners.

### Border Radius Syntax

- Single value: `border-radius: 10px` (all corners)
- Four values: `border-radius: 10px 20px 30px 40px` (top-left, top-right, bottom-right, bottom-left)
- Individual corners: `border-top-left-radius`, `border-top-right-radius`, etc.

### Example Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Border Radius</title>
    <style>
      div {
        width: 200px;
        height: 200px;
        margin: 30px;
        background-color: blue;
        /* Individual corner properties:
      border-top-left-radius: 90px;
      border-top-right-radius: 60px;
      border-bottom-left-radius: 5%;
      border-bottom-right-radius: 30px; */
        border-radius: 90px 60px 30px 5%;
      }
    </style>
  </head>
  <body>
    <div></div>
  </body>
</html>
```

**Explanation**: This creates a uniquely shaped element with different radius values for each corner. You can use pixels or percentages for radius values.

---

## Text Properties

CSS provides extensive control over text appearance and alignment. These properties are fundamental for typography and readability.

### Text Alignment

Text alignment controls how text is positioned within its container.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Text Alignment</title>
    <style>
      h4 {
        width: 400px;
      }
      .left {
        text-align: left;
      }
      .center {
        text-align: center;
      }
      .right {
        text-align: right;
      }
      p {
        text-align: justify;
      }
    </style>
  </head>
  <body>
    <h4 class="left">text-align: left</h4>
    <h4 class="center">text-align: center</h4>
    <h4 class="right">text-align: right</h4>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis ut
      sapiente recusandae facere delectus quia fugiat eos illum ea perspiciatis
      asperiores dolor, corrupti ad odit dicta expedita quos quisquam non! Lorem
      ipsum dolor sit amet consectetur adipisicing elit. Blanditiis ut sapiente
      recusandae facere delectus quia fugiat eos illum ea perspiciatis
      asperiores dolor, corrupti ad odit dicta expedita quos quisquam non! Lorem
      ipsum dolor sit amet consectetur adipisicing elit. Blanditiis ut sapiente
      recusandae facere delectus quia fugiat eos illum ea perspiciatis
      asperiores dolor, corrupti ad odit dicta expedita quos quisquam non! Lorem
      ipsum dolor sit amet consectetur adipisicing elit. Blanditiis ut sapiente
      recusandae facere delectus quia fugiat eos illum ea perspiciatis
      asperiores dolor, corrupti ad odit dicta expedita quos quisquam non!
    </p>
  </body>
</html>
```

### Text Decoration

Text decoration adds visual effects to text like underlines, overlines, and strikethroughs.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Text-Decoration</title>
    <style>
      h4 {
        text-decoration: wavy #123456 5px line-through;
      }
      a {
        text-decoration: none;
      }
    </style>
  </head>
  <body>
    <h4>This is a h4</h4>
    <a href="#">This is a link</a>
  </body>
</html>
```

### Text Transform

Text transform changes the capitalization of text without changing the HTML content.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Text Transform</title>
    <style>
      p {
        text-transform: uppercase;
      }
    </style>
  </head>
  <body>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod quos placeat
      praesentium unde fugit dolores, impedit maxime quisquam minima adipisci
      itaque ratione totam vitae nemo commodi voluptate est repellendus eveniet!
    </p>
  </body>
</html>
```

**Explanation**: Text properties control alignment (left, center, right, justify), decoration (underline, overline, line-through), and transformation (uppercase, lowercase, capitalize).

---

## Font Properties

Font properties control the appearance of text including size, family, and weight. These are crucial for establishing visual hierarchy and brand consistency.

### Font Size with REM Units

REM (Root EM) units are relative to the root element's font size, making them ideal for responsive design.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Font-Properties</title>
    <style>
      html {
        font-size: 62.5%;
      }
      h1 {
        font-size: 3rem; /* 3 * 12pt = 36pt */
      }
      h2 {
        font-size: 2rem;
      }
      h3 {
        font-size: 1.5rem;
      }
      p {
        font-size: 1rem; /* 1 * 12pt = 12pt */
      }
    </style>
  </head>
  <body>
    <h1>This is a heading</h1>
    <h2>This is a heading</h2>
    <h3>This is a heading</h3>
    <p>
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eligendi
      incidunt veniam consequuntur enim voluptatibus animi saepe obcaecati
      mollitia ea debitis esse non voluptate asperiores nam ullam ratione,
      accusamus praesentium. Dolorum.
    </p>
  </body>
</html>
```

### Font Family and Weight

Font family specifies which fonts to use, while font weight controls the thickness of characters.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap"
      rel="stylesheet"
    />
    <title>Weight, Family</title>
    <style>
      p {
        font-family: "Playwrite CU", Arial, Helvetica, sans-serif;
        font-weight: lighter;
      }
      h2 {
        font-weight: normal;
      }
      div {
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <h2>This is a heading</h2>
    <div>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Deserunt hic
        voluptatum quo sint a, nostrum incidunt necessitatibus deleniti quis
        aperiam corrupti architecto fuga non quasi repellendus accusamus
        eligendi itaque magnam!
      </p>
    </div>
  </body>
</html>
```

**Explanation**: REM units create scalable typography, Google Fonts provide custom typefaces, and font-weight values (lighter, normal, bold, or numeric values 100-900) control text thickness.

---

## Centering Elements

Centering elements is a common layout requirement. This example demonstrates both horizontal and vertical centering techniques using modern CSS properties.

### Centering Techniques Used

- `margin: 0 auto` for horizontal centering of block elements
- `text-align: center` for centering inline content
- `align-content: center` for vertical centering in containers
- Setting explicit dimensions and using full viewport height

### Example Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Center elements</title>
    <style>
      html {
        height: 100%;
      }
      body {
        align-content: center;
        height: 100%;
        margin: 0;
      }
      div {
        width: 50%;
        height: 300px;
        background-color: lightblue;
        margin: 0 auto;
        align-content: center;
      }
      p {
        width: 50%;
        height: 150px;
        background-color: gray;
        margin: 0 auto;
        text-align: center;
        align-content: center;
      }
    </style>
  </head>
  <body>
    <div>
      <p>This is a paragraph</p>
    </div>
  </body>
</html>
```

**Explanation**: This creates a perfectly centered layout where the outer div is centered horizontally and vertically on the page, and the inner paragraph is centered within the div both horizontally and vertically.

### Key Centering Concepts

- **Horizontal centering**: `margin: 0 auto` for block elements, `text-align: center` for inline content
- **Vertical centering**: `align-content: center` on containers with defined height
- **Full viewport usage**: Setting `html` and `body` to `height: 100%` to use full screen height
- **Nested centering**: Each element can be centered within its parent container

---

## Background Images

Background images allow you to set images as backgrounds for elements. You can control how they repeat, size, and position.

### Key Properties:

- `background-image`: Sets the image
- `background-repeat`: Controls repetition
- `background-size`: Controls sizing
- `background-attachment`: Controls scrolling behavior

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Background Image</title>
    <style>
      body {
        background-image: url("building.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
        height: 100vh;
      }
    </style>
  </head>
  <body>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit...</p>
    <!-- Multiple paragraphs for scrolling effect -->
  </body>
</html>
```

### Background Properties Explained:

- `cover`: Scales image to cover entire container
- `no-repeat`: Image appears only once
- `fixed`: Image stays fixed during scrolling
- `100vh`: Full viewport height

---

## RGBA and Opacity

Transparency in CSS can be achieved through RGBA colors or the opacity property. The key difference is that opacity affects the entire element and its children.

### RGBA vs Opacity:

- **RGBA**: Only affects background color
- **Opacity**: Affects entire element including text and children

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Transparent Colors</title>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body {
        height: 100vh;
        padding: 50px;
        background-image: url("building.jpg");
        background-repeat: no-repeat;
        background-size: cover;
      }
      div {
        width: 300px;
        height: 300px;
        display: inline-block;
        margin-right: 50px;
        border: 5px solid black;
      }
      .alpha {
        background-color: rgba(200, 0, 0, 0.7);
      }
      .opacity {
        background-color: blue;
        opacity: 0.3;
      }
    </style>
  </head>
  <body>
    <div class="alpha">
      <p>Text remains opaque</p>
    </div>
    <div class="opacity">
      <p>Text becomes transparent too</p>
    </div>
  </body>
</html>
```

### RGBA Syntax:

- `rgba(red, green, blue, alpha)`
- Alpha values: 0 (transparent) to 1 (opaque)

---

## Gradients

CSS gradients create smooth transitions between colors. There are two main types: linear and radial gradients.

### Types of Gradients:

- **Linear**: Colors transition in a straight line
- **Radial**: Colors transition from center outward
- The values to top, to bottom, to left, and to right are equivalent to the angles 0deg, 180deg, 270deg, and 90deg, respectively. o deg = bottom to top [ to top ]
- There can be multiple background. (colors, image)

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Gradients</title>
    <style>
      div {
        margin: 20px;
        width: 200px;
        height: 200px;
        border: 1px solid black;
      }
      .linear {
        background-image: linear-gradient(
          black 33%,
          red 33%,
          red 67%,
          yellow 67%
        );
        /* linear-gradient(direction, color1 stop1, color2 stop2, ...) */
      }
      .radial {
        background-image: radial-gradient(red, yellow);
      }
    </style>
  </head>
  <body>
    <div class="linear"></div>
    <div class="radial"></div>
  </body>
</html>
```

### Gradient Syntax:

- **Linear**: `linear-gradient(direction, color-stops)`
- **Radial**: `radial-gradient(shape, color-stops)`
- **Color stops**: Percentage or pixel values where colors change

---

## Shadows

CSS box-shadow adds depth and dimension to elements. You can create multiple shadows and even inset shadows.

### Box-Shadow Syntax:

`box-shadow: h-offset v-offset blur spread color inset;`

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>box-shadow</title>
    <style>
      div {
        margin: 50px;
        width: 300px;
        height: 300px;
        background-color: aqua;
        box-shadow: 5px 5px 5px 0px lightseagreen inset, 5px 5px 3px lightblue;
      }
    </style>
  </head>
  <body>
    <div></div>
  </body>
</html>
```

### Shadow Parameters:

- **h-offset**: Horizontal shadow position
- **v-offset**: Vertical shadow position
- **blur**: Blur radius (optional)
- **spread**: Shadow size (optional)
- **color**: Shadow color
- **inset**: Inner shadow (optional)

---

## Combinators

CSS combinators define relationships between selectors, allowing you to target elements based on their position relative to other elements.

### Types of Combinators:

- **Adjacent Sibling** (`+`): Selects immediate next sibling
- **General Sibling** (`~`): Selects all following siblings
- **Child** (`>`): Direct children only
- **Descendant** (space): All descendants

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Combinators</title>
    <style>
      * {
        margin: 0;
      }
      div {
        background-color: bisque;
        padding: 20px;
      }
      h2 {
        color: blue;
      }
      header {
        background-color: beige;
        padding: 20px;
      }
      h2 ~ p {
        font-weight: bold;
        color: violet;
      }
      h2 + p {
        color: green;
      }
    </style>
  </head>
  <body>
    <header>
      <p>Not a subsequent sibling</p>
      <h2>This is a heading</h2>
      <p>This is a paragraph</p>
      <p>This is a paragraph</p>
      <p>This is a paragraph</p>
    </header>
    <div>
      <h2>Another heading</h2>
      <article>
        <p>Lorem ipsum dolor sit amet...</p>
      </article>
    </div>
  </body>
</html>
```

### Combinator Effects:

- `h2 + p`: Only the first paragraph after h2 turns green
- `h2 ~ p`: All paragraphs after h2 become violet and bold

---

## Attribute Selectors

Attribute selectors target elements based on their attributes and values, making them perfect for form styling.

### Attribute Selector Syntax:

- `[attribute]`: Has the attribute
- `[attribute="value"]`: Exact value match
- `[attribute^="value"]`: Starts with value
- `[attribute$="value"]`: Ends with value
- `[attribute*="value"]`: Contains value

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Attribute Selector</title>
    <style>
      form {
        padding: 20px;
      }
      input {
        margin: 5px;
        box-sizing: border-box;
      }
      input[type="email"],
      input[type="password"] {
        height: 25px;
        width: 150px;
        border-radius: 30px;
        border: 1px solid black;
        padding-left: 10px;
      }
      input[type="submit"] {
        height: 25px;
        width: 150px;
        background-color: brown;
        border: none;
        border-radius: 10px;
      }
    </style>
  </head>
  <body>
    <form>
      <input type="email" placeholder="Enter your email" /><br />
      <input type="password" placeholder="Enter your password" /><br />
      <input type="submit" value="SIGN IN" />
    </form>
  </body>
</html>
```

### Use Cases:

- Form input styling
- Link targeting (external vs internal)
- File type identification

---

## Pseudo Classes

Pseudo-classes target elements in specific states or positions, adding interactivity and dynamic styling.

### Common Pseudo-Classes:

- `:hover`: Mouse over state
- `:active`: Click state
- `:focus`: Input focus state
- `:visited`: Visited links
- `:first-child`, `:last-child`: Position-based
- `:nth-child()`: Nth position
- `:valid`, `:invalid`: Form validation states
- `input:focus:invalid`: Combine

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Pseudo-classes</title>
    <style>
      * {
        margin: 0;
        box-sizing: border-box;
      }
      a {
        margin: 10px;
        width: 250px;
        text-align: center;
        display: inline-block;
        text-decoration: none;
        color: white;
        text-transform: uppercase;
        background-color: tomato;
        padding: 1em;
        border-radius: 10px;
        font-weight: 600;
      }
      a:hover {
        background-color: aqua;
        color: black;
        border: 1px solid brown;
      }
      a:visited {
        background-color: blueviolet;
      }
      a:active {
        background-color: black;
      }
      input:focus {
        background-color: #ccc;
        outline: none;
        border: none;
      }
      input:invalid {
        border: 1px solid red;
      }
      input:valid {
        border: 1px solid green;
      }
      input[type="checkbox"]:checked + span {
        text-decoration: line-through;
        color: #ddd;
      }
      li:first-child {
        border: 2px solid black;
      }
      li:last-child {
        border: 2px solid blue;
      }
      li:nth-child(5) {
        background-color: orange;
      }
      li:nth-child(2n) {
        background-color: grey;
      }
    </style>
  </head>
  <body>
    <a href="#">This is a link</a>
    <input type="email" />
    <input type="checkbox" />
    <span>Todo-Element</span>
    <ol>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
      <li>This is a list-item</li>
    </ol>
  </body>
</html>
```

### Advanced Selectors:

- `:nth-child(2n)`: Every even child
- `:nth-child(odd)`: Every odd child
- `:checked + span`: Sibling element after checked checkbox

---

## Transitions

CSS transitions create smooth animations between property changes, enhancing user experience with fluid motion.

### Transition Properties:

- `transition-property`: Which property to animate
- `transition-duration`: How long the animation takes
- `transition-timing-function`: Animation curve
- `transition-delay`: Delay before animation starts

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Transitions</title>
    <style>
      div {
        height: 300px;
        width: 300px;
        background-color: brown;
        transition: 800ms ease-in-out;
      }
      div:hover {
        width: 460px;
        height: 460px;
      }
    </style>
  </head>
  <body>
    <div></div>
  </body>
</html>
```

### Timing Functions:

- `ease`: Slow start, fast middle, slow end
- `linear`: Constant speed
- `ease-in-out`: Slow start and end
- `cubic-bezier()`: Custom curves

---

# Positioning

CSS positioning controls how elements are placed and behave on a webpage. There are five main position values: `static`, `relative`, `absolute`, `fixed`, and `sticky`.

## 1. Position: Static (Default)

Elements with `position: static` follow the normal document flow. They cannot be moved using `top`, `right`, `bottom`, or `left` properties.

```css
.static-element {
  position: static;
  /* top, right, bottom, left have no effect */
}
```

```html
<div class="static-element">I'm in normal document flow</div>
```

## 2. Position: Relative

Elements with `position: relative` remain in the normal document flow but can be offset from their original position using `top`, `right`, `bottom`, or `left`.

```css
.relative-element {
  position: relative;
  top: 20px;
  left: 30px;
  background-color: lightblue;
}
```

```html
<div class="relative-element">I'm offset from my original position</div>
```

**Key Points:**

- Element still occupies its original space in the document flow
- Other elements are not affected by the offset
- Creates a positioning context for absolutely positioned children

## 3. Position: Absolute

Elements with `position: absolute` are removed from the normal document flow and positioned relative to their nearest positioned ancestor (or the viewport if none exists).

```css
.container {
  position: relative; /* Creates positioning context */
  width: 300px;
  height: 200px;
  border: 2px solid #333;
}

.absolute-element {
  position: absolute;
  top: 50px;
  right: 20px;
  background-color: lightcoral;
  width: 100px;
  height: 50px;
}
```

```html
<div class="container">
  <div class="absolute-element">I'm absolutely positioned</div>
</div>
```

**Key Points:**

- Removed from document flow (doesn't affect other elements)
- Positioned relative to nearest positioned ancestor
- Can overlap other elements

## 4. Position: Fixed

Elements with `position: fixed` are positioned relative to the viewport and remain in the same position even when scrolling.

```css
.fixed-element {
  position: fixed;
  top: 10px;
  right: 10px;
  background-color: lightgreen;
  padding: 10px;
  z-index: 1000;
}
```

```html
<div class="fixed-element">I stay in place while scrolling</div>
```

**Key Points:**

- Always positioned relative to the viewport
- Stays in place during scrolling
- Removed from document flow
- Common for navigation bars, modals, or floating buttons

## 5. Position: Sticky

Elements with `position: sticky` act like `relative` until they reach a specified scroll position, then become `fixed`.

```css
.sticky-element {
  position: sticky;
  top: 0;
  background-color: lightyellow;
  padding: 10px;
  border-bottom: 2px solid #333;
}
```

```html
<div class="content">
  <div class="sticky-element">I stick to the top when scrolling</div>
  <p>Lots of content here...</p>
</div>
```

**Key Points:**

- Hybrid between `relative` and `fixed`
- Sticks when reaching the specified threshold
- Must specify at least one of: `top`, `right`, `bottom`, or `left`
- Perfect for sticky headers or sidebars

## Complete Example

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .demo-container {
        height: 150px;
        border: 2px dashed #ccc;
        position: relative;
        margin: 20px 0;
      }

      .relative-demo {
        position: relative;
        top: 20px;
        left: 50px;
        background: lightblue;
        padding: 10px;
      }

      .absolute-demo {
        position: absolute;
        top: 10px;
        right: 10px;
        background: lightcoral;
        padding: 10px;
      }

      .fixed-demo {
        position: fixed;
        bottom: 20px;
        right: 20px;
        background: lightgreen;
        padding: 10px;
        z-index: 100;
      }

      .sticky-demo {
        position: sticky;
        top: 0;
        background: lightyellow;
        padding: 10px;
        border-bottom: 2px solid #333;
      }
    </style>
  </head>
  <body>
    <div class="demo-container">
      <div class="relative-demo">Relative Position</div>
      <div class="absolute-demo">Absolute Position</div>
    </div>

    <div class="fixed-demo">Fixed Position</div>

    <div style="position: relative">
      <div class="sticky-demo">Sticky Header 1</div>
      <p>lorem-1000</p>
    </div>
    <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
    <div style="position: relative">
      <div class="sticky-demo">Sticky Header 2</div>
      <p>lorem-1000</p>
    </div>
    <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
  </body>
</html>
```

---

# Pseudo Elements

Pseudo elements allow you to style specific parts of an element or insert content without adding extra HTML. They use double colons (`::`) in modern CSS.

## What are Pseudo Elements?

Pseudo elements create virtual elements that don't exist in your HTML but can be styled with CSS. They're perfect for adding decorative content, styling specific parts of text, or creating visual effects.

## Common Pseudo Elements

### 1. ::before and ::after

These create virtual elements before or after an element's content. They require the `content` property to be visible.

```css
.quote::before {
  content: '"';
  font-size: 2em;
  color: #666;
}

.quote::after {
  content: '"';
  font-size: 2em;
  color: #666;
}
```

```html
<p class="quote">This is a quoted text</p>
<!-- Renders as: "This is a quoted text" -->
```

### 2. ::first-line

Styles the first line of text in a block element.

```css
.article::first-line {
  font-weight: bold;
  color: #333;
  font-size: 1.2em;
}
```

```html
<p class="article">
  This first line will be styled differently. The rest of the paragraph will
  have normal styling.
</p>
```

### 3. ::first-letter

Styles the first letter of the first line in a block element.

```css
.drop-cap::first-letter {
  font-size: 3em;
  float: left;
  line-height: 1;
  margin-right: 5px;
  color: #c0392b;
}
```

```html
<p class="drop-cap">
  This paragraph has a decorative first letter that stands out.
</p>
```

### 4. ::selection

Styles the portion of text selected by the user.

```css
::selection {
  background-color: #3498db;
  color: white;
}

/* Firefox compatibility */
::-moz-selection {
  background-color: #3498db;
  color: white;
}
```

```html
<p>Try selecting this text to see the custom selection style!</p>
```

### 5. ::placeholder

Styles placeholder text in input fields.

```css
input::placeholder {
  color: #999;
  font-style: italic;
  opacity: 0.8;
}
```

```html
<input type="text" placeholder="Enter your name here" />
```

## Complete Example

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .demo-container {
        max-width: 600px;
        margin: 20px auto;
        padding: 20px;
        font-family: Arial, sans-serif;
      }

      /* First letter styling */
      .drop-cap::first-letter {
        font-size: 3em;
        float: left;
        line-height: 1;
        margin-right: 8px;
        color: #e74c3c;
        font-weight: bold;
      }

      /* Quote styling */
      .quote {
        font-style: italic;
        margin: 20px 0;
        position: relative;
        display: inline;
      }

      .quote::before,
      .quote::after {
        content: '"';
        font-size: 2em;
        color: #3498db;
        position: absolute;
      }

      .quote::before {
        left: -20px;
        top: -10px;
      }

      .quote::after {
        right: -20px;
        top: -10px;
      }

      /* Custom selection */
      ::selection {
        background: #f39c12;
        color: white;
      }

      /* Placeholder styling */
      input::placeholder {
        color: #95a5a6;
        font-style: italic;
      }

      input {
        padding: 10px;
        border: 2px solid #bdc3c7;
        border-radius: 4px;
        width: 100%;
        margin: 10px 0;
        outline: none;
      }
    </style>
  </head>
  <body>
    <div class="demo-container">
      <p class="drop-cap">
        This paragraph demonstrates the first-letter pseudo element. Notice how
        the first letter is styled differently from the rest. Lorem ipsum dolor
        sit amet, consectetur adipisicing elit. Consequatur perspiciatis commodi
        tenetur nam praesentium nisi quasi laudantium autem aliquid temporibus?
        Tempore ullam voluptatibus nemo ipsam magnam necessitatibus, iure earum
        accusantium.
      </p>

      <p class="quote">
        This is a quoted text that shows before and after pseudo elements.
      </p>

      <input
        type="text"
        placeholder="Try typing here and see the placeholder style"
      />

      <p>
        Try selecting any text on this page to see custom selection styling!
      </p>
    </div>
  </body>
</html>
```

```html
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      h1 {
        position: relative;
        display: inline;
      }
      h1::after {
        content: "";
        position: absolute;
        top: 100%;
        left: 50%;
        transform: translateX(-50%);
        width: 0%;
        height: 2px;
        background: blue;
        transition: all 1s ease-in-out;
      }
      h1:hover::after {
        width: 100%;
      }
    </style>
  </head>
  <body>
    <h1>HOme</h1>
  </body>
</html>
```

---

## Popup/Modal Design

Modern web applications often require modal dialogs or popups. This example shows how to create a centered modal with overlay.

### Key Techniques:

- **Fixed positioning** for overlay and modal
- **Transform translate** for perfect centering
- **Z-index** for layering
- **Viewport units** for full-screen overlay

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Accept Cookies</title>
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      html {
        font-family: Arial, Helvetica, sans-serif;
      }
      body {
        padding: 50px;
      }
      #popup {
        background: white;
        width: 300px;
        border-radius: 6px;
        text-align: center;
        padding: 1.5em;
        position: fixed;
        top: 50%;
        left: 50%;
        translate: -50% -50%;
        z-index: 6;
      }
      #popup button {
        margin-top: 10px;
        padding: 0.6em 2.5em;
        font: inherit;
      }
      #overlay {
        background-color: rgba(0, 0, 0, 0.3);
        height: 100vh;
        width: 100vw;
        position: fixed;
        top: 0;
        left: 0;
        z-index: 5;
      }
    </style>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit...</p>

    <div id="popup">
      <h2>Accept Cookies</h2>
      <button>Yes</button>
      <button>No</button>
    </div>
    <div id="overlay"></div>
  </body>
</html>
```

### Centering Technique:

```css
position: fixed;
top: 50%;
left: 50%;
translate: -50% -50%;
```

### Z-Index Layering:

- Background content: default (0)
- Overlay: 5
- Modal: 6 (highest)

---

## Flexbox Layout

### Overview

Flexbox is a one-dimensional layout method that allows you to arrange items in rows or columns. It's perfect for creating responsive layouts and aligning content efficiently.

### Key Flexbox Concepts

**Flex Container Properties:**

- `display: flex` - Creates a flex container
- `justify-content` - Controls horizontal alignment
- `align-items` - Controls vertical alignment
- `flex-wrap` - Controls whether items wrap to new lines
- `gap` - Sets spacing between flex items

**Common Values:**

- `justify-content: center, flex-start, flex-end, space-between, space-around`
- `align-items: center, flex-start, flex-end, stretch`

### Example Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Flexbox Layout</title>
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      body {
        box-sizing: border-box;
        min-height: 100vh;
        padding: 20px;
        background-color: #0f1016;
        color: white;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      .flex-layout {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 20px;
      }
      .container {
        width: min(350px, 100%);
        box-sizing: border-box;
        background-color: #191a20;
        border: 3px solid #4b4c55;
        border-radius: 10px;
        box-shadow: 0 5px 5px rgba(0, 0, 0, 0.1);
        padding: 30px;
      }
      h2 {
        font-size: 2rem;
      }
      p {
        margin-top: 10px;
      }
    </style>
  </head>
  <body>
    <div class="flex-layout">
      <div class="container">
        <h2>Hello World</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem cumque
          recusandae excepturi deleniti, necessitatibus repellat ab at dicta
          quia debitis, illo libero, vero magni suscipit veritatis. Laboriosam
          illum facere earum!
        </p>
      </div>
      <div class="container">
        <h2>Hello World</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem cumque
          recusandae excepturi deleniti, necessitatibus repellat ab at dicta
          quia debitis, illo libero, vero magni suscipit veritatis. Laboriosam
          illum facere earum!
        </p>
      </div>
      <div class="container">
        <h2>Hello World</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem cumque
          recusandae excepturi deleniti, necessitatibus repellat ab at dicta
          quia debitis, illo libero, vero magni suscipit veritatis. Laboriosam
          illum facere earum!
        </p>
      </div>
      <div class="container">
        <h2>Hello World</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem cumque
          recusandae excepturi deleniti, necessitatibus repellat ab at dicta
          quia debitis, illo libero, vero magni suscipit veritatis. Laboriosam
          illum facere earum!
        </p>
      </div>
    </div>
  </body>
</html>
```

### Key Features in This Example:

- **Centering**: Body uses flexbox to center content both horizontally and vertically
- **Responsive Cards**: Cards wrap to new lines when screen space is limited
- **Modern Styling**: Dark theme with subtle shadows and rounded corners
- **Gap Property**: Provides consistent spacing between cards

---

## Grid Layout

CSS Grid is a two-dimensional layout system that allows you to create complex layouts with rows and columns. It's perfect for creating bento-box style layouts and precise positioning.

## Key Grid Concepts

### Grid Container Properties

- `display: grid` - Creates a grid container
- `grid-template-columns` - Defines column sizes
- `grid-template-rows` - Defines row sizes
- `gap` - Sets spacing between grid items (shorthand for `row-gap` and `column-gap`)
- `grid-template-areas` - Defines named grid areas for easier item placement

### Grid Item Properties

- `grid-row` - Specifies which rows an item spans
- `grid-column` - Specifies which columns an item spans
- `grid-area` - Names a grid area for easier positioning

---

## Alignment Properties

### Container-Level Alignment

These properties are applied to the **grid container** and affect the positioning of all grid items.

#### `justify-items` (Horizontal Alignment of Items)

Controls how grid items are aligned horizontally **within their grid cells**.

- **`stretch`** (default) - Items stretch to fill the entire width of the cell
- **`start`** - Items align to the left edge of the cell
- **`end`** - Items align to the right edge of the cell
- **`center`** - Items align to the center of the cell

```css
.grid-container {
  display: grid;
  justify-items: center; /* Centers all items horizontally in their cells */
}
```

#### `align-items` (Vertical Alignment of Items)

Controls how grid items are aligned vertically **within their grid cells**.

- **`stretch`** (default) - Items stretch to fill the entire height of the cell
- **`start`** - Items align to the top edge of the cell
- **`end`** - Items align to the bottom edge of the cell
- **`center`** - Items align to the center of the cell

```css
.grid-container {
  display: grid;
  align-items: center; /* Centers all items vertically in their cells */
}
```

#### `place-items` (Shorthand)

A shorthand for setting both `align-items` and `justify-items`.

```css
.grid-container {
  place-items: center; /* Centers items both vertically and horizontally */
  /* Equivalent to: align-items: center; justify-items: center; */
}

.grid-container {
  place-items: start end; /* align-items: start; justify-items: end; */
}
```

---

#### `justify-content` (Horizontal Alignment of Grid)

Controls how the **entire grid** is aligned horizontally within the container (when grid is smaller than container).

- **`start`** - Grid aligns to the left
- **`end`** - Grid aligns to the right
- **`center`** - Grid aligns to the center
- **`stretch`** - Grid stretches to fill the container width
- **`space-between`** - Equal space between columns, no space at edges
- **`space-around`** - Equal space around columns
- **`space-evenly`** - Equal space between and around columns

```css
.grid-container {
  display: grid;
  grid-template-columns: 100px 100px 100px;
  width: 500px;
  justify-content: center; /* Centers the entire grid horizontally */
}
```

#### `align-content` (Vertical Alignment of Grid)

Controls how the **entire grid** is aligned vertically within the container (when grid is smaller than container).

- **`start`** - Grid aligns to the top
- **`end`** - Grid aligns to the bottom
- **`center`** - Grid aligns to the center
- **`stretch`** - Grid stretches to fill the container height
- **`space-between`** - Equal space between rows, no space at edges
- **`space-around`** - Equal space around rows
- **`space-evenly`** - Equal space between and around rows

```css
.grid-container {
  display: grid;
  grid-template-rows: 100px 100px;
  height: 400px;
  align-content: center; /* Centers the entire grid vertically */
}
```

#### `place-content` (Shorthand)

A shorthand for setting both `align-content` and `justify-content`.

```css
.grid-container {
  place-content: center; /* Centers the grid both ways */
  /* Equivalent to: align-content: center; justify-content: center; */
}
```

---

### Item-Level Alignment

These properties are applied to **individual grid items** and override container-level alignment.

#### `justify-self` (Individual Horizontal Alignment)

Controls how a specific item is aligned horizontally within its cell.

- **`stretch`** (default)
- **`start`** - Align to left
- **`end`** - Align to right
- **`center`** - Align to center

```css
.grid-item {
  justify-self: end; /* This item aligns to the right */
}
```

#### `align-self` (Individual Vertical Alignment)

Controls how a specific item is aligned vertically within its cell.

- **`stretch`** (default)
- **`start`** - Align to top
- **`end`** - Align to bottom
- **`center`** - Align to center

```css
.grid-item {
  align-self: start; /* This item aligns to the top */
}
```

#### `place-self` (Shorthand)

A shorthand for setting both `align-self` and `justify-self`.

```css
.grid-item {
  place-self: center; /* Centers this item in its cell */
  /* Equivalent to: align-self: center; justify-self: center; */
}
```

---

### Example 1: Basic Bento Grid

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Grid - Bento Layout</title>
    <style>
      body {
        text-align: center;
        align-content: center;
      }
      .bento-grid {
        display: grid;
        grid-template-columns: 250px 250px 250px;
        grid-template-rows: 250px 250px;
        gap: 10px;
      }
      .box {
        background-color: #0071ff;
      }
      #item-1 {
        grid-row: 1 / 3; /* Spans from row 1 to row 3 */
      }
      #item-4 {
        grid-column: 2 / 4; /* Spans from column 2 to column 4 */
      }
    </style>
  </head>
  <body>
    <div class="bento-grid">
      <div id="item-1" class="box"></div>
      <div id="item-2" class="box"></div>
      <div id="item-3" class="box"></div>
      <div id="item-4" class="box"></div>
      <div id="item-5" class="box"></div>
      <div id="item-6" class="box"></div>
      <div id="item-7" class="box"></div>
      <div id="item-8" class="box"></div>
      <div id="item-9" class="box"></div>
      <div id="item-10" class="box"></div>
    </div>
  </body>
</html>
```

### Example 2: Grid Areas (Advanced)

**HTML:**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Grid Areas Layout</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div style="grid-area: box-1" class="box">1</div>
    <div style="grid-area: box-2" class="box">2</div>
    <div style="grid-area: box-3" class="box">3</div>
    <div style="grid-area: box-4" class="box">4</div>
    <div style="grid-area: box-5" class="box">5</div>
    <div style="grid-area: box-6" class="box">6</div>
    <div style="grid-area: box-7" class="box">7</div>
    <div style="grid-area: box-8" class="box">8</div>
    <div style="grid-area: box-9" class="box">9</div>
  </body>
</html>
```

**CSS (style.css):**

```css
body {
  display: grid;
  grid-template-areas:
    "box-1 box-2 box-3"
    "box-4 box-5 box-6"
    "box-7 box-8 box-9";
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(3, 200px);
  gap: 10px;
  padding: 20px;
}

.box {
  background-color: #4caf50;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2rem;
  color: white;
  border-radius: 8px;
}
```

### Grid vs Flexbox: When to Use What

**Use Flexbox when:**

- Creating one-dimensional layouts (row or column)
- Aligning items within a container
- Building navigation bars, cards, or simple responsive layouts

**Use Grid when:**

- Creating two-dimensional layouts (rows and columns)
- Building complex page layouts
- Creating bento-box or dashboard-style interfaces
- Need precise control over item positioning

### Advanced Grid Features

**Fractional Units (fr):**

- `1fr` means "take up 1 fraction of available space"
- `repeat(3, 1fr)` creates 3 equal columns

**Auto-sizing:**

- `auto-fit` and `auto-fill` for responsive grids
- `minmax()` function for flexible sizing

**Example of Responsive Grid:**

```css
.responsive-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}
```

This creates a grid that automatically adjusts the number of columns based on available space, with each column being at least 300px wide.

---

# Media Query Example Guide

This guide demonstrates how to use CSS media queries to create responsive designs that adapt to different screen sizes.

## HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Media Query Example</title>
    <style>
      /* CSS goes here */
    </style>
  </head>
  <body>
    <div class="box"></div>
    <p>Resize your browser window to see the box change:</p>
    <ul>
      <li>Desktop (769px+): Blue, 200x200px</li>
      <li>Tablet (768px and below): Green, 150x150px</li>
      <li>Mobile (600px and below): Red, 100x100px</li>
    </ul>
  </body>
</html>
```

## CSS with Media Queries

### Base Styles (Desktop)

```css
.box {
  width: 200px;
  height: 200px;
  background-color: blue;
  margin: 20px;
}
```

### Tablet Styles (768px and below)

```css
@media screen and (max-width: 768px) {
  .box {
    background-color: green;
    width: 150px;
    height: 150px;
  }
}
```

### Mobile Styles (600px and below)

```css
@media screen and (max-width: 600px) {
  .box {
    background-color: red;
    width: 100px;
    height: 100px;
  }
}
```

### Print

```css
@media print {
  .box {
    background-color: black !important;
    color: white;
  }
  /* Hide navigation, ads, etc. */
  .no-print {
    display: none;
  }
}
```

## Breakpoints Explained

| Device Type | Screen Width | Box Color | Box Size  |
| ----------- | ------------ | --------- | --------- |
| Desktop     | 769px+       | Blue      | 200x200px |
| Tablet      | ≤768px       | Green     | 150x150px |
| Mobile      | ≤600px       | Red       | 100x100px |

## Key Points

1. **Media Query Syntax**: `@media screen and (max-width: XXXpx)`
2. **Cascading**: Smaller screens inherit styles from larger breakpoints, then override specific properties
3. **Mobile-First vs Desktop-First**: This example uses desktop-first approach (starts with desktop styles, then overrides for smaller screens)
4. **Viewport Meta Tag**: Essential for responsive design - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

---

# CSS Variables and Theming Guide

## What are CSS Variables?

CSS Variables (also called CSS Custom Properties) are a powerful feature that allows you to store values in reusable variables. They're perfect for creating dynamic themes because you can change multiple properties at once by updating just the variable values.

## Basic Syntax

```css
/* Define variables */
:root {
  --variable-name: value;
}

/* Use variables */
.element {
  property: var(--variable-name);
}
```

## How Theming Works

### 1. Define Theme Variables

Variables are typically defined in the `:root` pseudo-class, making them globally available:

```css
:root {
  --bg-primary: #ffffff;
  --text-primary: #212529;
  --accent-color: #007bff;
}
```

### 2. Create Theme Variants

Use attribute selectors to override variables for different themes:

```css
[data-theme="dark"] {
  --bg-primary: #212529;
  --text-primary: #f8f9fa;
  --accent-color: #0d6efd;
}
```

### 3. Apply Variables to Elements

Use `var()` function to apply variables to CSS properties:

```css
body {
  background-color: var(--bg-primary);
  color: var(--text-primary);
}
```

## Theme Switching

Themes are typically switched by changing the `data-theme` attribute on the body or html element:

```javascript
// Switch to dark theme
document.body.setAttribute("data-theme", "dark");

// Switch to light theme
document.body.setAttribute("data-theme", "light");
```

## Complete Example

```html
<!DOCTYPE html>
<html lang="en" data-theme="light">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Variables Theming Demo</title>
    <style>
      /* Theme Variables */
      :root {
        --bg-primary: #ffffff;
        --text-primary: #000000;
      }

      /* Dark theme */
      [data-theme="dark"] {
        --bg-primary: #000000;
        --text-primary: #ffffff;
      }

      /* Styles */
      body {
        background-color: var(--bg-primary);
      }
      h1 {
        color: var(--text-primary);
      }
      button {
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <h1>Hello</h1>
    <button onclick="toggleTheme()">Switch Theme</button>

    <script>
      function toggleTheme() {
        const html = document.documentElement;
        const light = html.getAttribute("data-theme") === "light";
        html.setAttribute("data-theme", light ? "dark" : "light");
      }
    </script>
  </body>
</html>
```

---

# Animation with Keyframes

## What are Keyframes?

Keyframes define the start and end points of smooth transitions in animations. They tell the browser what styles to apply at specific moments during an animation.

## Basic Syntax

```css
@keyframes animation-name {
  from {
    /* starting styles */
  }
  to {
    /* ending styles */
  }
}
```

Or using percentages:

```css
@keyframes animation-name {
  0% {
    /* starting styles */
  }
  50% {
    /* middle styles */
  }
  100% {
    /* ending styles */
  }
}
```

## Simple Examples

### 1. Fade In Animation

```css
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

.fade-element {
  animation: fadeIn 2s ease-in;
}
```

### 2. Slide Right Animation

```css
@keyframes slideRight {
  0% {
    transform: translateX(-100px);
  }
  100% {
    transform: translateX(0);
  }
}

.slide-element {
  animation: slideRight 1s ease-out;
}
```

### 3. Color Change Animation

```css
@keyframes colorChange {
  0% {
    background-color: red;
  }
  50% {
    background-color: yellow;
  }
  100% {
    background-color: green;
  }
}

.color-box {
  animation: colorChange 3s infinite;
}
```

### 4. Bounce Animation

```css
@keyframes bounce {
  0%,
  100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-30px);
  }
}

.bounce-ball {
  animation: bounce 1s ease-in-out infinite;
}
```

### 5. Rotate Animation

```css
@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.spinner {
  animation: rotate 2s linear infinite;
}
```

## Animation Properties

- `animation-name`: The keyframe name
- `animation-duration`: How long the animation takes (e.g., 2s, 500ms)
- `animation-timing-function`: Speed curve (ease, linear, ease-in, ease-out)
- `animation-delay`: How long the animation waits (e.g., 2s, 500ms)
- `animation-iteration-count`: How many times to repeat (1, 3, infinite)
- `animation-direction`: Direction of animation (normal, reverse, alternate)

## Shorthand Example

```css
.element {
  animation: slideRight 1s ease-out 0.5s infinite alternate;
  /*         name duration timing delay iteration direction */
}
```

## Key Points

- Use `from` and `to` for simple start/end animations
- Use percentages (0%, 25%, 50%, 100%) for complex multi-step animations
- Multiple properties can change simultaneously in one keyframe
- Animations can be paused, reversed, and repeated
- Always name your keyframes descriptively

## Quick HTML Example

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      @keyframes pulse {
        0% {
          transform: scale(1);
        }
        50% {
          transform: scale(1.1);
        }
        100% {
          transform: scale(1);
        }
      }

      .button {
        animation: pulse 2s infinite;
        padding: 10px 20px;
        background: blue;
        color: white;
        border: none;
        border-radius: 5px;
      }
    </style>
  </head>
  <body>
    <button class="button">Pulsing Button</button>
  </body>
</html>
```

This creates a button that continuously pulses by scaling up and down.

---

# Multi Page Website Build Guide

This guide will walk you through creating a complete multi-page website with modern styling and navigation. The project includes a home page, about page, products page, and login page.

## Project Overview

**Final Structure:**

```
project-folder/
├── index.html
├── about.html
├── products.html
├── login.html
└── style.css
```

**Features:**

- Responsive navigation bar
- Modern gradient design
- Video embedding
- Product showcase
- Login form
- Consistent styling across all pages

---

## Project Setup

### Create Project Folder

```bash
mkdir my-website
cd my-website
```

### Create Base Files

Create these empty files in your project folder:

- `index.html`
- `about.html`
- `products.html`
- `login.html`
- `style.css`

---

## Step 1: Basic HTML Structure + Global CSS

### HTML Structure (for all pages)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Home</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Content will go here -->
  </body>
</html>
```

### Corresponding CSS (Global Setup)

```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

* {
  margin: 0;
  padding: 0;
}

html {
  text-align: center;
  font-family: Poppins, "Segoe UI", sans-serif;
}
```

---

## Step 2: Navigation Bar

### HTML Chunk (add to body of each page)

```html
<nav>
  <a href="index.html" class="active">Home</a>
  <a href="about.html">About</a>
  <a href="products.html">Products</a>
  <a href="login.html">Login</a>
</nav>
```

### Corresponding CSS

```css
nav {
  position: fixed;
  top: 0;
  width: 100%;
  padding: 25px;
  border-bottom: 2px solid #e3e3e3;
}

nav a {
  text-decoration: none;
  color: #929292;
  margin: 0 20px;
}

nav a:hover {
  color: black;
}

nav a.active {
  color: black;
}
```

**Test this step:** Open your HTML file and verify the navigation appears at the top with hover effects.

---

## Step 3: Basic Header Container

### HTML Chunk (add after nav)

```html
<header>
  <!-- Page content will go here -->
</header>
```

### Corresponding CSS

```css
header {
  padding-top: calc(50px + 1rem + 2px);
}
```

**Why this CSS:** The padding-top accounts for the fixed navigation bar height.

---

## Step 4: Main Heading (Home Page)

### HTML Chunk (inside header)

```html
<h1>
  This will be a great<br />
  slogan for your product
</h1>
```

### Corresponding CSS

```css
h1 {
  margin-top: 100px;
  font-size: 3.75rem;
  font-weight: bold;
  line-height: 1.2em;
}
```

**Test this step:** Your heading should now appear large and bold with proper spacing.

---

## Step 5: Description Paragraph (Home Page)

### HTML Chunk (add after h1)

```html
<p>
  Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime quibusdam, eum
  sunt aliquid laborum dicta perspiciatis recusandae reprehenderit laboriosam
  accusamus dolorem libero, deleniti, enim voluptatibus pariatur ipsam culpa
  distinctio porro fuga modi. Voluptas quasi, maiores eveniet ea corrupti esse
  voluptatem.
</p>
```

### Corresponding CSS

```css
h1 + p {
  width: 800px;
  margin: 35px auto;
}
```

**Why this CSS:** The `h1 + p` selector targets only paragraphs immediately after h1 elements.

---

## Step 6: Call-to-Action Button (Home Page)

### HTML Chunk (add after paragraph)

```html
<a href="login.html" id="cta-button">Try now for free</a>
```

### Corresponding CSS

```css
#cta-button {
  text-decoration: none;
  text-transform: uppercase;
  color: white;
  background: linear-gradient(to right, #d786ff, #722cff);
  display: inline-block;
  padding: 1em 3em;
  font-weight: 600;
  border-radius: 1000px;
  transition: 150ms ease;
}

#cta-button:hover {
  scale: 1.1;
}
```

**Test this step:** Your button should have a purple gradient and scale up on hover.

---

## Step 7: Video Player (About Page)

### HTML Chunk (in about.html header)

```html
<h1>About</h1>
<iframe
  class="video-player"
  src="https://www.youtube.com/embed/PL3Odw-k8W4?si=LsP-K-EvKn7-q4HD"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen
>
</iframe>
```

### Corresponding CSS

```css
.video-player {
  margin-top: 30px;
  width: min(1100px, 100%);
  aspect-ratio: 16 / 9;
  border-radius: 15px;
}
```

**Test this step:** The video should display with rounded corners and proper aspect ratio.

---

## Step 8: Products Container (Products Page)

### HTML Chunk (in products.html header)

```html
<h1>Products</h1>
<div class="products-container">
  <!-- Individual items will go here -->
</div>
```

### Corresponding CSS

```css
.products-container {
  margin-top: 30px;
}
```

---

## Step 9: Product Items (Products Page)

### HTML Chunk (inside products-container)

```html
<div class="item">
  <h2>Item 1</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium, esse.
    Eveniet consequatur harum rem dolore, fugiat error laudantium impedit
    repellendus
  </p>
</div>
<div class="item">
  <h2>Item 2</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium, esse.
    Eveniet consequatur harum rem dolore, fugiat error laudantium impedit
    repellendus
  </p>
</div>
<div class="item">
  <h2>Item 3</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium, esse.
    Eveniet consequatur harum rem dolore, fugiat error laudantium impedit
    repellendus
  </p>
</div>
```

### Corresponding CSS

```css
.item {
  box-sizing: border-box;
  width: 300px;
  height: 300px;
  display: inline-block;
  margin: 0 20px;
  margin-bottom: 20px;
  align-content: center;
  padding: 20px;
  border-radius: 30px;
}

.item > h2 {
  margin-bottom: 10px;
}

.item:first-child {
  border: 1px solid black;
}

.item:nth-child(2) {
  background-color: #7932ff;
  color: white;
}

.item:last-child {
  background-color: black;
  color: white;
}
```

**Test this step:** You should see three product cards with different styling - bordered, purple, and black.

---

## Step 10: Login Form (Login Page)

### HTML Chunk (in login.html header)

```html
<h1>Login</h1>
<form action="">
  <input type="text" placeholder="Username" />
  <input type="password" placeholder="Password" />
  <input type="submit" value="Login" />
</form>
```

### Corresponding CSS

```css
form {
  margin-top: 30px;
}

input {
  display: block;
  margin: 0 auto;
  margin-bottom: 15px;
  font: inherit;
  border-radius: 30px;
}

input[type="text"],
input[type="password"] {
  padding: 5px 20px;
  width: 400px;
  height: 50px;
  border: none;
  background-color: #ebedf5;
}

input[type="submit"] {
  width: 200px;
  padding: 10px;
  background-color: #0071ff;
  color: white;
  font-weight: 600;
  border: none;
}
```

**Test this step:** Your form should have rounded input fields and a blue submit button.

---

# Portfolio Website

A comprehensive guide to building a professional responsive mobile first portfolio website from scratch using HTML and CSS.

### Project Structure:

```text
project/
├── index.html
├── css/
│   ├── globals.css
│   ├── common.css
│   ├── sidebar.css
│   ├── hero.css
│   ├── about.css
│   ├── work-count.css
│   ├── skills.css
│   └── contact.css
└── images/
    ├── profile.png
    ├── bg.jpg
    └── photo.jpg
```

---

### Project Setup & Global Styles

#### HTML Setup

Create `index.html` with basic structure:

```html
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bidur Sapkota - Portfolio</title>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Quicksand:wght@300;400;500;600;700&display=swap"
      rel="stylesheet"
    />

    <!-- Font Awesome -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    />

    <!-- Stylesheets -->
    <link rel="stylesheet" href="css/globals.css" />
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html>
```

#### CSS - globals.css

Create `css/globals.css`:

```css
html {
  scroll-behavior: smooth;
}

body {
  font-family: "Quicksand", sans-serif;
  margin: unset;
}

a {
  text-decoration: none;
}

h1,
h2,
h3,
p {
  all: unset;
  display: block;
}

ul,
li {
  all: unset;
}
```

---

### Hero Section

#### HTML

Add after the sidebar `</nav>`:

```html
<section id="hero">
  <h1 class="hero__job">
    Hi! <br />
    I am Bidur, <br />
    Full Stack Developer
  </h1>
  <h2 class="hero__edu">Electronics, Communication and Information Engineer</h2>
  <button class="hero__btn">Download CV <i class="fa fa-download"></i></button>
</section>
```

#### CSS - hero.css

Create `css/hero.css`:

Add to `index.html` head:

```html
<link rel="stylesheet" href="css/hero.css" />
```

```css
#hero {
  background-color: #efe7ec;
  background-image: url("../images/photo.jpg");
  background-repeat: no-repeat;
  background-position: right bottom;
  background-size: contain;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0 30px;
}
.hero__job {
  font-family: "Playfair Display", serif;
  font-size: 28px;
  line-height: 1.3;
  font-weight: 700;
  margin-bottom: 20px;
}

.hero__edu {
  font-family: "Quicksand", sans-serif;
  line-height: 1.5;
  margin-bottom: 50px;
  font-weight: 300;
  color: black;
}

.hero__btn {
  width: 300px;
  font-size: 12px;
  letter-spacing: 2px;
  font-weight: normal;
  padding: 10px 15px;
  text-transform: uppercase;
  font-family: "Quicksand", sans-serif;
  border-radius: 2px;
  border: 1px solid black;
  cursor: pointer;
  background-color: transparent;
}
```

---

### About Section

#### HTML

Add after hero section:

```html
<section id="about" class="section">
  <span class="section__title">about us</span>
  <h2 class="section__subtitle">who am i?</h2>

  <p class="about__description">
    <strong>Hi! I am Your Name</strong>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum, sint
    dolorem. Animi nemo officia dolores harum.
  </p>

  <p class="about__description">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius soluta
    laudantium, illo iusto aliquid recusandae.
  </p>

  <div class="about__skills">
    <div class="about__box">
      <i class="fa-solid fa-ear-listen"></i>
      <h3>Graphic design</h3>
    </div>
    <div class="about__box">
      <i class="fa-solid fa-globe"></i>
      <h3>web design</h3>
    </div>
    <div class="about__box">
      <i class="fa-solid fa-database"></i>
      <h3>Software</h3>
    </div>
    <div class="about__box">
      <i class="fa-solid fa-mobile"></i>
      <h3>application</h3>
    </div>
  </div>

  <div class="about__happy">
    <h2>I am happy to know you that 300+ projects done successfully!</h2>
    <button>hire me</button>
  </div>
</section>
```

---

#### About Section - CSS Styling

#### Reusable Section Styles

#### CSS - common.css

Create `css/common.css`:

Add to `index.html` head:

```html
<link rel="stylesheet" href="css/common.css" />
```

```css
.section {
  margin-top: 100px;
  padding: 15px;
}

.section__title {
  display: block;
  margin-bottom: 15px;
  font-size: 10px;
  text-transform: uppercase;
  color: #999999;
  font-weight: 500;
  letter-spacing: 5px;
}

.section__subtitle {
  margin-bottom: 45px;
  font-size: 18px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 5px;
  line-height: 1.8;
  color: black;
  font-family: "Playfair Display", serif;
}
```

#### Non-Reusable Section Styles

#### CSS - about.css

Create `css/about.css`:

Add to `index.html` head:

```html
<link rel="stylesheet" href="css/about.css" />
```

```css
.about__description {
  font-family: "Quicksand", sans-serif;
  font-weight: normal;
  line-height: 1.8;
  color: rgba(0, 0, 0, 0.7);
  font-size: 16px;
  margin-bottom: 10px;
}

.about__description:last-of-type {
  margin-bottom: 40px;
}

.about__box {
  color: #fff;
  border-bottom: 2px solid #2c98f0;
  padding: 24px;
  box-shadow: 0px 0px 56px -8px rgba(0, 0, 0, 0.17);
  margin-bottom: 50px;
}

.about__box > i {
  margin-bottom: 20px;
  color: #2c98f0;
  font-size: 30px;
}

.about__box > h3 {
  font-size: 16px;
  font-family: "Quicksand", sans-serif;
  font-weight: 500;
  color: #000;
  margin-bottom: 30px;
  text-transform: capitalize;
}

.about__box:nth-child(2) {
  border-color: #ec5453;
}

.about__box:nth-child(2) > i {
  color: #ec5453;
}

.about__box:nth-child(3) {
  border-color: #f9bf3f;
}

.about__box:nth-child(3) > i {
  color: #f9bf3f;
}

.about__box:last-child {
  border-color: #a84cb8;
}

.about__box:last-child > i {
  color: #a84cb8;
}

.about__happy {
  padding: 30px;
  background: #f9bf3f;
}

.about__happy > h2 {
  font-family: "Playfair Display", serif;
  color: black;
  font-weight: normal;
  margin-bottom: 30px;
  line-height: 1.5;
  font-size: 30px;
}

.about__happy > button {
  font-family: "Quicksand", sans-serif;
  font-size: 16px;
  font-weight: normal;
  color: #000;
  text-transform: uppercase;
  letter-spacing: 1px;
  border: 1px solid black;
  padding: 2px 10px;
  background: transparent;
}
```

---

### Work Statistics Section

#### HTML

Add after about section:

```html
<section id="work__count">
  <span>309</span>
  <span>cups of coffee</span>
  <span>356</span>
  <span>projects</span>
  <span>30</span>
  <span>clients</span>
  <span>10</span>
  <span>partners</span>
</section>
```

#### CSS - work-count.css

Create `css/work-count.css`:

Add to `index.html` head:

```html
<link rel="stylesheet" href="css/work-count.css" />
```

```css
#work__count {
  background-image: url("../images/bg.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  padding: 70px 15px;
  margin-top: 100px;
  position: relative;
}

#work__count::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.4);
  z-index: 0;
}

#work__count > span {
  display: block;
  text-align: center;
  z-index: 1;
  position: relative;
}

#work__count > :nth-child(odd) {
  font-size: 40px;
  font-family: "Quicksand", sans-serif;
  font-weight: 700;
  margin-bottom: 20px;
  color: white;
}

#work__count > :nth-child(even) {
  font-size: 14px;
  letter-spacing: 5px;
  text-transform: uppercase;
  font-family: "Quicksand", sans-serif;
  font-weight: normal;
  margin-bottom: 40px;
  color: rgba(255, 255, 255, 0.7);
}
```

---

### Skills Section

#### HTML

Add after work count section:

```html
<section id="skills" class="section">
  <span class="section__title">my speciality</span>
  <span class="section__subtitle">my skills</span>

  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt maiores
    ducimus id consequatur? Natus obcaecati.
  </p>

  <div class="skill__box">
    <div class="skill">
      <span>Photoshop</span>
      <div class="skill__percent__box">
        <div class="skill__percent">
          <span>75%</span>
        </div>
      </div>
    </div>

    <div class="skill">
      <span>React Js</span>
      <div class="skill__percent__box">
        <div
          class="skill__percent"
          style="width: 60%; background: #ec5453; color: #ec5453"
        >
          <span>60%</span>
        </div>
      </div>
    </div>

    <div class="skill">
      <span>HTML5</span>
      <div class="skill__percent__box">
        <div
          class="skill__percent"
          style="width: 85%; background: #f9bf3f; color: #f9bf3f"
        >
          <span>85%</span>
        </div>
      </div>
    </div>

    <div class="skill">
      <span>CSS3</span>
      <div class="skill__percent__box">
        <div
          class="skill__percent"
          style="width: 90%; background: #a84cb8; color: #a84cb8"
        >
          <span>90%</span>
        </div>
      </div>
    </div>

    <div class="skill">
      <span>Wordpress</span>
      <div class="skill__percent__box">
        <div
          class="skill__percent"
          style="width: 70%; background: #2fa499; color: #2fa499"
        >
          <span>70%</span>
        </div>
      </div>
    </div>

    <div class="skill">
      <span>SEO</span>
      <div class="skill__percent__box">
        <div
          class="skill__percent"
          style="width: 80%; background: #4054b2; color: #4054b2"
        >
          <span>80%</span>
        </div>
      </div>
    </div>
  </div>
</section>
```

---

#### CSS - skills.css

Create `css/skills.css`:

Add to `index.html` head:

```html
<link rel="stylesheet" href="css/skills.css" />
```

```css
#skills > p {
  font-family: "Quicksand", sans-serif;
  color: rgba(0, 0, 0, 0.7);
  font-weight: normal;
  line-height: 1.8;
  margin-top: 50px;
  margin-bottom: 15px;
}

.skill {
  margin-bottom: 20px;
}

.skill > span {
  font-size: 16px;
  font-family: "Quicksand", sans-serif;
  margin-bottom: 10px;
  color: black;
  font-weight: normal;
  display: block;
}

.skill__percent__box {
  background: #f2f3f7;
  border-radius: 8px;
}

.skill__percent {
  width: 75%;
  height: 6px;
  background: #2c98f0;
  border-radius: 8px;
  position: relative;
  color: #2c98f0;
}

.skill__percent::after {
  content: "";
  position: absolute;
  right: 0;
  top: -2px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: inherit;
}

.skill__percent > span {
  position: absolute;
  top: -22px;
  right: 0;
  color: inherit;
  font-size: 12px;
  line-height: 1.2;
  font-weight: 600;
}
```

---

### Contact Form Section

#### HTML

Add after skills section:

```html
<section id="contact" class="section">
  <span class="section__title">get in touch</span>
  <h2 class="section__subtitle">contact</h2>

  <form
    action=""
    id="contactForm"
    class="contact__form"
    onsubmit="submitForm(event);"
  >
    <input
      type="text"
      placeholder="Name"
      id="name"
      name="name"
      class="contact__input"
    />
    <textarea
      id="message"
      class="contact__textarea"
      name="message"
      placeholder="Message"
      rows="4"
    ></textarea>
    <button class="contact__button" type="submit">Send Message</button>
  </form>
</section>
```

#### CSS - contact.css

Create `css/contact.css`:

Add to `index.html` head:

```html
<link rel="stylesheet" href="css/contact.css" />
```

```css
.contact__input,
.contact__textarea {
  height: 54px;
  width: 100%;
  font-family: "Quicksand", serif;
  font-size: 16px;
  font-weight: normal;
  padding: 10px 20px;
  line-height: 1.4;
  margin-bottom: 15px;
  background-color: #f2f3f7;
  border: none;
  outline: none;
}

.contact__textarea {
  resize: vertical;
  height: 130px;
}

.contact__button {
  cursor: pointer;
  background: #2c98f0;
  color: #fff;
  margin-bottom: 100px;
  font-size: 12px;
  text-transform: uppercase;
  font-weight: normal;
  font-family: "Quicksand", sans-serif;
  letter-spacing: 1px;
  border-radius: 2px;
  padding: 8px 15px;
  border: none;
}
```

---

### Sidebar Navigation - HTML Structure

#### HTML

Add before closing `</body>` tag:

```html
<nav class="sidebar">
  <div class="sidebar__hamburger" id="hamburger">
    <div class="sidebar__hamburger__lines">
      <div class="sidebar__hamburger__line"></div>
      <div class="sidebar__hamburger__line"></div>
      <div class="sidebar__hamburger__line"></div>
    </div>
  </div>

  <div class="sidebar__content">
    <img class="sidebar__image" src="images/profile.png" alt="Profile Image" />
    <h1 class="sidebar__name">Bidur Sapkota</h1>
    <h2 class="sidebar__job">Developer <span>in Nepal</span></h2>

    <ul class="sidebar__list">
      <a href="#hero" class="sidebar__list__item">home</a>
      <a href="#about" class="sidebar__list__item">about</a>
      <a href="#skills" class="sidebar__list__item">skills</a>
      <a href="#contact" class="sidebar__list__item">contact</a>
    </ul>

    <p class="sidebar__copyright">
      &copy; 2024 All rights reserved | Made with &#128150 by <span>Bidur</span>
    </p>
  </div>
</nav>
```

- HTML entities (&copy;), there are others too. Search HTML entities in google.
- Search html emoji codes for heart emoji and other emojis.

---

#### CSS - sidebar.css

Create `css/sidebar.css`:

Add to `index.html` head:

```html
<link rel="stylesheet" href="css/sidebar.css" />
```

```css
.sidebar__hamburger {
  padding: 30px 15px;
  position: fixed;
  top: 0;
  left: 0;
  cursor: pointer;
  transition-duration: 500ms;
  z-index: 50;
}

.sidebar__hamburger__translate {
  transform: translateX(300px);
}

.sidebar__hamburger__lines {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 30px;
  height: 15px;
}

.sidebar__hamburger__line {
  width: 30px;
  height: 2px;
  background: #000;
}

.sidebar__content {
  width: 300px;
  height: 100vh;
  background: #f2f3f7;
  position: fixed;
  top: 0;
  left: -300px; /* initially 0 for dev*/
  overflow-y: scroll;
  transition-duration: 500ms;
  display: flex;
  flex-direction: column;
  align-items: center;
  z-index: 50;
}

.sidebar__hamburger__translate + .sidebar__content {
  transform: translateX(300px);
}

.sidebar__image {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 50%;
  margin-top: 50px;
  margin-bottom: 30px;
}

.sidebar__name {
  font-size: 22px;
  color: black;
  margin-bottom: 7.5px;
  font-family: "Playfair Display", serif;
  font-weight: bold;
  text-transform: capitalize;
}

.sidebar__job {
  font-size: 12px;
  font-weight: normal;
  color: #2c98f0;
  text-transform: uppercase;
}

.sidebar__job > span {
  color: rgba(0, 0, 0, 0.7);
}

.sidebar__list {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 30px;
  margin-bottom: 50px;
}

.sidebar__list__item {
  font-size: 12px;
  letter-spacing: 1px;
  padding: 2px;
  margin-bottom: 10px;
  text-transform: uppercase;
  color: rgba(0, 0, 0, 0.7);
  position: relative;
  cursor: pointer;
}

.sidebar__list__item::after {
  content: "";
  width: 0px;
  height: 1px;
  background: #2c98f0;
  position: absolute;
  top: calc(100% + 2px);
  left: 50%;
  transform: translateX(-50%);
  transition: all ease 0.2s;
}

.sidebar__list__item:hover::after {
  width: 120%;
}

.sidebar__copyright {
  padding: 0 20px;
  margin-bottom: 30px;
  color: rgba(0, 0, 0, 0.5);
  text-align: center;
  font-size: 12px;
  line-height: 2;
}

.sidebar__copyright > span {
  color: #2c98f0;
}
```

---

#### Sidebar JavaScript Functionality

Add before closing `</body>` tag:

```html
<script>
  const hamburger = document.getElementById("hamburger");
  hamburger.addEventListener("click", () => {
    hamburger.classList.toggle("sidebar__hamburger__translate");
  });
</script>
```

### Responsive Design

Update about.css

```css
/* ....... */
/* ....... */
@media screen and (min-width: 768px) {
  .about__skills {
    display: flex;
    justify-content: space-between;
    gap: 30px;
  }
  .about__box {
    flex-grow: 1;
  }
}
```

Update skills.css

```css
@media screen and (min-width: 768px) {
  .skill__box {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
  }
}
```

Update sidebar.css

```css
@media screen and (min-width: 768px) {
  body {
    margin-left: 300px;
  }
  .sidebar__hamburger {
    display: none;
  }
  .sidebar__content {
    left: 0 !important;
    transform: unset !important; /*edge case for mobile to desktop mode switch, while sidebar visible*/
  }
}
```
