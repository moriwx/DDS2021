# DDS2021
Doing Data Science 2021

## prettydoc
Install the package in R. Add the `html` file to `R\\library\\prettydoc\\resources\\templates` and `css` file to `R\\library\\prettydoc\\resources\\css`.
You could set the output of `Rmd` as
```
output:
  prettydoc::html_pretty:
    theme: morris
    highlight: github
    toc: TRUE
```
