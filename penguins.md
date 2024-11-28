Penguins
================
Antariksh Nag
2024-11-28

``` r
data <- mtcars

library(ggplot2)

ggplot(data, aes(x = wt, y = mpg)) +
  geom_point() + 
  theme_bw()
```

![](penguins_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->
