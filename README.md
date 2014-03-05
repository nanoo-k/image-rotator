image-rotator
=============

A Javascript object that works with XML and JSON objects for transitioning between images.

Goal
====
And object that accepts an XML like the following, or a JSON equivalent:

	`<!--  
	'timer'    :: number of seconds between each image transition
	'fadeTime' :: number of seconds during each image transition
	'order'    :: how you want your images displayed. choose either 'sequential' or 'random'
	'looping'  :: if the slide show is in sequential mode, this stops the show at the last image (use 'yes' for looping, 'no' for not)
	'xpos'     :: _x offset position of all loaded clips (0 is default)
	'ypos'     :: _y offset position of all loaded clips (0 is default)
	-->
	<gallery timer="5" fadetime="3" order="sequential" looping="yes" xpos="0" ypos="0">
	<image path="images/images_slideshow/image1.jpg" />
	<image path="images/images_slideshow/image2.jpg" />
	<image path="images/images_slideshow/image3.jpg" />
	<image path="images/images_slideshow/image4.jpg" />
	<image path="images/images_slideshow/image5.jpg" />
	<image path="images/images_slideshow/image6.jpg" />
	<image path="images/images_slideshow/image7.jpg" />
	<image path="images/images_slideshow/image8.jpg" />
	<image path="images/images_slideshow/image9.jpg" />
	<image path="images/images_slideshow/image10.jpg" />
	<image path="images/images_slideshow/image11.jpg" />
	</gallery>`

This object was developed to replace the Flash banner that existed at www.ThreeRiversHorseTraining.com.