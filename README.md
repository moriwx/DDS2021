# DDS2021
Doing Data Science 2021

## prettydoc
Install the package in R. Then add the `html` file to `R\library\prettydoc\resources\templates` and `css` file to `R\library\prettydoc\resources\css`.
Example:
```
output:
  prettydoc::html_pretty:
    theme: morris
    highlight: github
    toc: TRUE
```
