Improving Food Security Through Climate Smart Agriculture
================
<Immaculate Juma Haayo>
\<Thursday 7/9 2023\>

- [Student Details](#student-details)
- [Setup Chunk](#setup-chunk)
- [Understanding the Dataset (Exploratory Data Analysis
  (EDA))](#understanding-the-dataset-exploratory-data-analysis-eda)
  - [Loading the Dataset](#loading-the-dataset)
    - [Source:](#source)
    - [Reference:](#reference)

# Student Details

**Student ID Number** \| Immaculate Juma Haayo \|  
**Student Name** \| 134111 \|  
**BBIT 4.2 Group** \| B \|  
**BI Project Group Name/ID (if applicable)** \| GroundBreakers\|

# Setup Chunk

**Note:** the following KnitR options have been set as the global
defaults: <BR>
`knitr::opts_chunk$set(echo = TRUE, warning = FALSE, eval = TRUE, collapse = FALSE, tidy = TRUE)`.

More KnitR options are documented here
<https://bookdown.org/yihui/rmarkdown-cookbook/chunk-options.html> and
here <https://yihui.org/knitr/options/>.

# Understanding the Dataset (Exploratory Data Analysis (EDA))

## Loading the Dataset

### Source:

The dataset that was used can be downloaded here:
<https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset?resource=download>

### Reference:

Ingle,A.(2020). Crop Recommendation Dataset
<https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset?resource=download>

``` r
library(readr)
Crop_recommendation <- read_csv("../data/Crop_recommendation.csv")
```

    ## Rows: 2200 Columns: 8
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (1): label
    ## dbl (7): N, P, K, temperature, humidity, ph, rainfall
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
View(Crop_recommendation)

# Provide the executable R code inside the various code chunks as guided by the lab work.
```

…to be continued
