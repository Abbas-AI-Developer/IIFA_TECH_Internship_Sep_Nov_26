# HTML Foundation — Day 1 to Day 5

> **Internship:** Iffa Tech
> **Topic:** HTML Foundation
> **Goal:** Build a strong foundation in HTML, forms, media, accessibility, and basic SEO.

---

# Day 1 — Web Basics

## 1. What is the Web?

The **Web (World Wide Web)** is a system that allows us to access websites and web pages through the internet.

When we open a website, the browser sends a request to a server, and the server sends the required files back to the browser.

### Basic Flow

```text
User
  ↓
Browser
  ↓
Internet
  ↓
Web Server
  ↓
Website Files
  ↓
Browser displays the webpage
```

---

## 2. What is a Browser?

A **web browser** is software used to access and display websites.

Examples:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari
* Opera

The browser reads HTML, CSS, and JavaScript and displays the result as a webpage.

---

## 3. Client and Server

### Client

The **client** is usually the user's device or browser that requests information from a server.

Examples:

* Laptop
* Mobile
* Chrome browser

### Server

A **server** is a computer/system that stores website files and processes requests.

For example:

```text
Client → Request → Server
Client ← Response ← Server
```

If you open:

```text
example.com
```

your browser sends a request to the server. The server responds with the website's files.

---

## 4. What is VS Code?

**Visual Studio Code (VS Code)** is a code editor used to write and manage programming files.

It can be used for:

* HTML
* CSS
* JavaScript
* Python
* React
* Node.js
* and many other technologies.

---

## 5. Basic Folder Structure

A simple HTML project can look like this:

```text
my-website/
│
├── index.html
├── style.css
├── script.js
│
└── images/
    └── logo.png
```

### Files

* `index.html` → webpage structure
* `style.css` → webpage design
* `script.js` → webpage behavior
* `images/` → images used in the website

---

# 6. First HTML Page

Create a file called:

```text
index.html
```

Basic HTML:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My First Website</title>
</head>

<body>

    <h1>Hello World</h1>

    <p>This is my first HTML page.</p>

</body>

</html>
```

### Important

`<!DOCTYPE html>` tells the browser that the document uses modern HTML.

---

# Day 2 — HTML Document Structure

## 1. What is HTML?

**HTML stands for HyperText Markup Language.**

HTML is used to create the **structure of a webpage**.

HTML is not a programming language. It is a **markup language**.

---

# 2. Basic HTML Structure

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>My Website</title>

</head>

<body>

    <h1>Welcome</h1>

    <p>Hello World</p>

</body>

</html>
```

---

# 3. `<html>`

The `<html>` element is the root element of an HTML document.

```html
<html>
    
</html>
```

Usually we specify the language:

```html
<html lang="en">
```

---

# 4. `<head>`

The `<head>` contains information about the webpage that is generally not directly displayed as page content.

Example:

```html
<head>

    <meta charset="UTF-8">

    <title>My Website</title>

</head>
```

The head can contain:

* `<title>`
* `<meta>`
* `<link>`
* `<style>`
* `<script>`

---

# 5. `<body>`

The `<body>` contains the visible content of the webpage.

Example:

```html
<body>

    <h1>My Website</h1>

    <p>Welcome to my website.</p>

</body>
```

---

# 6. `<title>`

The `<title>` defines the title of the webpage shown in the browser tab.

```html
<title>Abbas - AI Engineer</title>
```

---

# 7. `<meta>`

`<meta>` provides information about the webpage.

### Character Encoding

```html
<meta charset="UTF-8">
```

This helps the browser correctly display characters.

### Responsive Design

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

This helps webpages work properly on different screen sizes.

---

# 8. Headings

HTML provides six heading levels:

```html
<h1>Main Heading</h1>

<h2>Section Heading</h2>

<h3>Subsection</h3>

<h4>Heading 4</h4>

<h5>Heading 5</h5>

<h6>Heading 6</h6>
```

`<h1>` is the most important heading.

A page should generally have a clear heading structure.

---

# 9. Paragraph

The `<p>` element is used for paragraphs.

```html
<p>
    HTML is used to create the structure of webpages.
</p>
```

---

# 10. Links

The `<a>` element creates hyperlinks.

