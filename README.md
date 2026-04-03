```markdown
# HTML and HTML5 Basics

This repository introduces the **fundamental concepts and tags of HTML and HTML5** used to structure and present content on the web.

---

## 📌 Core Concepts

### HTML
**HTML (HyperText Markup Language)** is the standard language used to structure web pages.

- The `<html>` tag is the **root element** of an HTML page.
- All other elements (except `<!DOCTYPE>`) must be inside this element.
- It wraps the **entire content** of the document.

**Usage:**  
Tells the browser that the document is an HTML file.

---

### HTML5
**HTML5** is the **fifth and current major version** of HTML.  
It introduces improved **semantic structure, multimedia support, and better accessibility**.

---

# 🏗️ Document Structure Tags

## `<head>`
A container for **metadata** (data about the document).

Content inside this tag **is not displayed** on the web page but provides instructions for browsers and search engines.

**Common elements inside `<head>`**

- Scripts
- Stylesheets
- Character encoding
- Page title
- Metadata

---

## `<title>`
Defines the **title of the document**.

Displayed in:

- Browser tab
- Bookmark title
- Search engine results

**Importance:**  
Important for **SEO (Search Engine Optimization)** and **accessibility**.

---

## `<body>`
Contains **all visible content** of the webpage.

Examples of elements placed inside `<body>`:

- Text
- Images
- Hyperlinks
- Tables
- Lists
- Forms

⚠️ Only **one `<body>` element** can exist per page.

---

## `<meta>`
Defines metadata that cannot be represented by other HTML elements.

Placed inside the `<head>` section.

### Common Uses

| Attribute | Description |
|----------|-------------|
| `charset` | Defines character encoding (usually UTF-8) |
| `viewport` | Controls page display on mobile devices |
| `description` | Provides a summary for search engines |

---

# 📝 Text and Content Tags

| Tag | Description |
|----|-------------|
| `<h1>` - `<h6>` | Heading tags (largest to smallest) |
| `<p>` | Paragraph |
| `<br>` | Line break |
| `<hr>` | Thematic line divider |
| `<b>` | Bold text without extra importance |
| `<strong>` | Indicates strong importance (semantic) |
| `<i>` | Italic text (alternate voice or mood) |

---

# 📋 List Tags

| Tag | Description |
|----|-------------|
| `<li>` | List item |
| `<ol>` | Ordered list |
| `<ul>` | Unordered list |

---

# 🔗 Links and Media

| Tag | Description |
|----|-------------|
| `<a>` | Anchor tag (hyperlink) |
| `<img>` | Image element |

---

# 📊 Table Tags

| Tag | Description |
|----|-------------|
| `<table>` | Table container |
| `<tr>` | Table row |
| `<td>` | Table data cell |
| `<th>` | Table header cell |

---

# 📦 Container Elements

| Tag | Description |
|----|-------------|
| `<div>` | Generic block container |
| `<span>` | Generic inline container |

---

# 🧠 Semantic HTML5 Elements

Semantic elements describe the **meaning of the content**.

| Tag | Description |
|----|-------------|
| `<header>` | Header content of a page |
| `<footer>` | Footer content |
| `<nav>` | Navigation links |
| `<article>` | Independent content (blog post, news article) |
| `<section>` | Thematic section of content |
| `<aside>` | Related but secondary content |
| `<main>` | Main content of the document |

---

# 📝 Forms

## `<form>`
Used to collect **user input**.

### Common Input Types

- `text`
- `email`
- `url`
- `date`
- `radio`
- `password`
- `number`

---

# 🔐 Form Methods

| Method | Description |
|------|-------------|
| **GET** | Sends form data through the URL (visible in browser address bar) |
| **POST** | Sends data securely inside the request body |

---

# ⚙️ Scripts

## `<script>`

Used to embed or reference **client-side JavaScript**.

Example uses:

- Interactive features
- Form validation
- Dynamic content updates

---

# 📚 Additional HTML5 Elements

| Tag | Description |
|----|-------------|
| `<details>` | Defines additional information that users can show/hide |
| `<summary>` | Visible heading for a `<details>` element |
| `<dialog>` | Defines a dialog box or popup window |
| `<data>` | Provides a machine-readable value for content |

---

# 📖 Summary

HTML and HTML5 provide the **foundation of every web page**.  
Learning these core tags helps developers:

- Structure web content
- Improve accessibility
- Optimize pages for search engines
- Build maintainable websites
```
