## My pagedown rendered CV

This repo is based on https://github.com/nstrayer/cv, thank you! Found it while reading his blog post, https://livefreeordichotomize.com/2019/09/04/building_a_data_driven_cv_with_r/

This repo contains the source-code and results of my CV built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

- `resume.Rmd`: Source template for single page resume. This is what I have used to create my own CV. Alternatively, I could modify index.Rmd to create a multi-paged cv.
- `mypositions.csv`: A csv with columns encoding the various fields needed for a position entry in the CV. A column `section` is also available so different sections know which rows to use.
- `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. # my_cv
