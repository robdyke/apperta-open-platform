# Defining an Open Platform
The Apperta Foundation is a not-for-profit community interest company supported by NHS England and NHS Digital (HSCIC) 

They produced a document called “Defining an Open Platform” to make the case for open platforms and lay out a blueprint for an open platform architecture at a level of detail that would allow any willing party to build a first generation implementation of an open platform that would be interoperable with any other.

The document is a PDF. Commenting on the document is handled by User Voice. 

I think there is room for improvement.

## Goals
- open source the document
- add discussion thingummy

## Getting started
- fork the repo and clone it
- open the PDF and pick a section of the document to convert 
- make a new page in 'docs/_docs' for the section you have chosen by duplicating template.md
- using the text files in source_files copy and paste the text from the relevant pages into the new document 


## References

[How to Convert a PDF File to Editable Text Using the Command Line in Linux](https://www.howtogeek.com/228531/how-to-convert-a-pdf-file-to-editable-text-using-the-command-line-in-linux/)

Extract text from each page to a file

`for i in {1..48}; do pdftotext -f $i -l $i Apperta_Defining_an_Open_Platform_SP.pdf Apperta_Defining_an_Open_Platform_SP-nolayout-p$i.txt; done`
