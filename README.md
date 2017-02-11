# LaTeX_Report_Skeleton
##INSTRUCTIONS
report.tex is supposed to remain unchanged
create bibliography.bib in this directory
 
add figures, table data, etc to the relevant folders
no changes to these folders will be tracked by git

add folders within Sections to contain section data
ie: Introduction; folders should have a .tex file sharing hte same name
ie: Introduction/Introduction.tex
this file will be imported using /addsection
use this file to import other files in the section
nothing within section other that the 3 .tex files will be tracked

You can use hte python script to generate a folder and matching .tex file
For an upper-level directory. Please no spaces.
Run, type the name, and a folder and file will be generated with that name

I've used 
git update-index --assume-unchanged FILE
to ignore changes to many files
git update-index --no-assume-unchanged FILE
can be used to undo this if needed

## Bibliography Types
https://en.wikipedia.org/wiki/BibTeX