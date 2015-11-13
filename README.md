# Flexgrid
Sass Grid using flexbox

## Install

Just add the _grid.scss to your project using Sass.

## Use the grid

This grid is based on container, children will fit

    <div class="grid-4">
	    <div>Hello, i'm 25% width</div>
	    <div>Hello, i'm 25% width</div>
	    <div>Hello, i'm 25% width</div>
	    <div>Hello, i'm 25% width</div>
    </div>

Use **.push-first** if you want an item to be in first place, no matter what is his HTML order:


    <div class="grid-3">
	    <div>Hello, i'm 33% width</div>
	    <div>Hello, i'm 33% width</div>
	    <div class="push-first">
		    Hello, i'm 1st item, 33% width
	    </div>	    
    </div>
    
## Going responsive
Here we write a container with children taking 6 columns on large screen, 4 columns on medium screen and 1 column on small screen.

    <div class="grid-6-m-4-s-1">
	    <div>Hello</div>
	    <div>Hello</div>
	    <div>Hello</div>
	    <div>Hello</div>
    </div>
