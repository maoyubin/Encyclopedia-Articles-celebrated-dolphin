# Encyclopedia  Entry: `<head>`

`<head>`

`<head>` is where you would provide the metadata for your HTML document.  This includes your title, as well as links to your style sheet and scripts. Information inside the `<head>` element is not visible to website visitors. 


## Syntax

Introduction to the syntax/usage. A example of CSS syntax is below:

`<head>`

`<title>First Website</title>`

`<meta charset="UTF-8">`

`<link rel="stylesheet" type="text/css" href="mystyle.css">`

`</head>`

## Example: Title

The title to your website.

```
        <title>First Website</title>
```

The first piece of information you want to include in the `<head>` tag is your title, shown above. This title will show up on the top of the web-page in your browser. Your title will also be what Google uses to name the link they provide in search results. 

## Example: meta charset

Your websites charset declaration.

```
        <meta charset="UTF-8">
```

The main reason to include this in your head tag is to tell the browser what character encoding to use. This keeps the browser support consistent across all browsers.

## Example: Linking to external files.

Linking to external files such as a style sheet in your HTML document.

```
        <link rel="stylesheet" type="text/css" href="mystyle.css">
```

In the `<head>` tag is also where you include linking to important files such as CSS files or script files (.js). Above is an example of linking to your style sheet named mystyle.css. You first provide the link rel, which is telling the browser what relationship this file has to the HTML document. You will then tell the browser what type of file it is. Finally, you use href to provide the exact file name.

## Special Notes

The `<head>` tag is required in your HTML document, and should only be used once. You should begin the `<head>` tag right after the `<html>` tag, and end before the `<body>` tag.


	<html>
	  <head>
	  </head>
	  <body>

