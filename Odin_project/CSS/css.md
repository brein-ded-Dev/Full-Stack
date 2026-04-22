# Selectors
- `* {} ` this is considered as the universal selector and all elements below this would have the attributes applied to them. 
- `div or p {}` This would select all elements with the given element type, like all <div> or <p> elements would have the attribute applied to them. 
- `.class-name {}` the `.` is the class selector and selects all the elements of the used class. 
- `#id-name{}` the `#` is the ID seelctor and selects the elements inside the given id. 
- 2 selectors can be grouped using a `,`
    - `.class-1`
        `.class-2` this can be used to provide common attributes without repetition. 

- chaining 2 selectors can be done using `.class-1 .class2` 1 space in between just two selectors attached to each other, this is useful if we cant to make changes to the
`class2` attribute present inside the `class-1` attribute. 
1st one is the ancestor and the second one is the child element. 
we can chain seelctors in any manner i.e `.class1 .class2`
`.class1 #id1`
`#id1 #id2`

- `.class1.class2` This is would use the elements with both class1 and class 2 attributes
- no space in middle
can be arranged in any manner
`.class1#id1` etc. 

# Properties
- `color` property- the value can be in any format like `hex` `hsl` or the `rgb` format
- `font-family`- the family can either be specific `has to be inside quotes for specific` `"calibri"`or generic `serif` which does not require quotes 
- `font-size` we define the value in pixels like `22px` no space in between. 
- `font-weight` the level of boldness- can either be a keyword like `bold` or a value between `1-100`
- `text-align` used to horizontally align the text like `text-align: center`
- `height` `width` image height and width values via CSS, `auto` can be used which manually changing one value in order to maintain proportions accordingly

# Linking CSS to HTML
Inside the Head element we use
- `<link rel="stylesheet" href"">` rel is used when both files are in the same directory and is used to define that the sheet in question is a style sheet. Href for absolute/relative link of the said file.

## Embeded CSS / internal CSS. 
- Inside the head element we enclose all our styling options under the <style> element </style>

