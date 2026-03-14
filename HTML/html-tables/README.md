# HTML Tables

HTML **Tables** are used to organize and display data in rows and columns on a webpage. Tables are useful for presenting structured information like schedules, employee data, product lists, and reports.

---

## Basic Table

A **basic table** is created using the `<table>` tag.
Each row is defined using `<tr>` and each cell using `<td>`.

### Example

```html
<table border="1">
    <tr>
        <td>Name</td>
        <td>role</td>
    </tr>
    <tr>
        <td>Sai</td>
        <td>Frontend Developer</td>
    </tr>
    <tr>
        <td>Rahul</td>
        <td>Backend Developer</td>
    </tr>
</table>
```

---

## Table with Head, Body, and Footer

HTML tables can be structured using:

* `<thead>` – Table header
* `<tbody>` – Table body
* `<tfoot>` – Table footer

This helps organize the table content clearly.

### Example

```html
<table border="2">
    <thead>
        <tr>
            <th>Item</th>
            <th>Quantity</th>
            <th>Price</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Apple</td>
            <td>10</td>
            <td>$1.00</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td>Total</td>
            <td>15</td>
            <td>$2.50</td>
        </tr>
    </tfoot>
</table>
```

---

## Colgroup and Column Styling

The `<colgroup>` and `<col>` tags allow styling specific columns in a table.

### Example

```html
<colgroup>
    <col style="background-color: lightyellow;">
    <col>
    <col style="background-color: lightblue;">
</colgroup>
```

This example changes the background color of selected columns.

---

## Table Caption

The `<caption>` tag is used to give a title or description to a table.

### Example

```html
<table>
    <caption>Employee Details</caption>
</table>
```

---

## Colspan Attribute

The **`colspan` attribute** allows a table cell to span across multiple columns.

### Example

```html
<th colspan="2">Contact Info</th>
```

This merges two columns into one cell.

---

## Rowspan Attribute

The **`rowspan` attribute** allows a table cell to span across multiple rows.

### Example

```html
<td rowspan="2">Row1 Cell1</td>
```

This merges two rows into one cell.

---

## Live Output

You can view the output of the **HTML Tables page** here:

```
https://visweshwarreddypemmana.github.io/web-development-learning/HTML/html-tables/
```

Or click the link below:

[**View HTML Tables Output**](https://visweshwarreddypemmana.github.io/web-development-learning/HTML/html-tables/)

This link shows the **rendered webpage of the `index.html` file** hosted using **GitHub Pages**.

---