```html
<a href="https://example.com">Visit Website</a>
```

### Open in New Tab

```html
<a href="https://example.com" target="_blank">
    Visit Website
</a>
```

---

# Day 3 — Lists, Tables and Media

# 1. Ordered List

An ordered list displays numbered items.

```html
<ol>

    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>

</ol>
```

Output:

```text
1. HTML
2. CSS
3. JavaScript
```

---

# 2. Unordered List

An unordered list displays bullet points.

```html
<ul>

    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>

</ul>
```

---

# 3. List Item

`<li>` represents an individual list item.

```html
<li>HTML</li>
```

---

# 4. Tables

Tables are used to display data in rows and columns.

Basic example:

```html
<table>

    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Abbas</td>
        <td>25</td>
    </tr>

</table>
```

### Important Table Elements

* `<table>` → table
* `<tr>` → table row
* `<th>` → table heading
* `<td>` → table data

---

# 5. Images

The `<img>` element displays an image.

```html
<img src="image.jpg" alt="My Profile Image">
```

### Important Attributes

`src` → image location

`alt` → alternative text

Example:

```html
<img
    src="profile.jpg"
    alt="Profile photo of Abbas"
    width="200"
>
```

---

# 6. Audio

The `<audio>` element is used to add audio.

```html
<audio controls>

    <source src="music.mp3" type="audio/mpeg">

</audio>
```

`controls` displays the browser's audio controls.

---

# 7. Video

The `<video>` element is used to display video.

```html
<video width="500" controls>

    <source src="video.mp4" type="video/mp4">

</video>
```

---

# 8. Iframe

An `<iframe>` embeds another webpage or external content inside a webpage.

Example:

```html
<iframe
    src="https://example.com"
    width="600"
    height="400">
</iframe>
```

A common use is embedding maps or videos.

---

# 9. Link Targets

## `_blank`

Opens the link in a new browsing context, commonly a new tab.

```html
<a href="https://example.com" target="_blank">
    Open Website
</a>
```

---

## `_self`

Opens the link in the current browsing context.

```html
<a href="page.html" target="_self">
    Open Page
</a>
```

---

## `_parent`

Opens the link in the parent browsing context.

```html
<a href="page.html" target="_parent">
    Open Page
</a>
```

---

## `_top`

Opens the link in the top-level browsing context.

```html
<a href="page.html" target="_top">
    Open Page
</a>
```

These targets are especially relevant when working with frames/iframes.

---

# Day 4 — HTML Forms

HTML forms are used to collect information from users.

Examples:

* Login forms
* Registration forms
* Contact forms
* Search forms
* Application forms

---

# 1. Basic Form

```html
<form>

    <label for="name">Name:</label>

    <input type="text" id="name" name="name">

    <button type="submit">Submit</button>

</form>
```

---

# 2. Input Types

HTML provides different input types.

### Text

```html
<input type="text">
```

### Password

```html
<input type="password">
```

### Email

```html
<input type="email">
```

### Number

```html
<input type="number">
```

### Date

```html
<input type="date">
```

### Checkbox

```html
<input type="checkbox">
```

### Radio

```html
<input type="radio">
```

### File

```html
<input type="file">
```

### Submit

```html
<input type="submit" value="Submit">
```

---

# 3. Labels

`<label>` provides a description for a form control.

```html
<label for="email">Email:</label>

<input type="email" id="email">
```

The `for` value should match the input's `id`.

This improves usability and accessibility.

---

# 4. Textarea

`<textarea>` allows users to enter multi-line text.

```html
<label for="message">Message:</label>

<textarea id="message" rows="5" cols="30"></textarea>
```

---

# 5. Select

`<select>` creates a dropdown.

```html
<label for="country">Country:</label>

<select id="country">

    <option>Pakistan</option>
    <option>Turkey</option>
    <option>Germany</option>

</select>
```

---

# 6. Fieldset

`<fieldset>` groups related form controls.

```html
<fieldset>

    <legend>Personal Information</legend>

    <label for="name">Name:</label>
    <input type="text" id="name">

    <label for="email">Email:</label>
    <input type="email" id="email">

</fieldset>
```

`<legend>` provides a caption for the fieldset.

---

# 7. Required

The `required` attribute makes a field mandatory.

```html
<input type="text" required>
```

