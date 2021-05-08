# DDS2021
Doing Data Science 2021

## prettydoc
Please install the package `prettydoc` in R.
This template is based on `architect`.
You can add the `html` file to `RPATH\library\prettydoc\resources\templates` and `css` file to `RPATH\library\prettydoc\resources\css`.
Code at the head as following:
```
output:
  prettydoc::html_pretty:
    theme: morris
    highlight: github
    toc: TRUE
```
