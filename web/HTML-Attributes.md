# HTML Attributes

**Date:** 2025-12-01
**Tags:** #HTML #Attributes #Frontend #WebDevelopment
**Back to ->** [README](../README.md) or [HTML Fundamentals](./HTML-Fundamentals.md)

## 1. Definition
An **attribute** is a special value used to adjust the behavior or appearance of an HTML element. Attributes provide additional information about elements.

* They are always specified in the **opening tag**.
* **Syntax:** `name="value"`

## 2. Common Attributes
Here are some of the most frequently used attributes to configure elements:

* **`src` (Source):**
    * Used to specify the location (URL) for the source of an image (`<img>`).
* **`alt` (Alternative Text):**
    * Used in `<img>` elements.
    * **Best Practice:** Always include descriptive text for accessibility (screen readers) and in case the image fails to load.
* **`href` (Hypertext Reference):**
    * Specifies the destination URL of a link (`<a>`).
* **`target`:**
    * Specifies where to open the linked document (e.g., `_blank` for a new tab).
* **`type`:**
    * Specifies the type of `<input>` element to display (e.g., text, password, checkbox).

---

## 3. Input Type Options
The `type` attribute defines how an input field behaves.

* **`text`:** Defines a standard single-line text input.
* **`checkbox`:** Defines a checkbox allowing users to select zero or more options of a limited number of choices.

---

## 4. Boolean Attributes (Special Syntax)
**Definition:** Boolean attributes represent a state (True/False). If the attribute is present in the tag, the value is considered **True**. They do not require a value assigned to them.

### Examples of Boolean Attributes:
* **`checked`:** Specifies that an input element (like a checkbox) should be pre-selected when the page loads.
* **`disabled`:** Specifies that the element is unusable and un-clickable.
* **`readonly`:** Specifies that an input field is read-only (content cannot be changed by the user).
* **`required`:** Specifies that an input field must be filled out before submitting the form.

### Syntax Example:
```html
<input type="text" required>
<input type="checkbox" checked disabled>
