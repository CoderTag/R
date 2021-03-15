## Important R Packages

library() function - List all installed packages
search() function - List all packages currently loaded in R environment
install.packages("tidyverse") function -- Install packages
package("package name") funtion - to load package in the environment before use

| S.No | Package Name | Description                                                                                                                                                                   |
| :--- | :----------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | tidyr        | Make the data' tidy'. This package works well with dplyr.                                                                                                                     |
| 2    | dplyr        | Perform data wrangling and data analysis                                                                                                                                      |
| 3    | ggplot2      | Provide elegant and quality graph                                                                                                                                             |
| 4    | ggraph       | It's an extension of ggplot. The limitation of ggplot is dependency on tabular data, is taken away by ggraph.                                                                 |
| 5    | tidyquant    | Financial package. Used to carry out quantitative financial analysis. This is an add to tidyverse universe.                                                                   |
| 6    | dygraphs     | Provide interface to main JS library which we can use for charting. This package used for plotting time-series data.                                                          |
| 7    | leaflet      | Used for creating interactive visualization. It's an open source JS library. New York Times, Github, Flicker etc. uses it                                                     |
| 8    | ggmap        | Used for delineating spatial visualization. Consist of various tools for geolocating and routing                                                                              |
| 9    | glue         | Used to perform operations of data wrangling. Also used for evaluating R expression present in the string.                                                                    |
| 10   | shiny        | Used to develop interactive and aesthetically pleasing web apps. It provides various extensions with HTML widgets, CSS and JS                                                 |
| 11   | plotly       | Provides online interactive and quality graphs.Extends upon JS library plotly.js                                                                                              |
| 12   | tidyext      | Provides various functions of text mining for word processing and carrying out analysis through ggplot, dplyr and other miscellaneous tools.                                  |
| 13   | stringr      | Provides simplicity and consistency to use wrappers for 'stringi' package. stringi package facilitates common string operations.                                              |
| 14   | reshape2     | facilitates flexible reorganization and aggregation of data using melt() and decast() functions.                                                                              |
| 15   | dichromat    | Used to remove red-green or blue-green contrasts from colors                                                                                                                  |
| 16   | digest       | Used to create cryptographic hash objects of R functions.                                                                                                                     |
| 17   | MASS         | provides a large number of statistical functions. It provides datasets that are in conjunction with the book "Modern Applied Statistics with S."                              |
| 18   | caret        | to perform classification and regression tasks.CaretEnsemble is a feature of caret which is used for the combination of different models.                                     |
| 19   | e1071        | useful functions which are essential for data analysis like Naive Bayes, Fourier Transforms, SVMs, Clustering, and other miscellaneous functions.                             |
| 20   | sentimentr   | provides functions for carrying out sentiment analysis. It is used to calculate text polarity at the sentence level and to perform aggregation by rows or grouping variables. |

## Data Types

| Data Types | Example                       | Description                                                                          |
| :--------- | :---------------------------- | :----------------------------------------------------------------------------------- |
| Logical    | True, False                   |                                                                                      |
| Numeric    | 12,32,112,5432                | Decimal value is called numeric in R, and it is the default computational data type. |
| Integer    | 3L, 66L, 2346L                | L tells R to store the value as an integer,                                          |
| Complex    | Z=1+2i, t=7+3i                | A complex value in R is defined as the pure imaginary value i.                       |
| Character  | 'a', '"good'", "TRUE", '35.4' | We convert objects into character values with the help ofas.character() function.    |
| Raw        |                               | holds raw bytes.                                                                     |

```
> R --version
R version 3.6.3 (2020-02-29) -- "Holding the Windsock"

> logical_var <- TRUE
> logical_var
[1] TRUE
> class(logical_var)
[1] "logical"

> num_var <- 43
> num_var
[1] 43
> class(num_var)
[1] "numeric"

> int_var <- 232L
> int_var
[1] 232
> class(int_var)
[1] "integer"

> com_var <- 3+4i
> com_var
[1] 3+4i
> class(com_var)
[1] "complex"

> char_var <- "Sunny Day"
> char_var
[1] "Sunny Day"
> class(char_var)
[1] "character"

> raw_var <- charToRaw(char_var)
> raw_var
[1] 53 75 6e 6e 79 20 44 61 79
> class(raw_var)
[1] "raw"


```

## Data Structures

Everything in R is an object.

| Data structure | Example     | Description                                                                                                                                                                                        |
| :------------- | :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Atomic vector  |             | A vector is the basic data structure in R.There are six types of atomic vectors such as logical, integer, character, double, and raw.A vector can be one of the two types: Atomic vector and Lists |
| List           |             | A list contains a mixture of data types. The list is also known as vectors.We can create a list with the help of list() or as.list(). We can use vector() to create a required length empty list.  |
| Array          |             |                                                                                                                                                                                                    |
| Matrices       | True, False |                                                                                                                                                                                                    |
| Data Frame     | True, False |                                                                                                                                                                                                    |
| Factors        | True, False |                                                                                                                                                                                                    |
