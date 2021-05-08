# DDS2021

Doing Data Science 2021

## prettydoc

Per [GitHub documentation](https://github.com/yixuan/prettydoc), `toc_float` does not work with `prettydoc`.
This customized theme, mainly based on [*Architect*](https://github.com/jasonlong/architect-theme),
combines beautiful typography with a floating table of contents.

### How to use it

1. Install package `prettydoc` in R.
2. Add `morris.html` to `RPATH\library\prettydoc\resources\templates`.
3. Add `morris.css` and `morris.min.css` to `RPATH\library\prettydoc\resources\css`.
4. Code at the preamble of `.Rmd` file as following:
  ```
  output:
    prettydoc::html_pretty:
      theme: morris
      highlight: github
      toc: TRUE
  ```
