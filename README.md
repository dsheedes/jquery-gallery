
# jquery-gallery
Simple, responsive gallery built with jQuery

## Requirements
Latest jQuery version

## How to use
Designate an area on your website to hold the gallery. For example a `div`.
Inside of the div place the images you want to display.

Use jquery to hook the plugin to the actual gallery like so: `$("#gallery").gallery()`

The gallery should now display.

It has several parameters you can send to it.

    .gallery({
		loop:true/false (default false),
		thumbnails:true/false (default false),
		caption:true/false (default false),
	})

Enabling loop will allow the gallery to return to the first position after reaching the end and vice versa.
Enabling thumbnails automatically generates thumbnails from the given images.
Enabling caption designates an area and displays the caption text.
 
Thumbnails and caption **cannot** be displayed at the same time.
In order to write a caption, give the image you wish to display it on a `data-gallery-caption`

Example given in `index.html` file.
