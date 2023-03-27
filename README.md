# metadata_checkup

check sequencing metadata files for errors

## How to use

Either run the code chunks in RStudio or use the following command line

``
Rscript -e "rmarkdown::render('check_metasheet.Rmd', params = list(filepath = './files/my_metadata_file.xlsx'), output_file ='./files/my_metadata_file.nb.html')"
``

you might need to install pandoc on your system for the command line option to work. On Linux, pandoc can be installed with this command

``
sudo apt install pandoc
``



