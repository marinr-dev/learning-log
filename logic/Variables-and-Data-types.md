# Variables and Data Types

**Date:** 2025-11-29
**Tags:** #Logic #Fundamentals #Variables #DataTypes
**Back to ->** [README](../README.md) or [Tools for the Course](./Tools-for-the-Course.md)

## 1. Definitions
### What is a Variable?
A **variable** is a named storage location in the computer's memory used to hold a value.
* Think of it as a **box** where you store data.
* The content of this box **can change** during the execution of the program.
### What is a Data Type?
A **data type** defines the kind of value a variable can hold and what operations can be performed on it (e.g., you can multiply numbers, but you cannot multiply text).

---
## 2. Common Data Types
Here are the standard data types used in programming logic:

| Type | Description | Examples | Standard Default Value |
| :--- | :--- | :--- | :--- |
| **Integer (Int)** | Whole numbers without decimals. | `1`, `-5`, `42` | `0` |
| **Float / Real** | Numbers with decimal points. | `3.14`, `1.5`, `-0.01` | `0.0` |
| **String** | A sequence of characters (text). | `"Hello"`, `"Code"` | `""` (Empty string) or `Null` |
| **Character (Char)** | A single letter, digit, or symbol. | `'a'`, `'@'`, `'1'` | `'\0'` (Null char) |
| **Boolean** | Logical values (True or False). | `True`, `False` | `False` |

> **Note:** Strings and Chars are usually enclosed in quotes. Python accepts both single `' '` and double `" "` quotes.

---
## 3. Naming Conventions (Identifiers)
An **identifier** is the name we give to variables, functions, or constants.

**Rules & Best Practices:**
1.  Must start with a **letter** or an **underscore** (`_`).
2.  Should be **descriptive** (e.g., `userAge` is better than `x`).
3.  Case sensitivity matters (`age` is not the same as `Age`).
### Casing Styles
* **snake_case:** Words separated by underscores. Used in **Python** variables.
    * *Example:* `user_name`, `items_count`
* **camelCase:** First word lowercase, subsequent words capitalized. Used in **Java/JavaScript**.
    * *Example:* `userName`, `itemsCount`
* **PascalCase:** Every word capitalized. Used for **Classes**.
    * *Example:* `UserProfile`, `GameController`

---
## 4. Constants
A **constant** is a type of variable whose value **cannot change** once assigned.

* **Convention:** We use **UPPER_SNAKE_CASE** (All uppercase with underscores).
* *Example:* `PI = 3.1416`, `MAX_LIVES = 3`

---
## 5. Typing Systems & Concepts

### Declaration vs. Initialization
* **Declaration:** Telling the computer "I need a variable named X of type Y".
* **Initialization:** Giving the variable its first value.
* **Hard Coding:** Embedding data directly into the source code rather than obtaining it from external sources or user input.
    * *Example:* Writing `tax = 0.19` is hard coding. Reading the tax from a database is not.
### Dynamic vs. Static Typing
This refers to how the language handles data types.

1.  **Statically Typed (e.g., C++, Java):**
    * You **must** specify the data type when declaring the variable.
    * *Example:* `int age = 20;`
2.  **Dynamically Typed (e.g., Python, JavaScript):**
    * You **do not** need to specify the data type. The language infers it from the value.
    * *Example:* `age = 20` (Python knows it's an integer).

---
## Code Examples
* [Variables](./Variables.psc)
* [Variables2](./Variables2.psc)
* [Tipos de Datos/Data Types](./TiposDatos.psc)
* [Reglas y Mejores Prácticas/Rules and Best Practices](./ReglasNombres.psc)
* [Constantes/Constants](./Constantes.psc)
* [Ejemplo/Example](./EjercicioDatos.psc)
