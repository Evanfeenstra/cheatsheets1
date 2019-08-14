# html 

### basic elements

`<div>`: basic wrapper element. (default = display:block;)

`<span>`: (default = display:inline-block;). Usually used for text

`<p>`: paragraph. Has built-in margins

`<h1>`...`<h5>`: headers. built-in font-sizes

`<a>`: links! (anchor). 
 - href="https://something.com"
 - target="_blank" to open a new tab 

`<img>`: images
 - src="/url_of_your_image"
 - alt="name of your image (for screen readers)"

### semantic tags

- `<header>`
- `<section>`
- `<main>`
- `<footer>`
- `<nav>`
- `<pre>`: preformatted text
- `<code>`: code snippets
- `<aside>`
- `<article>`

### forms

`<form>`: has an "onSubmit" prop

All form inputs have "value" and "onChange" props
- `<input>`: text input
- `<button>`: (if type="submit" then clicking the button will submit the surround form)
- `<select>`: dropdown (has `<option>` elements in it)
- `<radio>`
- `<checkbox>`: (has a "checked" prop instead of "value")

### built in props

- style={{ height:40 }} (this is the React style)
- className (to add CSS classes)
- id (to add a CSS id)
- onClick (all elements are clickable)
- onHover

### React vs HTML notes

- all props are camelcase! like className, onClick... in original HTML, they are all lowercase.
- in original HTML, props MUST be strings
- in original HTML, "className" is just "class"
