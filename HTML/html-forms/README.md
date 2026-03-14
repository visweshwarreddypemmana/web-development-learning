# HTML Student Registration Form

## HTML Form

An **HTML form** is used to collect user input on a webpage. Forms allow users to enter information such as name, email, gender, and other details. The entered data can be sent to a server for processing.

### Syntax

```
<form action="url" method="post">
    form elements
</form>
```

### Example

```
<form action="/submit" method="post">
</form>
```

Here:

* **action** – specifies where the form data will be sent
* **method** – defines how the data will be sent (`GET` or `POST`)

---

# Student Registration Form

This project creates a **Student Registration Form** using HTML.

The form collects information such as:

* Personal details
* Gender
* Programming languages
* Country
* Skills
* Additional information

---

# Elements Demonstrated in This Code

## Form Tag

The `<form>` tag is used to create a form where users can enter data.

### Example

```
<form action="/submit" method="post">
</form>
```

---

# Fieldset Tag

The `<fieldset>` tag is used to **group related form elements together**.

It helps organize the form into sections.

### Example

```
<fieldset>
    form elements
</fieldset>
```

---

# Legend Tag

The `<legend>` tag provides a **title for the fieldset group**.

### Example

```
<fieldset>
<legend>Personal Information</legend>
</fieldset>
```

---

# Label Tag

The `<label>` tag is used to **describe an input field**.

It improves accessibility and usability.

### Example

```
<label for="name">Name:</label>
```

---

# Input Tag

The `<input>` tag is used to create different types of input fields.

### Example

```
<input type="text">
```

Different types of inputs used in this form include:

* text
* number
* email
* date
* radio
* checkbox
* file
* color
* range

---

# Text Input

The `type="text"` input is used to enter text data such as a name.

### Example

```
<input type="text" placeholder="Enter your name">
```

---

# Number Input

The `type="number"` input allows users to enter numeric values.

### Example

```
<input type="number" min="1" max="100">
```

---

# Email Input

The `type="email"` input ensures the user enters a valid email format.

### Example

```
<input type="email" placeholder="example@gmail.com">
```

---

# Date Input

The `type="date"` input allows users to select a date from a calendar.

### Example

```
<input type="date">
```

---

# Radio Button

Radio buttons allow users to **select only one option from multiple choices**.

### Example

```
<input type="radio" name="gender" value="male">
```

---

# Checkbox

Checkboxes allow users to **select multiple options**.

### Example

```
<input type="checkbox" value="Java">
```

---

# Select Dropdown

The `<select>` tag creates a dropdown list.

### Example

```
<select>
<option>India</option>
<option>USA</option>
</select>
```

Users can select one option from the list.

---

# Datalist

The `<datalist>` element provides **autocomplete suggestions for input fields**.

### Example

```
<input list="skills">

<datalist id="skills">
<option value="HTML">
<option value="CSS">
</datalist>
```

---

# Textarea

The `<textarea>` tag allows users to enter **multiple lines of text**.

### Example

```
<textarea rows="4" cols="40"></textarea>
```

This is useful for descriptions or messages.

---

# File Upload

The `type="file"` input allows users to upload files.

### Example

```
<input type="file">
```

In this form it is used to upload a **resume**.

---

# Color Picker

The `type="color"` input allows users to choose a color.

### Example

```
<input type="color">
```

---

# Range Input

The `type="range"` input creates a **slider to select a value within a range**.

### Example

```
<input type="range" min="0" max="10">
```

---

# Submit Button

The `type="submit"` button sends the form data to the server.

### Example

```
<input type="submit" value="Submit Form">
```

---

# Reset Button

The `type="reset"` button clears all form fields.

### Example

```
<input type="reset" value="Reset Form">
```

---
## Live Output

You can view the output of the **HTML Forms page** here:

```
https://visweshwarreddypemmana.github.io/web-development-learning/HTML/html-forms/
```

Or click the link below:

[**View HTML Forms Output**](https://visweshwarreddypemmana.github.io/web-development-learning/HTML/html-forms/)

This link shows the **rendered webpage of the `index.html` file** hosted using **GitHub Pages**.

---
