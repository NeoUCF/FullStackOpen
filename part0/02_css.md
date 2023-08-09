# CSS (Cascading Style Sheets)
<https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics>

Styles (color, size, font, shapes, etc.) can be applied using CSS. CSS can be integrated into your HTML in 3 ways:
1. Inline Style
2. Internal Style
3. External Style (recommended)

To have External CSS, write your styles in a separate file (ex. `style.css`). Then link the stylesheet between the `<head></head>` tags.

`<link href="styles/style.css" rel="stylesheet" />`

![Alt text](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png)
The whole structure above is called a **ruleset**.

You can select multiple elements and apply a single ruleset to all of them.
```css
p,
li,
h1 {
  color: red;
  width: 500px;
  border: 1px solid black;
}
```

## Types of Selectors:
- **Element/Tag/Type Selector**
  - ```css
	h1 {
	}
  	```
- **ID Selector**
  - ```css
	#unique {
	}
  	```
- **Class Selector**
  - ```css
	.box {
	}
  	```
- **Attribute Selector**
  - ```css
	a[href="https://example.com"] {
	}
  	```
- **Pseudo-Class Selector**
  - ```css
	a:hover {
	}
  	```
- **Pseudo-Element Selector**
  - ```css
	a::first-line {
	}
  	```
- **Combinators**
  - ```css
	article > p {
	}
	```

## CSS Box Model

![CSS Box Model](https://www.simplilearn.com/ice9/free_resources_article_thumb/CSS-Box-Model.png)