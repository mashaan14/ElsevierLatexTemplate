# Elsevier `LaTeX` Template
A LaTeX Template with double column based on `cas-dc.cls`

<p align="middle">
  <img src="/Manuscript_Page_1.jpg" width="49%" />
  <img src="/Manuscript_Page_2.jpg" width="49%" /> 
</p>

## Editorial Manager
Some Elsevier journals require uploading raw latex files to the editorial manager instead of a pdf. But editorial manager does not support subdirectories. Because of these dependencies, it will produce a pdf full of errors. This repository contains the latex files for Elsevier journals. It does not have any subdirectories, so most of the errors are solved.

## Tips to ensure a successful upload to Editorial Manager
1.	Generate the `.pdf` on your machine
2.	Copy all the content of `.bbl` to the end of the `.tex` file
3.	Comment out the link to `.bib` file
4.	Run the pdf again to make sure it produces the right pdf with no links to `.bib`
5.	Zip figures + 1 `.tex` file
6.	Drag and drop the zip onto the Editorial Manager
7.	Zip all other supported documents (e.g., response to reviewers and highlights)
8.	Choose the right classification for the supported documents after being unzipped by Editorial Manager


because submissions to Editorial Manager must:
- not include any subfolders
- have only one .tex file
