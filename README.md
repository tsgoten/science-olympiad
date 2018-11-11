# Science Olympiad Cheat Sheet Template
## Overview
This is mainly for study events with limited pages. The particular example for this template is Water Quality, but will work for similar events. 

In my experience using a cheatsheet in landscape orientation with multiple columns with a really small font is the best way to take notes, but you are free to modify that in the template.

## Colors
xcolor package for the various subheadings and such, I created new commands for some of the colors for ease of use, example `\red{}`

You can also use commands like `\mysubsub` to access the various colors for the subheadings

## Pictures
Now supports the use of images in multiple columns.
### Directory
Just save the images into the same directory as the tex files.
### Defualt
The default command  `\fig{example}` takes in just the file name, and defaults to `\columnwidth`.
### Specified Width
Use the command `\figwith{example}{5}` to specify the exact width in cetimeters
### Wrapped figure
Use the command `\figwrap{example}{5}{10}{r}` for a wrapped image. Here `example` is a possible file name `example.jpeg`, 5 and 10 are width and height respectively. r is for which side of the column the picture has to be placed.

## Autogenerate Glossary
yet to start work to progress
