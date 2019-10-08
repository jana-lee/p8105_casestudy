Case\_Study
================
Jana Lee
10/8/2019

Load in packages:

``` r
library(p8105.datasets)
data(nyc_airbnb)
view(nyc_airbnb)

options(
  ggplot2.continuous.colour = "viridis",
  ggplot2.continuous.fill = "viridis"
)
scale_colour_discrete = scale_colour_viridis_d
scale_fill_discrete = scale_fill_viridis_d
theme_set(theme_minimal() + theme(legend.position = "bottom"))
```

Brainstorming questions: \* how are airbnb prices related to rent in the
neighborhood? \* which neighborhood is most expensive and which is
cheapest? \* do hosts with multiple sites have higher prices or ratings?
\* does price have any relation to ratings? \* average length of stay
related to neighborhood? price?
etc?

## Exploratory Question: Which neighborhood is most expensive and which is cheapest in Manhattan?
