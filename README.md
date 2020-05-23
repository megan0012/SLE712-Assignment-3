## SLE712 Assignment 3 (Trimester 1, 2020)
This project is an assessment for Practical 3 of SLE712 (Bioinformatics and Molecular Biology Techniques) taught by Dr. Mark Ziemann of the School of Life and Environmental Sciences of Deakin University, Waurn Ponds Campus on the first trimester of 2020. This project uses the R language in manipulating genetic data to gain insights and develop data analysis skills necessary for Bioinformatics. This project uses Github as versioning control.

## Contents
* Folder Structure
* Getting Started
* Authors
* License
* Acknowledgments

## Folder Structure

The project comprises of three main folders in which you would store certain files.

### Data/

This folder should contain data files like .csv, .tsv, .fa, etc.

In this folder:

- A gene expression data and a growth data for part 1 of the project taken from [Dr. Mark Ziemann's Github repository for the unit](https://github.com/markziemann/SLE712_files/tree/master/bioinfo_asst3_part1_files).
- A sample gene sequence file for part 2 of the project taken from [Dr. Mark Ziemann's Github repository for the unit](https://github.com/markziemann/SLE712_files/tree/master/bioinfo_asst3_part2_files).
- Files generated by the RScripts like downloads and files pertaining to the creation of BLAST databases.

### Scripts/

This folder should contain R script files.

In this folder:

- Script for part 1 of the project containing basic data manipulation on a gene expression data and a tree growth data 
- Script for part 2 of the project containing analysis on a sample gene sequence against a library of *Escherichia coli* genes

### Rmd/

This folder should contain all R markdown and associated files.

In this folder:

- **references** which should contain any reference documents to be used by R Markdown file. This currently includes:
  - A default Harvard-Style word doc, "SLE712References.docx"
- **img** which should contain images to be inserted into R Markdown file. This currently includes:
  - An image showing the output formats generated by the scripts or the R Markdown files.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.  

### Prerequisites

Things you need to install

- R version 3.6.3 (2020-02-29)
- RStudio Version 1.2.1335
- Packages and Libraries 
  *For part 2, make sure to install these packages before you run the code*
  + seqinr
  + R.utils
  + rBLAST
- A function (made by Dr. Ziemann) referenced from this [link](https://raw.githubusercontent.com/markziemann/SLE712_files/master/bioinfo_asst3_part2_files/mutblast_functions.R)

### Installing

#### R, RStudio, and Packages Installation Tutorial
To install R, RStudio, and Packages, go to [this tutorial from datacamp](https://www.datacamp.com/community/tutorials/installing-R-windows-mac-ubuntu)

### Cloning the repository
To clone the repository, follow this [tutorial from RStudio](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN) and use this link as the **repository URL:**

  *<https://github.com/megan0012/SLE712-Assignment-3.git>*

## Authors

* **Megan Soria** - [LinkedIn Profile](https://www.linkedin.com/in/megan-soria-b8a97857/)
* **Ankush Dehlia** - [LinkedIn Profile](https://www.linkedin.com/in/ankush-dehlia/)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details