The user must provide a value before submitting the form.

---

# 8. Pattern

The `pattern` attribute allows a form control to require a value matching a specified regular expression.

Example:

```html
<input
    type="text"
    pattern="[A-Za-z]+"
>
```

This example expects alphabetic characters.

---

# 9. Min and Max

These attributes are commonly used with number/date-related inputs.

```html
<input
    type="number"
    min="1"
    max="100"
>
```

The allowed value range is from 1 to 100.

---

# 10. Complete Form Example

```html
<form>

    <fieldset>

        <legend>Registration Form</legend>

        <label for="name">Name:</label>
        <input
            type="text"
            id="name"
            name="name"
            required
        >

        <br><br>

        <label for="email">Email:</label>
        <input
            type="email"
            id="email"
            name="email"
            required
        >

        <br><br>

        <label for="age">Age:</label>
        <input
            type="number"
            id="age"
            name="age"
            min="18"
            max="60"
        >

        <br><br>

        <label for="message">Message:</label>

        <br>

        <textarea
            id="message"
            name="message"
            rows="5">
        </textarea>

        <br><br>

        <button type="submit">Submit</button>

    </fieldset>

</form>
```

---

# Day 5 — Semantic HTML, Accessibility and SEO

# 1. Semantic HTML

Semantic HTML uses elements that clearly describe their meaning and purpose.

Examples:

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

Instead of using only generic `<div>` elements, semantic elements provide meaningful structure.

---

# 2. `<header>`

Used for introductory content or the header of a page/section.

```html
<header>

    <h1>My Website</h1>

</header>
```

---

# 3. `<nav>`

Used for navigation links.

```html
<nav>

    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>

</nav>
```

---

# 4. `<main>`

Contains the main content of the page.

```html
<main>

    <h1>About Me</h1>

    <p>This is the main content.</p>

</main>
```

---

# 5. `<section>`

Groups related content.

```html
<section>

    <h2>My Skills</h2>

    <p>Python, HTML, CSS and JavaScript.</p>

</section>
```

---

# 6. `<article>`

Represents self-contained content.

Examples:

* Blog post
* News article
* Forum post
* Product review

```html
<article>

    <h2>My First Blog Post</h2>

    <p>This is my blog content.</p>

</article>
```

---

# 7. `<aside>`

Contains related or secondary content.

```html
<aside>

    <h3>Related Articles</h3>

</aside>
```

---

# 8. `<footer>`

Contains footer information.

```html
<footer>

    <p>© 2026 Abbas</p>

</footer>
```

---

# 9. Accessibility

**Accessibility** means designing websites so that people with different abilities can use them.

Good accessibility practices include:

* Proper headings
* Labels for form controls
* Alternative text for images
* Keyboard-friendly navigation
* Meaningful link text
* Semantic HTML
* Appropriate ARIA when necessary

---

# 10. Alt Text

The `alt` attribute provides alternative text for an image.

```html
<img
    src="profile.jpg"
    alt="Abbas working on a laptop"
>
```

If the image cannot be displayed, the alternative text can communicate its purpose.

Screen readers can also use the alternative text.

---

# 11. Labels and Accessibility

Always associate labels with form controls where appropriate.

Good:

```html
<label for="email">Email</label>

<input
    type="email"
    id="email"
>
```

The `for` attribute connects the label with the input's `id`.

---

# 12. ARIA Basics

ARIA stands for:

**Accessible Rich Internet Applications**

ARIA attributes can provide additional accessibility information when native HTML semantics are not enough.

Example:

```html
<button aria-label="Close">
    X
</button>
```

Important rule:

> Prefer native HTML elements and semantics first. Use ARIA when it is actually needed.

---

# 13. Data Attributes

Custom data attributes allow developers to store custom information on HTML elements.

They begin with:

```text
data-
```

Example:

```html
<button data-user-id="123">
    View Profile
</button>
```

Another example:

```html
<div
    data-category="AI"
    data-level="beginner">
</div>
```

JavaScript can later access these values.

---

# 14. SEO

SEO stands for:

**Search Engine Optimization**

SEO helps search engines understand and discover webpage content.

Basic HTML practices include:

* Meaningful `<title>`
* Proper headings
* Descriptive content
* Semantic HTML
* Useful link text
* Image `alt` text
* Meta description

