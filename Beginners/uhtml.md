<!-- <img src=../image-1.png alt="more info soon" /> -->

# Understanding HTML

HTML or Hyper Text Markup Language is the standard markup language for creating web pages and web applications. HTML is the skeleton of a webpage. It is used to define the structure and layout of the webpage.

# Stucture of the modern HTML page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <!-- This is where you add your stylesheets and scripts -->
</head>
<body>
    <!-- This is where you add your content -->
</body>
</html>
```
_Tip: If you don't want to type all of this everytime, type `doc` instead and press `tab` in VSCode to let Emmet snippets fill out the code for you._

***

# HTML Tags

HTML tags are used to define the structure of the webpage. They are enclosed in angle brackets `<>`. Most tags have an opening tag and a closing tag. The closing tag is the same as the opening tag except it has a forward slash `/` before the tag name.

```html
<tagname>Content goes here</tagname>
```

Some tags are self closing tags. They don't have a closing tag. They are closed by adding a forward slash `/` before the closing angle bracket `>`.

```html
<tagname />
```

***

# A list of tags that almost all websites would use

- `<html>` - The root element of an HTML page
- `<head>` - Contains metadata about the document
- `<title>` - The title of the document
- `<body>` - The visible part of the document
- `<h1>` -> `<h6>` - Headings
- `<p>` - Paragraph
- `<br>` - Line break
- `<hr>` - Horizontal rule
- `<a>` - Anchor tag
- `<img>` - Image
- `<ul>` - Unordered list
- `<ol>` - Ordered list
- `<li>` - List item
- `<table>` - Table
- `<tr>` - Table row
- `<th>` - Table header
- `<td>` - Table data
- `<div>` - Division
-  `<main>` - Main content of the document
- `<section>` - Subsection of the document

# Task to be completed

Create a simple layout with the tags mentioned above to see its usage.

Todo:
- Create html file
- add a title saying _"my first page"_
- in the body add all 6 heading tags 
- add an image from google images by copying the image address and adding it to the image tag's src attribute 

- create a table with the following data

|S.no.|Name|Age|
|----|----|---|
|1|John|20|
|2|Doe|21|
|3|Jane|19|

For your reference :
<details closed>
<summary>Solutions:</summary>

```html
<head>
    <title>
        my first page
    </title>
    <!-- your other metadata goes here -->
</head>
```

```html 
<img src="your-link-here" alt="alt text" />
```

```html
<table>
    <th>
        <td>S.no.</td>
        <td>Name</td>
        <td>Age</td>
    </th>
    <tr>
        <td>1</td>
        <td>John</td>
        <td>20</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Doe</td>
        <td>21</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Jane</td>
        <td>19</td>
    </tr>
</table>
```

</details>


