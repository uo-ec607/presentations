# Student presentations

Please push your presentations to this repo as separate sub-directories, indicating the order that you presented, your name, and a v. brief description, all separated by dashes. E.g.: `01-FirstnameLastname-Topic/`.

## R Markdown

Please try to make your presentations using [R Markdown](https://rmarkdown.rstudio.com/). You can use any one of the multiple slide deck options. (For what it's worth, I use the [xaringan package with metropolis theme](https://github.com/yihui/xaringan/wiki/Themes) for my lecture slides). Or you can output as a [GitHub document](https://rmarkdown.rstudio.com/github_document_format.html) or [HTML document](https://bookdown.org/yihui/rmarkdown/html-document.html). If you choose the latter, I would request that you please include `keep_md: true` in your YAML, so that it is readable directly on GitHub.

## Topics

Topics will be allocated on a first-come-first-served basis. Each person is expected to present twice. Please add your name to the table below (you can [edit this README](https://help.github.com/articles/editing-files-in-your-repository/) directly on GitHub) as soon as you have chosen. Note, however, that "open" presentation topics need to be approved first. I've given a list of suggested ideas towards the bottom of this page. I would also prefer that some topics are only presented after specific lectures, but we can discuss that after you chosen.

| Lecture | Topic | Resources | Presenter |
|---------|-------|-----------|-----------|
| 1 | None | NA | NA | 
| 2 | R Markdown | [a](https://rmarkdown.rstudio.com/), [b](https://bookdown.org/yihui/rmarkdown/) |  | 
| 3 | GitKraken (or other GUI) | [a](https://www.gitkraken.com/), [b](https://www.sourcetreeapp.com/), [c](https://desktop.github.com/), [d](https://github.atom.io/), [e](https://code.visualstudio.com/docs/introvideos/versioncontrol) |  |
| 4 |  |  |  |
| 5 | Tidy data | [a](https://tidyr.tidyverse.org/articles/tidy-data.html), [b](https://vita.had.co.nz/papers/tidy-data.pdf)  |  | 
|   | tinyverse | [a](http://www.tinyverse.org/) |  | 
| 6 |  |  |  | 
|   | SelectorGadget | [a](https://cran.r-project.org/web/packages/rvest/vignettes/selectorgadget.html) |  | 
| 7 | APIs | [a](https://zapier.com/learn/apis/) |  | 
| 8 | Regular expressions | [a](http://stat545.com/block022_regular-expression.html), [b](https://www.garrickadenbuie.com/project/regexplain/), [c](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf) |  | 
| 9 | CRS | [a](https://geocompr.robinlovelace.net/spatial-class.html#crs-intro), [b](https://www.nceas.ucsb.edu/~frazier/RSpatialGuides/OverviewCoordinateReferenceSystems.pdf) |  | 
| 10 |  |  |  | 
| 11 | Tidyeval | [a](https://dplyr.tidyverse.org/articles/programming.html), [b](https://tidyeval.tidyverse.org/) |  | 
| 12 |  |  |  |
| 13 |  |  |  |  
| 14 |  |  |  |
| 15 |  |  |  | 
| 16 |  |  |  | 
| 17 |  |  |  | 
| 18 |  |  |  | 
| 19 | Big data  | [a](https://www.aeaweb.org/articles?id=10.1257/jep.28.2.3), [b](https://www.aeaweb.org/articles?id=10.1257/aer.p20151023), [c](https://www.aeaweb.org/articles?id=10.1257/jep.31.2.87)  |  | 
| 20 |  |  |  | 

### Open topic and package suggestions

Don't feel limited to these, but here are some suggestions for the open topic slots:

#### Bayesian
- [greta](https://greta-stats.org/)
- [rstan](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started) or derivatives ([brms](https://paul-buerkner.github.io/brms/), [rstanarm](http://mc-stan.org/rstanarm/), etc.)

#### C++
- [Rcpp](http://dirk.eddelbuettel.com/code/rcpp.html) (Note: You may want to start with a short introduction like [this](https://csgillespie.github.io/efficientR/performance.html#rcpp) or [this](https://adv-r.hadley.nz/rcpp.html))

#### Communication
- [blogdown](https://bookdown.org/yihui/blogdown/)
- [Shiny](https://shiny.rstudio.com/)

#### Education

- [learnr](https://rstudio.github.io/learnr/)
- [R/exams](http://www.r-exams.org/)

#### Julia
- [RCall](http://juliainterop.github.io/RCall.jl/stable/index.html) 
- [JuliaCall](https://non-contradiction.github.io/JuliaCall/index.html) or [Julia ConnectoR](https://github.com/stefan-m-lenz/JuliaConnectoR)

#### Packages

- Various good posts and examples, including [here](https://r-mageddon.netlify.app/post/writing-an-r-package-from-scratch/), [here](https://www.hvitfeldt.me/blog/usethis-workflow-for-package-development/), and [here](https://zenartofrpkgs.netlify.app)

#### Python
- [Conda](https://conda.io/docs/) and/or [Jupyter Notebooks](https://jupyter.org/)
- [Reticulate](https://rstudio.github.io/reticulate/)

#### Social and networks
- [ggraph](https://ggraph.data-imaginist.com/) and [tidygraph](https://tidygraph.data-imaginist.com/)
- [rtweet](https://rtweet.info/)
- [wikipediatrend](https://github.com/petermeissner/wikipediatrend/)

#### Text / NLP
- [tidytext](https://juliasilge.github.io/tidytext/)

#### Time-series and forecasting
- [prophet](https://facebook.github.io/prophet/)
- [tsibble](https://tsibble.tidyverts.org/) and/or [fable](https://fable.tidyverts.org/)
- [zoo](https://cran.r-project.org/web/packages/zoo/index.html)

#### Workflow and automation
- [renv](https://rstudio.github.io/renv)
- [GNU Make](https://www.gnu.org/software/make/) (Good, short intros [here](https://stat545.com/automating-pipeline.html) and [here](http://zmjones.com/make/))
- [targets](https://wlandau.github.io/targets/) / [drake](https://ropensci.github.io/drake/)
- [workflowr](https://jdblischak.github.io/workflowr/)
