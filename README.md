# Week1-md-example

This is an example of how to create a markdown (.md) document that will display correctly on Github.
I've included the original Rmarkdown (.Rmd) file, along with the things that are produced when you knit it. 

Things to note:

1. Lines 5-6 of the Rmarkdown file have been edited to read as follows:
output:
  rmarkdown::github_document: default
  
This is what allows the .md file to be produced in a way that will work for github.

2. As well as uploading the .md file you also have to upload the figure files. This is so that
github can find them when it tries to render the .md file.

Note that this didn't display the Latex equation for the solution correctly. The simplest way of
doing that is to knit to a pdf instead and then upload the pdf. (See example pdf in this repo.)

Other options for this can be fdound in the "Useful-Tips" repository here.
