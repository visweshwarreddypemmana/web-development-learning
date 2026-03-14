# HTML Lists

HTML Lists are used to organize and display related items in a structured format on a webpage. Lists help make content easier to read and understand.

---

## Unordered List

An **unordered list** displays items with bullet points. The order of the items does not matter.

### Example

```html
<ul>
    <li>India</li>
    <li>USA</li>
    <li>England</li>
</ul>
````

---

## Ordered List

An **ordered list** displays items with numbers or letters. The order of the items is important.

### Example

```html
<ol>
    <li>India</li>
    <li>USA</li>
    <li>England</li>
</ol>
```

---

## Nested Unordered List

A **nested list** is a list placed inside another list. It helps represent hierarchical data.

### Example

```html
<ul>
    <li>India
        <ul type="square">
            <li>Delhi</li>
            <li>Mumbai</li>
            <li>Andhra Pradesh</li>
        </ul>
    </li>
</ul>
```

---

## Nested Ordered List

Ordered lists can also be nested to create sub-items.

### Example

```html
<ol type="A">
    <li>India
        <ol type="a">
            <li>Delhi</li>
            <li>Mumbai</li>
            <li>Andhra Pradesh</li>
        </ol>
    </li>
</ol>
```

---

## Ordered List Types

The **type attribute** changes the numbering style.

Common values include:

* **1** – Numbers (default)
* **A** – Uppercase letters
* **a** – Lowercase letters
* **I** – Uppercase Roman numerals
* **i** – Lowercase Roman numerals

### Example

```html
<ol type="A">
    <li>India</li>
    <li>USA</li>
    <li>England</li>
</ol>
```

---

## Start Attribute

The **start attribute** begins the list from a specific number.

### Example

```html
<ol start="3">
    <li>India</li>
    <li>USA</li>
    <li>England</li>
</ol>
```

---

## Value Attribute

The **value attribute** sets the number of a specific list item manually.

### Example

```html
<ol start="3">
    <li>India</li>
    <li value="5">USA</li>
    <li>England</li>
</ol>
```

---

## Reversed Ordered List

The **reversed attribute** displays the list in descending order.

### Example

```html
<ol reversed>
    <li>India</li>
    <li>USA</li>
    <li>England</li>
</ol>
```

---

## Description List

A **description list** is used to display terms and their descriptions.

It uses three tags:

* `<dl>` – Description List
* `<dt>` – Description Term
* `<dd>` – Description Definition

### Example

```html
<dl>
    <dt>India</dt>
    <dd>Capital: Delhi</dd>

    <dt>USA</dt>
    <dd>Capital: Washington D.C.</dd>

    <dt>England</dt>
    <dd>Capital: London</dd>
</dl>
```

---

## Live Output

You can view the output of the **HTML Lists page** here:

[https://visweshwarreddypemmana.github.io/web-development-learning/HTML/html-lists/](https://visweshwarreddypemmana.github.io/web-development-learning/HTML/html-lists/)

Or click the link below:

[**View HTML Lists Output**](https://visweshwarreddypemmana.github.io/web-development-learning/HTML/html-basic-elements/)

This link shows the **rendered webpage of the `index.html` file** hosted using **GitHub Pages**.

---
