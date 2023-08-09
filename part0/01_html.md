# HTML (HyperText Markup Language)
<https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics>

HTML the structure of a webpage. It consists of **Elements**. A typical element includes an opening **tag** with some attributes, enclosed text content, and a closing tag.

![Anatomy of HTML Element](https://developer.mozilla.org/en-US/docs/Glossary/Element/anatomy-of-an-html-element.png)

You can put elements inside other elements too — this is called **nesting**. Tags must open and close correctly.

**Void Elements** are elements which have no content. (ex. `<img src="images/firefox-icon.png" alt="My test image">`)

## Anatomy of an HTML document
Here's a basic `index.html`.
```html
<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image" />
  </body>
</html>
```

# Images
`<img src="images/firefox-icon.png" alt="My test image">`

The `src` attribute contains the path to our image file.
The `alt` attribute is a descriptive text of the image for accessibility reasons.

# Marking up text
Some essential tags:
- Headings
  - `<h1>Big Heading</h1>`
  - ...
  - `<h6>Little Heading</h6>`
- Paragraphs
  - `<p>Content for paragraph</p>`
- Lists
  - ```html
	<ul>
		<li>Bullet Point / Unordered list</li>
		<li>Bullet Point / Unordered list</li>
		<li>Bullet Point / Unordered list</li>
	</ul>
	```
  - ```html
	<ol>
		<li>Numbered / Ordered list</li>
		<li>Numbered / Ordered list</li>
		<li>Numbered / Ordered list</li>
	</ol>
	```

# Links
Use the **Anchor** tag to link a page to another.
```html
<a href="https://www.mozilla.org/en-US/about/manifesto/">
  Mozilla Manifesto
</a>
``` 