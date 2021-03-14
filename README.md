# R
R Practice

## Package

library() function - List all installed packages
search() function - List all packages currently loaded in R environment
install.packages("tidyverse") function -- Install packages
package("package name") funtion - to load package in the environment before use

Important packages -
S.No | Package Name | Description
| :--- | :--- | :---
1  | tidyr | Make the data' tidy'. This package works well with dplyr.
2  | dplyr | Perform data wrangling and data analysis
3  | ggplot2 | Provide elegant and quality graph
4  | ggraph | It's an extension of ggplot. The limitation of ggplot is dependency on tabular data, is taken away by ggraph.
5  | tidyquant | Financial package. Used to carry out quantitative financial analysis. This is an add to tidyverse universe.
6  | dygraphs | Provide interface to main JS library which we can use for charting. This package used for plotting time-series data.
7  | leaflet | Used for creating interactive visualization. It's an open source JS library. New York Times, Github, Flicker etc. uses it
8  | ggmap | Used for delineating spatial visualization. Consist of various tools for geolocating and routing
9  | glue | Used to perform operations of data wrangling. Also used for evaluating R expression present in the string.
10  | shiny | Used to develop interactive and aesthetically pleasing web apps. It provides various extensions with HTML widgets, CSS and JS 
11  | plotly | Provides online interactive and quality graphs.Extends upon JS library plotly.js 
12  | tidyext | Provides various functions of text mining for word processing and carrying out analysis through ggplot, dplyr and other miscellaneous tools.
13  | stringr | Provides simplicity and consistency to use wrappers for 'stringi' package. stringi package facilitates common string operations. 
14  | reshape2 | facilitates flexible reorganization and aggregation of data using melt() and decast() functions. 
15  | dichromat | Used to remove red-green or blue-green contrasts from colors 
16  | digest | Used to create cryptographic hash objects of R functions.
17  | MASS | provides a large number of statistical functions. It provides datasets that are in conjunction with the book "Modern Applied Statistics with S."
18  | caret | to perform classification and regression tasks.CaretEnsemble is a feature of caret which is used for the combination of different models.
19  | e1071 | useful functions which are essential for data analysis like Naive Bayes, Fourier Transforms, SVMs, Clustering, and other miscellaneous functions.
20  | sentimentr | provides functions for carrying out sentiment analysis. It is used to calculate text polarity at the sentence level and to perform aggregation by rows or grouping variables.



```
$nvm --version
0.35.2

$node --version
v12.14.0

 $nvm list
->     v12.14.0
       v12.18.2
         system
default -> 12.14.0 (-> v12.14.0)
node -> stable (-> v12.18.2) (default)
stable -> 12.18 (-> v12.18.2) (default)

$nvm install 12.19
Downloading and installing node v12.19.0...
Downloading https://nodejs.org/dist/v12.19.0/node-v12.19.0-linux-x64.tar.xz...
################################################################################################################################################################# 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v12.19.0 (npm v6.14.8)

$nvm list
       v12.14.0
       v12.18.2
->     v12.19.0
         system
default -> 12.14.0 (-> v12.14.0)
node -> stable (-> v12.19.0) (default)
stable -> 12.19 (-> v12.19.0) (default)

$node --version
v12.19.0

$nvm uninstall 12.14.0
Uninstalled node v12.14.0

$nvm list
       v12.18.2
->     v12.19.0
         system
default -> 12.14.0 (-> N/A)
node -> stable (-> v12.19.0) (default)
stable -> 12.19 (-> v12.19.0) (default)

# Always set the latest node version as default
$nvm alias default node
default -> node (-> v12.19.0)

$nvm list
       v12.18.2
->     v12.19.0
         system
default -> node (-> v12.19.0)
node -> stable (-> v12.19.0) (default)
stable -> 12.19 (-> v12.19.0) (default)
```

