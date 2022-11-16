---
title: "Import"
author: "Zia Ahmed"
date: "2022-11-10"
output: html_document
---

## Set working dirctory


```r
setwd("D:\\Dropbox\\GitHub\\chemstat-r-github.io\\Data")
```


```r
getwd()
```

```
## [1] "D:/Dropbox/GitHub/chemstat-r-github.io/Data"
```

```r
dir()
```

```
##  [1] "DT.csv"                           "LBC_data.csv"                    
##  [3] "LBC_data.feather"                 "meta_data.txt"                   
##  [5] "PAHdata.csv"                      "rice_arsenic.csv"                
##  [7] "rice_data.csv"                    "rice_data.RData"                 
##  [9] "rice_data.xlsx"                   "test.docx"                       
## [11] "test.html"                        "test.Rmd"                        
## [13] "test_data.csv"                    "test_data.txt"                   
## [15] "test_data.xlsx"                   "ttt.Rmd"                         
## [17] "US_FIPS.csv"                      "US_regions.csv"                  
## [19] "usa_geochemical.csv"              "usa_geochemical_meta_data.csv"   
## [21] "USA_regions.csv"                  "water_soil_rice_arsenic_data.csv"
```



```r
df_csv<-read.csv("LBC_data.csv")
```




```r
df_txt<-read.table("test_data.txt", header=T)
```


```r
tail(df_csv)
```

```
##        FIPS Year SMOKING POVERTY PM25  NO2   SO2 LBC_RATE
## 46600 56045 2007    23.8    8.80 6.05 0.38 0.002    62.34
## 46601 56045 2008    23.8    9.20 5.79 0.46 0.002    61.27
## 46602 56045 2009    24.1    9.90 5.00 0.36 0.002    60.46
## 46603 56045 2010    24.6    9.90 4.01 0.32 0.001    59.49
## 46604 56045 2011    26.1   11.50 4.53 0.33 0.001    59.44
## 46605 56045 2012    25.0   10.15 5.65 0.38 0.001    58.54
```


```r
str(df_csv)
```

```
## 'data.frame':	46605 obs. of  8 variables:
##  $ FIPS    : int  1001 1001 1001 1001 1001 1001 1001 1001 1001 1001 ...
##  $ Year    : int  1998 1999 2000 2001 2002 2003 2004 2005 2006 2007 ...
##  $ SMOKING : num  27 26 26 26.5 26.6 26.3 27.1 26.4 26.3 25.6 ...
##  $ POVERTY : num  11.3 11.4 10.5 10.8 10.3 10.4 11.6 10.4 12.5 10.4 ...
##  $ PM25    : num  17.1 15.4 14 13.9 14.8 ...
##  $ NO2     : num  1.38 1.04 1.47 1.74 1.1 0.9 1.1 1.17 0.84 0.77 ...
##  $ SO2     : num  0.057 0.055 0.054 0.051 0.052 0.053 0.05 0.055 0.055 0.056 ...
##  $ LBC_RATE: num  90.6 90.4 89.5 89.3 89.2 ...
```


```r
library(xlsx)
```


```r
df_xlsx <-read.xlsx("test_data.xlsx", 1) 
```



Variety =c("BR1","BR3", "BR16", "BR17", "BR18", "BR19","BR26",
          "BR27","BR28","BR29","BR35","BR36") # create a text vector
Yield = c(5.2,6.0,6.6,5.6,4.7,5.2,5.7,
                5.9,5.3,6.8,6.2,5.8) # create numerical vector
rice.data= data.frame(Variety, Yield)



```r
Variety =c("BR1","BR3", "BR16", "BR17", "BR18", "BR19","BR26",
          "BR27","BR28","BR29","BR35","BR36")
```



```r
Yield = c(5.2,6.0,6.6,5.6,4.7,5.2,5.7,
                5.9,5.3,6.8,6.2,5.8) # create numerical vector
```



```r
rice.data= data.frame(Variety, Yield)
```



