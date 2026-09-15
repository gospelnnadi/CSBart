# CSBart

## CSBart 1.0.1

- Added vignette to the package explaining generic usage. This can be accessed
  by running `browseVignettes('CSBart')`.
  
## CSBart 1.0.2  
  
- Corrected a large bug in how some of the functions handled character vectors
  in data frames, which had the effect of possibly ignoring some predictors.
  
## CSBart 1.0.3

- Corrected a bug in `gcsbart_regression()`, which botched the update of the
  regression coefficients.