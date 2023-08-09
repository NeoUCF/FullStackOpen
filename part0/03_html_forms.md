# HTML Forms
<https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Your_first_HTML_form>

**Web forms** are one of the main points of interaction between a user and a website or application.

From a **UX** perspective, keep your forms simple. Otherwise, it can be frustrating.

![Sketch of potential form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form/form-sketch-low.jpg)

Create wireframes or mockups to ease your design and build process.



```html
<form action="/my-handling-form-page" method="post">
	<ul>
		<li>
			<label for="name">Name:</label>
			<input type="text" id="name" name="user_name" />
		</li>
		<li>
			<label for="mail">Email:</label>
			<input type="email" id="mail" name="user_email" />
		</li>
		<li>
			<label for="msg">Message:</label>
			<textarea id="msg" name="user_message"></textarea>
		</li>

		<div class="button">
			<button type="submit">Send your message</button>
		</div>
	</ul>
</form>
```

CSS Styles omitted for brevity
