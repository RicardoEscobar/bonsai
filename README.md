# BONSAI
## Description
Bonsai wants to make a meme generator. [Here's what it looks like]("https://s3.amazonaws.com/codecademy-content/projects/2/bonsai/index.html"). Enter an image URL, and captions to go on the top and bottom.

## Tasks
1. Look at index.html:
In the `<div class="meme thumbnail">` section, there are three elements: an `<img>` element, a `<h1 class="top-caption">` element, and a `<h1 class="bottom-caption">` element.
In the `<div class="tool">` section, there are three `<input>` elements. When text is entered into the `<input id="top-text">`, the text of the `<h1 class="top-caption">` updates. Similarly when text is entered into the `<input id="bottom-text">`, the text of the `<h1 class="bottom-caption">` updates. Lastly, when text is entered into the `<input id="image-url">`, the src of the `<img>` updates.

2. In `app.js`, attach a keyup event handler to the `#top-text` input so that it can respond to when a user types a key. Check out how to use `.keyup()`

3. Inside the keyup event handler, get the text entered into the `#top-text` input using `.val()`. Then set it as the text of `<h1 class="top-caption">` using `.text()`.

4. Attach a second keyup event handler to the `#bottom-text` input. Inside this event handler, get the text entered into `#bottom-text`, and set it as the text of `<h1 class="bottom-caption">`

5. Attach a third keyup event handler to the `#image-url` input. Inside this event handler, get the text entered into `#image-url`, and set it as the src attribute of the element using `.attr()`. Check out how `.attr()` works.
