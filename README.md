
# jquery-gallery
Simple, responsive gallery built with jQuery

## Requirements
Latest jQuery version

## How to use
Designate an area on your website to hold the gallery. For example a `div`.
Inside of the div place the images you want to display.

```html
<div id="gallery">
	<img src="..." alt="Image 1" />
	<img src="..." alt="Image 2"/>
	<img src="..." alt="Image 3"/>
</div>
```

Use jquery to hook the plugin to the actual gallery like so: ```
```javascript
$("#gallery").gallery();
```

The gallery should now display.

It has several parameters you can send to the gallery plugin:
- loop
		true
		false (default)
 *Enabling **loop** will allow the gallery to return to the first position after reaching the end and vice versa.*
 

------------


- thumbnails
		true
		false(default)
*Enabling **thumbnails** automatically generates thumbnails from the given images.*

------------


- caption
		true
		false(default)

------------



------------


- start
		 1 to n; *n being the total amount of images in gallery (default 1)*
*By using start you can define a starting item*
 

------------


Thumbnails and caption **cannot** be displayed at the same time.
In order to write a caption, give the image you wish to display it on a `data-gallery-caption`

```html
<div id="gallery">
	<img src="..." alt="Image 1" data-gallery-caption="This text will appear as caption on an image."/>
</div>
```
Example given in `index.html` file.
