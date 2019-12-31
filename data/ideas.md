## Datasets for class


+ Known datasets already:
	+ crabs
	+ biopsy
	+ olive
	+ wine

+ `portal_data_joined.csv` is an ecological dataset from [Data Carpentry](https://datacarpentry.org/R-ecology-lesson/) (contains useful exercises as well)
	+ [Figshare link](https://ndownloader.figshare.com/files/2292169)
	+ "We are studying the species repartition and weight of animals caught in plots in our study area"

+ `dslabs::us_contagious_diseases` for fuck you antivaxxers

```
> head(dslabs::us_contagious_diseases)
```

+ `dslabs::brca` (from UCI ML Repo)
	+ A list of two matrices describing breast cancer samples where matrix named `x` gives features and `y` tells if benign or malignant. 
	+ Can be used for data wrangling (creating a tibble), binary classification
+ `gapminder`

```
> head(gapminder)
              country year infant_mortality life_expectancy fertility population          gdp continent


+ Two climate datasets: `greenhouse_gases` has levels over time for CO2, CH4, NO2 (yes over 2000 years), and `historic_co2` contain ice core and mauna loa co2 levels

```
> head(dslabs::greenhouse_gases)

> head(historic_co2)
```