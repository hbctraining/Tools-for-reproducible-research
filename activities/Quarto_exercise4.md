# Quarto Exercise

1. Check if you have the `tidyverse` and `pheatmap` packages installed, if you don't please install them:

    ```
    install.packages("tidyverse")
    install.packages("BiocManager")
    BiocManager::install("pheatmap")
    ```

2. **Download the linked [R script](https://www.dropbox.com/scl/fi/7dexob97xeigu31owv86r/Rscript.R?rlkey=zkpnbcqekwtxndmay8ghnrlhm&st=gp353rr6&dl=1)** and save it within the `quarto_workshop` project directory.

3. Open the Rscript file, **transform the R script into a Quarto Markdown file** by clicking `File` -> `Rename`, and rename it as `Rscript.qmd`.

4. It now has the correct extension for an Quarto Markdown file, but you won't be able to knit it as is. Add the following updates to be able to knit this file:
    - Add a basic YAML header at the top 
    - Create an R chunk for all code underneath each `#` comment in the original R script
    - Comment on the plots (you may have to run the code from the R script to see the plots first)
    - Add a table of contents in the YAML header by referring to these [instructions](https://quarto.org/docs/output-formats/html-basics.html#table-of-contents). YAML is fussy about indentations, make sure you are paying attention to it.
    - (Optional) If you would like to have a button that show/hide your code in the report, you can add an additional argument in the YAML header by referring to this [instruction](https://quarto.org/docs/output-formats/html-code.html#folding-code).
    - Add a code chunk with `sessionInfo()` at the end

5. **Render the markdown**

6. Upload the new Quarto file and the HTML report to the Dropbox link on the schedule page.

[Answer key](https://raw.githubusercontent.com/hbctraining/Tools-for-reproducible-research/master/lessons/Answer_key_Quarto_exercise4.qmd)
