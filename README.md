# StaticBuilder

Introduction:

This project's goal was to create a way for html developers to be able to import content
into their files in an easy and painless way that did not affect the actual website in any way.

There are a lot of reasons one may want to do this, among them being, to reuse code in an easy
and error-free way. Imagine having a simple html page, you create a navigation bar that is going
to be used throughout the website; normally, you would have to copy-paste the navigation bar html
and CSS code in each page. This easily becomes a nightmare when you are constantly tweaking page
elements that are common throughout the website. With this script, all it takes is to run it
and your commonly used code is automatically placed throughout the website in a matter of seconds.

How to use:

Currently the basic functionality of the program is working and it is not customizable without
changing the variables in the python script. That may not be hard to do but in the future it may
be desirable to add a config file for easy customization.

To use this program, you have to place it in the root of your project. Your website should be
placed in a Source folder. A Templates folder inside that Source folder will contain html files
that will be reused.

In any part of a file you want to import content into, use the special tag in this way:

<import src="relative/path/from/inside/the/Templates/folder"/>

When you run the python script to build the website, it will be placed into a Public folder
in the root directory of the project.

If you have any feedback, feel free to contact or raise an issue.

