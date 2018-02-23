# SwappingSounds

## Background of the project

This repo is an offshoot of a larger project I'm working on. I'm looking at how acoustic changes to the sounds that we use in langauge affect our ability to clearly communicate. This repo comes from an attempt to see whether hypothetical versions of English with the acoustics of two of our language sounds swapped would be hypothetically _easier_ or _harder_ to understand. 

Because of a bug in the code, initial inspections seemed to suggest that swapping basically any two sounds in English made it harder to understand. It's more complicated than this, but if that were true, it would be an interesting hint at certain types of optimizations happening behind the scenes. However, after I realized and fixed this bug, the results were not so obvious and I put this question on the backburner.

## Why I uploaded this

I uploaded this excerpt as a way of showcasing how far I've come in terms of managing large amounts of data in R, and how useful the tidyverse is. 

In `swapping_plots.Rmd`, which I made after I had learned a lot about `purrr` and the tidyverse, you can see how I read hundreds of files and save them hierarchically into a single data frame. From there I manipulate them in a variety of ways to investigate the hypotheses I had visually, and it's very compact and tidy. (However, since I intended it only to be used for personal perusal of the data, things aren't really labelled in a way that the layperson could probably understand.)

I wrote `pre_tidyverse_loading.Rmd` before I learned all of this. It's from a different part of the project, and not runnable with the data here, but you can see how **horrible** it was. I actually used _Python_ to automatically generate most of the R code. It was that bad.

