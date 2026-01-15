## Exercise #4

1. Check if you have the `tidyverse` and `pheatmap` packages installed, if you don't please install them using `install.packages()` before starting this exercise.
1. **Download the linked [R script](https://github.com/hbctraining/Training-modules/raw/master/Rmarkdown/Rscript.R)** and save it within the `rmd_workshop` project directory.
2. **Download the linked [RData object](https://github.com/hbctraining/Training-modules/raw/master/Rmarkdown/data/Rmarkdown_data.Rdata)** by right-clicking and save it to the `data` folder within the `rmd_workshop` project directory.
3. Open the Rscript file, **transform the R script into a RMarkdown file** by clicking `File` -> `Rename`, and rename it as `Rscript.Rmd`. 
4. It now has the correct extension for an RMarkdown file, but you won't be able to knit it as is. Add the following updates to be able to knit this file:
    - Add a basic YAML header at the top 
    - Create an R chunk for all code underneath each `#` comment in the original R script
    - Comment on the plots (you may have to run the code from the R script to see the plots first)
    - Add a floating table of contents in the YAML header by referring to these [instructions](https://bookdown.org/yihui/rmarkdown/html-document.html#floating-toc). YAML is fussy about indentations, make sure you are paying attention to it.
    - (Optional) If you would like to have a button that show/hide your code in the report, you can add an additional argument in the YAML header by referring to this [instruction](https://bookdown.org/yihui/rmarkdown/html-document.html#code-folding).
    - Add a code chunk with `sessionInfo()` at the end
4. **Knit the markdown** 
5. Upload the new Rmd file and the HTML report to the Dropbox link on the schedule page.
