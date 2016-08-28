# FutureLearnData: R data package for the Data to Insight MOOC

This package is primarly created for use with [iNZight](https://www.stat.auckland.ac.nz/~wild/iNZight).

## Contents

The R package contains these datasets:
- Gapminder
  - `gapminder`, data from 1952--2012
  - `gapminder-2008`, data for just 2008
- NHANES
  - `nhanes2009_2012`, modified data from 2009--2012
  - `nhanes_1000_50`, `nhanes_1000`, `nhanes_2000`, the first 50, 1000, and 2000 rows, respectively
- `olympics100m`, some olympics data
- Week 7 Datasets
  - `CanadaPop`, an experiment
  - `CocaineTrtmtExpt`, `CocaineTrtmtExpt-2Trt`, `CocaineTrtmtExpt-2Trt_D_P`, `CocaineTrtmtExpt_Lith_Desip`, an experiment and each two-treatment subset
  - `LightatNight`, an experiment on mice
  - `MindsetMatters`, an experiment on mindset effects on placebo
  - `SleepDeprivationExpt`, an experiment on sleep deprivation
- Week 7 Datasets (time series)
  - `Actual_VisitorArrivalsMonthlyFrom1998`, monthly arrivals into New Zealand by country of origin
  - `Actual_VisitorArrivalsQuarterlyFrom1998`, quarterly arrivals into New Zealand by country of origin
  - `AverageVisitorsMonthly`, average monthly visitors by country of origin
  - `AverageVisitorsQuarterly`, average quarterly visitors by country of origin

## Usage

To load, for example, the "Gapminder 2008" data set, just run these commands in R:
```{r}
library(FutureLearnData)
data('gapminder-2008')
```