---

# 15. SEO Meta Description

Example:

```html
<meta
    name="description"
    content="Learn HTML, CSS and JavaScript with practical web development tutorials."
>
```

The description gives search engines information about the page.

---

# 16. Complete Semantic HTML Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>Abbas - AI Engineer</title>

    <meta
        name="description"
        content="Personal website and portfolio of Abbas, an AI Engineer."
    >

</head>

<body>

    <header>

        <h1>Abbas - AI Engineer</h1>

        <nav>

            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="contact.html">Contact</a>

        </nav>

    </header>

    <main>

        <section>

            <h2>About Me</h2>

            <p>
                I am learning AI Engineering and web development.
            </p>

        </section>

        <section>

            <h2>My Skills</h2>

            <ul>

                <li>Python</li>
                <li>Machine Learning</li>
                <li>HTML</li>

            </ul>

        </section>

        <article>

            <h2>My Learning Journey</h2>

            <p>
                I am building practical projects while learning
                modern technology.
            </p>

        </article>

    </main>

    <footer>

        <p>© 2026 Abbas. All rights reserved.</p>

    </footer>

</body>

</html>
```

---

# Quick Revision — Important HTML Tags

| Tag           | Purpose                           |
| ------------- | --------------------------------- |
| `<html>`      | Root of HTML document             |
| `<head>`      | Metadata and document information |
| `<body>`      | Visible webpage content           |
| `<title>`     | Browser tab title                 |
| `<meta>`      | Metadata                          |
| `<h1>`–`<h6>` | Headings                          |
| `<p>`         | Paragraph                         |
| `<a>`         | Link                              |
| `<img>`       | Image                             |
| `<audio>`     | Audio                             |
| `<video>`     | Video                             |
| `<iframe>`    | Embedded content                  |
| `<ul>`        | Unordered list                    |
| `<ol>`        | Ordered list                      |
| `<li>`        | List item                         |
| `<table>`     | Table                             |
| `<tr>`        | Table row                         |
| `<th>`        | Table heading                     |
| `<td>`        | Table data                        |
| `<form>`      | Form                              |
| `<input>`     | Input field                       |
| `<label>`     | Input label                       |
| `<textarea>`  | Multi-line input                  |
| `<select>`    | Dropdown                          |
| `<option>`    | Dropdown option                   |
| `<fieldset>`  | Groups form controls              |
| `<legend>`    | Fieldset caption                  |
| `<header>`    | Header                            |
| `<nav>`       | Navigation                        |
| `<main>`      | Main content                      |
| `<section>`   | Content section                   |
| `<article>`   | Independent content               |
| `<aside>`     | Related/secondary content         |
| `<footer>`    | Footer                            |

---

# Important Attributes

| Attribute  | Purpose                                       |
| ---------- | --------------------------------------------- |
| `href`     | Link destination                              |
| `src`      | Resource/image location                       |
| `alt`      | Alternative image text                        |
| `id`       | Unique element identifier                     |
| `class`    | Groups elements for styling/JS                |
| `target`   | Controls link browsing context                |
| `required` | Makes input mandatory                         |
| `pattern`  | Specifies a validation pattern                |
| `min`      | Minimum value                                 |
| `max`      | Maximum value                                 |
| `name`     | Identifies form data                          |
| `data-*`   | Stores custom data                            |
| `aria-*`   | Provides additional accessibility information |

---

# Day 1–5 Final Learning Outcome

After completing these five days, I understand:

* Web basics
* Browser and server concepts
* Client/server communication
* VS Code and project structure
* Basic HTML document structure
* Headings and paragraphs
* Links and link targets
* Lists
* Tables
* Images
* Audio and video
* Iframes
* HTML forms
* Input types
* Form validation attributes
* Semantic HTML
* Accessibility basics
* Alt text
* Labels
* ARIA basics
* Data attributes
* SEO meta tags

## Practice Goal

Build a **Personal Portfolio Page** using:

* Semantic HTML
* Navigation
* About section
* Skills section
* Projects section
* Profile image
* Projects table
* Contact form
* Footer
* SEO meta description
* Accessible labels and image alt text

**Status: HTML Foundation Day 1–5 Completed ✅**
