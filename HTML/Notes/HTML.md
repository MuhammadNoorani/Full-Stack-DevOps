# HTML Overview


## Intro

- HTML stands for HyperText Markup Language
- It's the structure/building blocks of the web-page 
- It is not a programming language, it's a markup language. So, there's no logic built into HTML.
- HTML consists of elements and tags
- Each element has an opening and closing tags
- You can have as many tags nested into other tags


- Some tags are self-closing tags


## Get Started

### 1. Should install Live Server extension in VSCode

### 2.  BoilerPlate

  
```
<!DOCTYPE html>     
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

```

- `<!DOCTYPE html> `This tells browser this is web page.    
- `<html lang="en">` html is root element.
- `head` Contains metadata which is information about the document and also contains style sheets
- `metadata` items are used for SEO of the website

- Some Meta-Tags that google and other search engines use for SEO

``` 
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie-edge">
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML, CSS, XML, JavaScript">
<meta name="author" content="John Doe">

``` 
  
### 3. Inline ELements vs Block Elements

- ### `Inline Elements`

    - Do not start a new line
    - Only take needed width

        - Examples : `<span>` `<img>` `<a>`

- ### `Block Elements`

    - Starts a new line
    - Take full width available

        - Examples : `<div>` `<h1>` `<h6>` `<p>`

## Templates
1.  Table


## Most commonly used Tags

### a. Inline Text Formatting

1. `<h1></h1>`
2. `<p></p>`
3. `<br>` - Line Breaks
4. <strong>lorem and `tab` for fake data</strong> : Gives a block of text that you can put in paragraph as a filler.
5. `<strong>` - It identifies as important, Makes the text bold
6. `<em>` - It is for emphasis, it italicizes the word.
7. `mark` - It <mark>highlights</mark> the  text
8. `del` - For deleting, adds strike through
9. `small` -  It makes the text smaller
10. `ins` - Adds an underline under the text
11. `sub` - It is for <sub>subscript</sub> of  the word
12. `sup` - It is for <sup>superscript</sup> of  the word


```
Note

b and i : Bold, Italic - Not semantic, so not to be used anymore.

```


### b. Division and Span Tags

1. `<div>` -  Defines a section in the document and it's block level.

- It is a general purpose container and helpful in seperating and indentifying groups of elements.

2. `<span>` - Defines a section of a document in-line.

- For example : Want a section of paragraph to look different, then grab onto the span tag and then format as needed.
- It has a style attribute, through which you can apply CSS styling directly to HTML element.

```
<span style="color:red">
```

3. `<hr>` - Horizontal Rule, It draws a line, is a way to seperate sections fo the web page.

### c. Attributes, Images and Anchor Tags

- Attributes are used to provide additional information about HTML elements.
- They are defined in the opening tag, are key value pairs.

<br>

- Anchor tags create hyperlinks ot content outside of the current page or within the current page.
- It could be other pages on your website.

1. `<title="This is 1st paragraph, first line">` 
2. `<img src="banner.png" alt="alternate description here">` 
3. `<a href="#"></a>` - 

- `#` represents will remain on the same page.
-  `_blank` Opens a new blank tab for the link



- Anchor tags can be placed anywhere, they are inline can be wrapped also.

```
Trick : Click on the image and you are redirected to a link/page (hyper-linked). 
Wrapped anchor around image tag.

<a href="https://www.google.com">
    <img src="banner.png" a lt="alternate description here">
</a>

```


- For spacing and layout don't use line breaks, always use css



## General Guidelines

- Use lowercase element names - ✓ <div> X <DIV>
- Use lowercase attribute names
- Use lowercase file names
- Use camel case for names, classes, ID's, etc - ✓ myClass
- No spaces before or after = in attributes - ✓ title="My Title"
- Avoid long lines of code, break up code
- Do not add blank lines without a reason
- Indent code 2 or 4 spaces (preference)
- Close tags in proper order -
    x<p><strong>text</p></strong>
    ✓ <p><strong>text</strong></p>