# HTML
- Hyper Text MArkup Language
- Provides structure to the web page
- Not case sensitive. 

A website can have multiple layers. 
The home page, is auto detected by most servers by the file name of `index.html`
HTML Tags are containers for content or other tags (_present at index.html_)

HTML TAGs can be further customized using HTML attributes.
These are used to add more information to a tag can be thought of as low level CSS work.

The tags used inside body, like h1(heading) or p(para) are semantics to provide structure to the website. Everything inside bobdy tag is treated as display data (except keywords)

## Anchor Tags
THese tags are used to hypertext something in order to provide a supporting link it can point to, sample can be found in _index.html_

<a href = "URL" > link text</a>
    - a is the anchor tag
    - href is the hypertext reference, what will the hypertext reference to. 
    - link text is the text it will show in place of the URL. 

    href = "URL like google.com" this would be called an absolute anchor tag as this text would link to an absolute external website (google in this case. )
    href = "/index.html" This is a relative tag, the hypertext would link to different page of our website, this index.html is a file in our project and the hypertext would take us there when clicked upon
    for files under a different folder we will use href as 
    href = "/TESTING ``path to another folder`` /another.html"
## Image tags
 Used to display images on the website. 

 <img src= "URL" >

## `<>` opening tag syntax `</>` is the syntax for closing the tag
    `<!--` opening for comments `-->` closing for comments 

Output on the console is achieved using the `console.log`

Event handler functions are called `callback` functions. These functions are not invoked by the application code instead by runtime environment (in this case: browser) at the appropriate time. 

# CSS
 CSS Files also known as the  `cascading style sheet` is a  style sheet language used to determine the appearance of web pages. 
 `CLASS` can be understood as a label attached to elements in order to attach them together. 

 ## Has multiple identifiers allowing selection of certain content by class or the defined identifier. 




