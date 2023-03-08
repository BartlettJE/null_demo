# A whole lotta nothing: Comparing statistical approaches to supporting the null

Talk for the [Methods and Metascience group](https://psyteachr.github.io/mms/) at the University of Glasgow. 

In this talk, I provide a brief overview of different approaches to testing some kind of null effect. I use a data set from Ditta and Woodward (2022) who compared a hand calculation-based course and an R coding-based course.

In the original article, they found no significant difference between the courses and briefly reported Bayes Factors, but I compare the inferences you can make using three approaches: 

1. Equivalence testing 

2. Bayes factors 

3. Bayesian modelling and region of practical equivalence (ROPE)

# Using the files

In the Github repo, there are two key files: 

- null_slides.html - These are the rendered verison of the slides which you can view via Github pages: https://bartlettje.github.io/null_demo/null_slides.html

- null_slides.qmd - This is the background Quarto file I used to create the slides and apply the analysis techniques. If you want to try the methods out yourself, the data is available in the [data folder from Ditta and Woodward's OSF project](https://osf.io/rnkfa). Please download the data from their OSF project first as they admirably shared the data for their study. I renamed the file `Ditta_data.csv`, but you will need to edit the file name on line 69 if you call it something else. You can then see the commented code for running the analyses. 

# References

Ditta, A. S., & Woodward, A. M. (2022). Technology or tradition? A comparison of students’ statistical reasoning after being taught with R programming versus hand calculations. *Scholarship of Teaching and Learning in Psychology*. https://doi.org/10.1037/stl0000327
