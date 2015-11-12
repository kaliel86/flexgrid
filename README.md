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
