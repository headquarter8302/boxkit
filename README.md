<p align="center"><img src="https://github.com/headquarter8302/boxkit/blob/main/boxkit%20logo%20wh%20bg.png" width="250px" /></p>

# BOXKit
A CSS stylesheet for making boxes, no idea why anyone would want to use it, but many people need it, I guess?

## Description
As the first paragraph said, a CSS stylesheet for making boxes, whether it is just a box, or some gradiented, box-shadowed, roundy boxes. It's made from 100% vanilla CSS, no preprocessors like SASS, could be included in a project or website immediately.

## Installation
You could apply this stylesheet and install it to your websites and projects, but before following any of these methods, you need first to install one of the [releases](https://github.com/headquarter8302/boxkit/releases) from the [`main`](https://github.com/headquarter8302/boxkit/tree/main) branch, optimally, the latest release. Unless you want the wonky [`dev`](https://github.com/headquarter8302/boxkit/tree/dev) branch.

### Link method
This method is preferable.
1. Put the stylesheet to your website directory, or somewhere accessible.
2. Link it to your HTML file by using the `<link>` tag, of course insert it in a head element:<br>
*Replace `dir/` with the directory of the file, or the address, or just remove altogether if it is located in the root.*
````html
<link rel="stylesheet" href="dir/boxkit.css">
````
3. Done!

### Import method
This method could be used, if you somehow can't use a link tag, such as using it in a web hosting site or wikis.
1. Put the stylesheet to your website directory, or somewhere accessible..
2. Import it to your CSS page by using the `@import` method, of course insert it in the top of the CSS page:<br>
*Replace `dir/` with the directory of the file, or the address, or just remove altogether if it is located in the root.*
````css
@import url('dir/boxkit.css');
````
3. Done!

## Uses!
### Classes
The list below contains all available classes in the stylesheet
````css
.box
.round (defaults to 5px)
.round-10px
.round-15px
.round-20px
.round-30px
.background-blue
.background-red
.background-green
.background-yellow
.background-pink
.background-purple
.background-turqoise
.shadow-1
.shadow-3
.shadow-5
.shadow-10
.shadow-15
.shadow-20
.triangle
.circle
.padding (defaults to 5px)
.padding-10px
.padding-15px
.padding-20px
.padding-30px
.padding-50px
.padding-left
.padding-left-10px
.padding-left-15px
.padding-left-20px
.padding-left-30px
.padding-left-50px
.padding-top
.padding-top-10px
.padding-top-15px
.padding-top-20px
.padding-top-30px
.padding-top-50px
.padding-right
.padding-right-10px
.padding-right-15px
.padding-right-20px
.padding-right-30px
.padding-right-50px
.padding-bottom
.padding-bottom-10px
.padding-bottom-15px
.padding-bottom-20px
.padding-bottom-30px
.padding-bottom-50px
.margin (defaults to 5px)
.margin-10px
.margin-15px
.margin-20px
.margin-30px
.margin-50px
.margin-left
.margin-left-10px
.margin-left-15px
.margin-left-20px
.margin-left-30px
.margin-left-50px
.margin-top
.margin-top-10px
.margin-top-15px
.margin-top-20px
.margin-top-30px
.margin-top-50px
.margin-right
.margin-right-10px
.margin-right-15px
.margin-right-20px
.margin-right-30px
.margin-right-50px
.margin-bottom
.margin-bottom-10px
.margin-bottom-15px
.margin-bottom-20px
.margin-bottom-30px
.margin-bottom-50px
.border-color-blue
.border-red
.border-green
.border-yellow
.border-pink
.border-purple
.border-turqoise
````
And more coming!

The properties are made from classes for a reason, you could combine them!
````html
<div class="box round-10px background-red padding">This is a box with a 10 pixels border-radius, red background and a 5 pixel padding.</div>
````
