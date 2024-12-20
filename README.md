# R for Research: Exploratory Data Analysis using `ggplot2` and the `tidyverse`

An LSHTM Talent and Educational Development module introducing the `ggplot2` package for data visualisation and other packages in the `tidyverse` for data manipulation.

The slides can be found in `slides/`.

The practical instructions can be found in `practicals/`.

Data on FEV1 contained in this repository is sourced from the [ALA](https://rdrr.io/rforge/ALA/) package. A simple data dictionary is as follows:

| Variable | Type    | Description                                                  | Units  | Type   |
| :------- | :------ | :----------------------------------------------------------- | :----- | :----- |
| `id`     | Factor  | ID label for each participant                                | None   | factor |
| `age`    | Numeric | Age of participant at time of measurement                    | years  | double |
| `height` | Numeric | Height of participant at time of measurement                 | metres | double |
| `FEV1`   | Numeric | Spirometry measurement of lung function, forced exhaled volume in first second | litres | double |

Data are originally from [Dockery et al. (1983)](https://doi.org/10.1164/arrd.1983.128.3.405); this is a random sample of 300 girls living in Topeka, Kansas.

This resource is forked from material produced by Sam Clifford for the [LSHTM 2491 Data Challenge](https://github.com/samclifford/2491_eda) module.
