# CSS Modal
CSS-only dialog modal
[Demo](https://jsbin.com/jepuvuxoga/edit?html,css,output)
## Features
- Responsive
- Dark theme
- Possibility to place multiple close buttons
- No JavaScript

## Example

```html
<link rel="stylesheet" href="css-modal.css">

<input type="checkbox" name="modal-switch" id="modal-switch">
<label for="modal-switch">
	<button>Toggle modal</button>
</label>
<div class="modal">
	<div class="modal-header">
		Header
		<label for="modal-switch">&times;</label>
	</div>
	<div class="modal-body">
		<p>
			Somebody<br/>touched<br/>my<br/>spageht
		</p>
	</div>
	<div class="modal-footer">
		<label for="modal-switch">Close</label>
	</div>
</div>

```
## To-do

 - Can't click outside the modal
 - Multiple modals

----------
To make a dark modal, just add the class `modal-dark` to the modal:
```html
<div class="modal modal-dark">
	<div class="modal-header">
		Header
		<label for="modal-switch">&times;</label>
	</div>
	<div class="modal-body">
		<p>
			Somebody<br/>touched<br/>my<br/>dark<br/>spageht
		</p>
	</div>
	<div class="modal-footer">
		<label for="modal-switch">Close</label>
	</div>
</div>
```
# Browser compatibility
![From browseemall.com/Compatibility/ValidateCSS](https://i.imgur.com/A6SqxQ5.png)
From [browseemall.com/Compatibility/ValidateCSS](https://www.browseemall.com/Compatibility/ValidateCSS)
# License
Code copyright 2018 Enzo P. Code released under the [MIT License](https://github.com/SawnFx/css-modal/blob/master/LICENSE).
