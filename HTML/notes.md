#  HTML
**HTML (HyperText Markup Language)**  
- Provides structure to a web page  
- Not case sensitive  

A website can have multiple layers.

The home page is automatically detected by most servers when the file name is:

```index.html```

HTML **tags** are containers for content or other tags.

Tags can be customized using **HTML attributes**.  
Attributes add additional information to a tag (similar to low-level styling or configuration).
`href` inside the anchor tag would be considered as an attibute

Elements inside the `<body>` tag (like `<h1>` or `<p>`) provide **semantic structure** to the website.

Everything inside the `<body>` tag is treated as display content (except special keywords).

It is highly recommended to leave **formatting related tasks to _CSS_** wherever possible, minimal use of HTML for formatting even tho attributes for formatting exists within HTML

No matter how many spaces we put between words, HTML will auto remove all but one space
i.e` Only One space allowed between words unless we use the pre tag`

##  Tag Syntax

<opening-tag> Content </closing-tag>

## Pre tag
<pre>This ensures
text written within the tags
is pasted as is.
this will break line,
even if i didn't use the br function because of the pre tag. </pre>

##  Anchor Tag

Used to create hyperlinks.

<a href="URL">Link Text</a>

### Breakdown:
- `a` → Anchor tag  
- `href` → Hypertext reference (where the link points)  
- `Link Text` → Visible clickable text  

### Absolute Link (External Website)

<a href="https://google.com">Google</a>

### Relative Link (Within Your Project)

<a href="/index.html">Home</a>

### Linking to a File in Another Folder

<a href="/folder-name/another.html">Another Page</a>


##  Image Tag

Used to display images.

<img src="URL" alt="description" height= "Number" width = "Number">

### Breakdown:
- `src` → Image source (URL or file path)  
- `alt` → Text shown if the image fails to load  
- `height` - To adjust the height of the image
- `width` - To adjust the width of the image
**It is ill-advised to change both height and width together will mess with aspect ratio.**
***H & W should be changed using CSS not HTML. ***
images maintain aspect ratio even if only one parameter is set. 

## Comments

<!-- This is a comment -->

## Text formatting

<b> BOLD </b> 
<i> ITALIC </i>
<u> Underline </u>

<big> For big font size  </big>
<small> for smaller font size <small>

<sub> subscript </sub>
<sup> Super script </sup>

### Empty tags
Used plainly as text, nothing in middle, no closing and opening, just simple empty tag to be used as is. 

<hr> horizontal line accross page used to separate content
<br> break line.

## Callback Functions

Event handler functions are called **callback functions**.

They:
- Are not directly invoked by your application code  
- Are executed by the runtime environment (e.g., browser)  
- Run at the appropriate time (like button click, page load, etc.)

#  CSS

**CSS (Cascading Style Sheets)**  
A stylesheet language used to control the appearance of web pages.

##  Class

A `class` is a label attached to elements so they can be styled together.

### Example:

```html
<p class="intro">Hello</p>
```

```css
.intro {
  color: blue;
}
```



## 🎯 Selectors

CSS provides multiple identifiers to select elements:
- By tag  
- By class  
- By ID  
- By hierarchy  
- By attributes  

