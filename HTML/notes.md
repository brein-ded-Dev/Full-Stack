Will convert this entire MD to HTML Using perfect semantics. 
will make a index inside index to put up different sections of the website
like let's say i'll have block tags as a bigger heading, with each heading name inside clickable to take us to that portion of the website, or something like that, something complicated and slightly big. 

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

#  Tag Syntax

<opening-tag> Content </closing-tag>


# Pre tag
<pre>This ensures
text written within the tags
is pasted as is.
this will break line,
even if i didn't use the br function because of the pre tag. </pre>

#  Anchor Tag

Used to create hyperlinks.

<a href="URL" target = "" >Link Text</a>

# Breakdown:
- `a` → Anchor tag  
- `href` → Hypertext reference (where the link points)  
- `Link Text` → Visible clickable text. Like a Link text we can replace it with `<img src = "link">` for a clickable Picture
- `target` = Specifies where to open a new link. 
      - _main = new tab
      - 
      - 

# Absolute Link (External Website)

<a href="https://google.com">Google</a>

## Relative Link (Within Your Project)

<a href="/index.html">Home</a>

## Linking to a File in Another Folder

<a href="/folder-name/another.html">Another Page</a>


#  Image Tag

Used to display images.

<img src="URL" alt="description" height= "Number" width = "Number">

## Breakdown:
- `src` → Image source (URL or file path)  
- `alt` → Text shown if the image fails to load  
- `height` - To adjust the height of the image
- `width` - To adjust the width of the image
**It is ill-advised to change both height and width together will mess with aspect ratio.**
***H & W should be changed using CSS not HTML. ***
images maintain aspect ratio even if only one parameter is set. 

# Comments

<!-- This is a comment -->

# Text formatting

<b> BOLD </b> 
<i> ITALIC </i>
<u> Underline </u>

<big> For big font size  </big>
<small> for smaller font size <small>

<sub> subscript </sub>
<sup> Super script </sup>

## Empty tags
Used plainly as text, nothing in middle, no closing and opening, just simple empty tag to be used as is. 

<hr> horizontal line accross page used to separate content
<br> break line.

# Page Layout Techniques

## Semantic Tags 
- These tags like `header` or `footer` These aren't like MS word, in this case Search engines use these tags.
- These are tags whose purpose is obvious by looking at them/ reading them

<header> Give a header to the website
<footer> Gives footer to the website. 

### <main> 
  - This is used for the main content of the file 
  - <section> For a section of the page. This represents a generic grouping of content which generally  belongs to a larger whole.
  - <article> For an article on the page. This is a complete, self contained composition that makes sense on its own. 
  - <aside> For content aside from the main content like ads.To ensure that search engines do not include this within the main content itself.  

## Non-Semantic Tags

  ### <div> TAG
  - Does not have any particular functions
  - Contains other HTML elements/tags. 
  - Block Tag
  - Used for division or grouping of other elements by providing them layout and structure.
  - Makes styling with CSS easier as this becomes a class. 
   
  ### <span> Tag
  - Inline Tag
  - Is also used to contain other HTML tags/elements
  - Same purpose as Div but inline when it comes to CSS

## Lists
- Used to represent real life List data
- Regardless of list type, it uses the <li> Tag to represent list items
- Nested lists are ok and normal. 

### Unordered List <ul>
- 

### Ordered List <ol>


## Block Tags
These tags take up the entire width of the website no matter what.
- <address>
- <article>
- <aside>
- <blockquote>
- <canvas>
- <dd>
- <div>
- <dl>
- <dt>
- <fieldset>
- <figcaption>
- <figure>
- <footer>
- <form>
- <h1-h6>
- <header>
- <hr>
- <li>
- <main>
- <nav>
- <noscript>
- <ol>
- <p>
- <pre>
- <section>
- <table>
- <tfoot>
- <ul>
- <video>

## Inline Tags
These take as much space as they need, not more than that.
- <a>
- <abbr>
- <acronym>
- <b>
- <bdo>
- <big>
- <br> -inline because i can use it within existing content, and the data before the br tag will remain as is. 
- <button> 
- <cite>
- <code>
- <dfn>
- <em>
- <i>
- <img>
- <input>
- <kbd>
- <label>
- <map>
- <object>
- <tt>
- <var>
- <output>
- <q>
- <samp>
- <script>
- <select>
- <small>
- <span>
- <strong>
- <sub>
- <sup>
- <textarea>
- <time>
# Callback Functions

Event handler functions are called **callback functions**.

They:
- Are not directly invoked by your application code  
- Are executed by the runtime environment (e.g., browser)  
- Run at the appropriate time (like button click, page load, etc.)






#  CSS

**CSS (Cascading Style Sheets)**  
A stylesheet language used to control the appearance of web pages.

#  Class

A `class` is a label attached to elements so they can be styled together.

## Example:

```html
<p class="intro">Hello</p>
```

```css
.intro {
  color: blue;
}
```



# 🎯 Selectors

CSS provides multiple identifiers to select elements:
- By tag  
- By class  
- By ID  
- By hierarchy  
- By attributes  

