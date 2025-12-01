# HTML Fundamentals

**Date:** 2025-12-01
**Tags:** #HTML #Frontend #WebDevelopment
**Back to ->** [README](../README.md)

## 1. What is HTML?
**HTML** stands for **HyperText Markup Language**.
It is the standard markup language used to define the **structure** and **content** of a webpage.

### The Role of HTML
* It represents the content and logical structure of the document.
* HTML is made up of **elements**.
* Most elements use opening and closing tags (syntax: `<tag>` and `</tag>`).

---

## 2. Common HTML Elements

Here is a list of essential elements used to build a page:

* **`<h1>` (Main Heading):**
    * Represents the most important section.
    * **Rule:** There should only be **one** `<h1>` element per page.
* **`<h2>` to `<h6>` (Subheadings):**
    * These expose the hierarchy of the document. `<h2>` is the second most important, down to `<h6>` (least important).
    * Unlike `<h1>`, you can have multiple of these per page.
* **`<p>` (Paragraph):**
    * Used to add a block of text to a webpage.
* **`<input>`:**
    * Used to collect data from users (e.g., text fields).
* **`<a>` (Anchor):**
    * Used to define hyperlinks to other pages or locations.

---

## 3. Void Elements
**Definition:** Void elements are HTML elements that **do not have a closing tag** and cannot contain any content text inside them.

* **Examples:** `<input>`, `<img>`, `<br>`, `<hr>`.

---

## 4. Good Practices
To write professional and clean HTML code:

* **Lowercase Tags:** Although HTML tag names are case-insensitive (e.g., `<H1>` works the same as `<h1>`), it is an industry standard best practice to write all tags in **lowercase**.

---

## 5. Is HTML Enough?
**Question:** Can a website be built using HTML alone?

**Answer:**
Technically, yes, but it is not sufficient for modern web development. HTML only provides the **structure** and raw content. Without other technologies, the page will have no style and no interactivity.

* **HTML:** Structure.
* **CSS:** Style and Layout.
* **JavaScript:** Interactivity and Logic.

**Next step ->** [HTML Attributes](./HTML-Attributes.md)
