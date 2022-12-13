# pythonic methods to split your PDF's

The repository features the following:
> - This repository contains a compilation of different scripts to subdivide a pdf into smaller ones


### Local installation ###

To prepare the project, the following steps will be necessary:
> - Install [git](https://git-scm.com/downloads) locally;
> - On your local server, run a `git clone` command;


### Local execution ###
To execute any of the scripts here, you should

> - First download [python 3](https://www.python.org/). After, install the dependencies by typing `pip install -r requirements.txt` and then cd into the directory that most fits yout task. Run `python {script_of_your_directory}.py` on your terminal and then proceed with the use instructions;

### Use instructuions ###
> automatic-page-splitter

`script: singlepage-pdf-splitter.py`

This script performs the fragmentation of the pdf page by page, creating n pdfs with n = number of pages of the original pdf.

> customizable-splitter

`script: customizable_splitter.py`

This script is the most manual of all, at the same time it is the most customizable. It lets you create multiple pdfs bounded by numbered initial and final pages in the original pdf, simply by changing the list boundaries at the beginning of the code as explained by the comments therein.

> pdf-divider

`script: custom-pdf-div.py`

This script splits the pdf into a sub pdf. When activated by command line it receives 3 arguments: the original pdf directory and the initial and final pages, which will correspond to the first and last pages of the pdf that will be created from it.

### Lybraries ###

* pyPDF2
* pikepdf
* Pillow
