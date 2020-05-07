# Project 0

Web Programming with Python and JavaScript

These project is composed by the following files: 
4 html files:
	index.html
	detail.html
	location.html
	other.html
	I use Bootstrap 4 component NavBar in all pages in order to allow to navigate between pagens.
	I use Bootstrap 4 grid Model to define the columns for small/large screen in location.html page
1 scss file: 
	Using 4 variables:
		$colorb_lg: background color for large screens (more than 576px)
		$colorf_lg: font color for large screens
		$colorb_sm: background color for small screens (less than 576px)
		$colorf_sm: font color for small screens
	Using nesting: for th and td into table.
	Using inheritage: %message for defining text format for all html components
	I include a @media query to change the background and font color for small screens (configurable as sccs variables). 
1 css file generated with: sass --watch styles.scss:styles_created.css
1 folder called "images" containing the images used in this project.

Video URL https://youtu.be/jC2KxoQyOGM
