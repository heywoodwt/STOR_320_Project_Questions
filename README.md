# College Basketball Efficiency Analysis

Two research questions from a STOR 320 project on Division I college basketball,
worked in R Markdown against a season-level team dataset.

**Q7** — What is the correlation between adjusted offensive and adjusted defensive
efficiency within each team? Computed per team, then plotted as a distribution to see
whether strong offenses tend to come at the cost of defense.

**Q8** — Follow-on analysis of the same efficiency metrics.

Uses `tidyverse`, `ggplot2`, `corrplot`, and `gganimate`.

## Running it

```r
install.packages(c("tidyverse", "gganimate", "ggpubr", "vctrs", "corrplot"))
rmarkdown::render("main_markdown.rmd")
```

`CollegeBasketball.csv` holds the team-season data.

## License

MIT
