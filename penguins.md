Penguins
================
Antariksh Nag
2024-11-28

This is some analysis done on the mtcars data

``` r
data <- mtcars

library(ggplot2)

ggplot(data, aes(x = wt, y = mpg)) +
  geom_point() + 
  theme_bw()
```

![](penguins_files/figure-gfm/r-1.png)<!-- -->
