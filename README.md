# N741_Spring2020_Homework01_RMarkdown
N741-Spring2020: Homework01 Editing RMarkdown and R Code

## ANSWER KEY FILES are now posted

* rmarkdown01_answerKey.Rmd
* rmarkdown01_answerKey.html
* rmarkdown01_answerKey.pdf

## Homework 1: DUE 01/29/2020

This homework focuses on getting started using R, RStudio and Rmarkdown to create a report combining data, code and documentation together.

GITHUB: Fork or download this Github repository to get the files you need for Homework 01: https://github.com/melindahiggins2000/N741_Spring2020_Homework01_RMarkdown

RSTUDIO.CLOUD: You can also access this Homework repository in the RStudio Cloud workspace at https://rstudio.cloud/spaces/6704/join?access_code=bO8SHRY9WbMVzlO0DFDnJDUpgRNYdCla2Io5AiGk

Begin with the file "rmarkdown01.Rmd" - the "SaveAs" the file as your Homework 1 and then make the modifications and additions requested below.

Complete the following:

1. Change the title of the report
2. Change the author of the report to your name
3. Add an additional sentence or two in the `"Specific statistics within text"` section that **embeds the numeric result** for the mean height, standard deviation of the heights. Add this after the sentence that lists the minimum and maximum heights.
    - HINT: the functions you will need are `mean()`, and `sd()`.
4. Add a section that also displays a histogram of the number of rings for the abalones - outline the histogram bars in the color black and fill the color of the bars with the color blue. Add a few sentences about this distribution - what do you observe?
    - HINT: You will need to add a code chunk and add a section heading using two hashtags ## with a header and some text on your observations.
5. Add a section with another scatterplot of the `shuckedWeight` (plotted on the y-axis) against the `visceraWeight` (plotted on the x-axis). Color the points by `sex`. Add a sentence or two on what you see? Does anything seem off or unusual?
    - HINT: again add a code chunk and a section heading ## plus text on your observations on the histogram distribution
6. `knit` your report to HTML or DOC format and then save as a PDF to turn in on Canvas or knit to PDF directly
    - In RStudio.cloud you can `knit` directly to PDF - you may be prompted to install the `tinytex` `R` package. Learn more at https://yihui.name/tinytex/.

* NOTE: You should have 6 sections in your final updated report for Homework 01 - the 4 original section plus the 2 new sections (histogram and scatterplot) you are asked to create above.

---

