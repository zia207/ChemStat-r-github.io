---
title: ''
---

<div style="margin-bottom:20px;">
</div>

<img src="Image/PNG_FILE_01/getting_started.png" width="100%" style="display: block; margin: auto;" />

<div style="margin-bottom:20px;">
</div>


### **Table of Content**

* [What is R?](#what-is-r) 

* [Download R](#download-r)

* [Install R on Windows](#install-r-on-windows)

* [Install R on Mac OSX](#install-r-on-mac-osx)

* [Install R on Ubuntu](#install-r-on-ubuntu)

* [Open R-Base](#open-r-base)

* [Integrated Development Environment for R](#integrated-development-environment-for-r)

* [Download and Installation RStudio](#download-and-installation-rstudio)

  - [Open RStudio](#open-rstudio)
  
  - [Change RStudio Appearance and  Themes](#change-rstudio-appearance-and-themes)
  
* [R Packages or Libraries](#r-packages-or-libraries)

* [R Markdown](#r-markdown)

<div style="margin-bottom:30px;">
</div>


### **What is R?** 

[R](https://www.r-project.org/) is one of the most popular open-source statistical computing and visualization environments. It was developed in 1980 based on the [S-language](https://en.wikipedia.org/wiki/S_(programming_language)), and an open-source community regularly updates the software for a robust, programmable, portable, and open-source computing environment. We can use it to solve complex and sophisticated problems and "routine" analysis without restrictions on access or use.

<div style="margin-bottom:20px;">
</div>

### **Download R**

The R can be downloaded from the [R project](https://www.r-project.org/) of a repository CRAN or you can install [Microsoft R Open](https://mran.microsoft.com/download),  the enhanced distribution of R from Microsoft. It is a complete and free open source platform for statistical analysis and data science 

1.	Click [this link](https://www.r-project.org//) to download the latest stable version of R 
2.	Select a CRAN location (a mirror site) and please choose a location close to you
3.	Click on the "Download R for Windows" link at the top of the page.  
4.	Click on the "install R for the first time" link at the top of the page.
5.	Click "Download R for Windows" and save the executable file somewhere on your computer.





```{=html}
<div class="vembedr">
<div>
<iframe src="https://www.youtube.com/embed/bvoMiKKVf4U" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```

<div style="margin-bottom:20px;">
</div>


### **Install R on Windows** 

Installation instruction of R  in Windows and MAC could be found  [here](https://courses.edx.org/courses/UTAustinX/UT.7.01x/3T2014/56c5437b88fa43cf828bff5371c6a924/). Detail Installation steps of Microsoft R Open in different operating systems can be found [here](https://mran.microsoft.com/documents/rro/installation). 

1. Open Windows Explorer
2. Navigate to the directory where the downloaded R.4.2.1-win.exe (the latest version) file is exit. 
3. Double-click this **exe** file and follow the instruction as shown in the video below: 


```{=html}
<div class="vembedr">
<div>
<iframe src="https://www.youtube.com/embed/JmQ-GAidTWk" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```
<div style="margin-bottom:20px;">
</div>

### **Install R on Mac OSX**

Installing R on Mac OS is similar to Windows.  The easiest way is to install it through CRAN by going to the CRAN downloads page and following description as  as shown [here](https://itslinuxfoss.com/install-r-ubuntu-22-04/)

<div style="margin-bottom:20px;">
</div>

### **Install R on Ubuntu**  

The installation of R in Ubuntu little tricky for those who are not familiar with command line. Details R installation on Ubuntu 19.04/18.04/16.04 could be found [here](https://itslinuxfoss.com/install-r-ubuntu-22-04/).  

<img src="Image/PNG_FILE_02/r_ubuntu.png" width="90%" style="display: block; margin: auto;" />
<div style="margin-bottom:20px;">
</div>



### **Open R-Base** 

After R installation in Windows, double click on the desktop icon or open the program from START to run R.  R will be open as a **Console**  window. 
You can work in the console and use R with the command line. However, the command line can be pretty daunting to a beginner. It is better to work in **R Editor**.  First, you must create a **New script**  from  **File** menu. Any code you run in R-script output will be displayed in the console window. We can save all your R codes as an R script file and output them in the console as an R-Data file.
 

```{=html}
<div class="vembedr">
<div>
<iframe src="https://www.youtube.com/embed/cIubYlD5UVY" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```
<div style="margin-bottom:20px;">
</div>


## **Integrated Development Environment for R**

R can be run in the command line  and graphical user interfaces in [integrated development environment (IDE)](https://en.wikipedia.org/wiki/Integrated_development_environment). Below are the best programming IDE for R: 

1. [RStudio](https://www.rstudio.com/)
2. [R Tools for Visual Studio](https://docs.microsoft.com/en-us/visualstudio/rtvs/installing-r-tools-for-visual-studio?view=vs-2017)
3. [Rattle](https://rattle.togaware.com/) 
4. [ESS](https://www.dunebook.com/best-r-programming-ide/) 
5. [Tinn-R](https://tinn-r.software.informer.com/) 
6. [R AnalyticalFlow](https://r.analyticflow.com/en/)
7. [Radiant](https://radiant-rstats.github.io/docs/install.html)
8. [RBox](https://atom.io/packages/rbox)
9. [Code](https://code.visualstudio.com/)

<div style="margin-bottom:15px;">
</div>

### **Download and Installation RStudio**

[RStudio](https://www.rstudio.com/) is one of the best [integrated development environment  (IDE)](https://en.wikipedia.org/wiki/Integrated_development_environment) for R that includes a [console](https://support.rstudio.com/hc/en-us/articles/200404846-Working-in-the-Console), a [terminal](https://support.rstudio.com/hc/en-us/articles/115010737148-Using-the-RStudio-Terminal-in-the-RStudio-IDE) syntax-highlighting editor that supports direct code execution, as well as tools for plotting, history, debugging and workspace management. RStudio Desktop and RStudio Server for Windows, Mac, and Linux are open sources. 

First, you have to download the latest version of RStudio according to your operating system from [here](https://www.rstudio.com/products/rstudio/download/#download). 
For windows user, and just run the installation file and it normally detects your latest installed R version automatically. If you want to do some extra configuration, you need follow  some steps which can be found [here](http://www.dummies.com/programming/r/how-to-install-and-configure-rstudio/)

For installation instruction of R and RStudio in Mac OS could be found [here](https://web.stanford.edu/~kjytay/courses/stats32-aut2018/Session%201/Installation%20for%20Mac.html). 
Installing R Studio on Ubuntu could be found [here](https://www.geeksforgeeks.org/how-to-install-r-studio-on-windows-and-linux/)

<div style="margin-bottom:15px;">
</div>

### **Open RStudio**

We may open RStudio just double click Rstudio icon on your Desktop or on the task bar. It has several components: console, terminal, editors, global environment etc. 


```{=html}
<div class="vembedr">
<div>
<iframe src="https://www.youtube.com/embed/cEykrCTWOC8" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```
<div style="margin-bottom:20px;">
</div>



### **Change RStudio Appearance and Themes**

Navigate to **Tools → Global options → Appearance** and switch the theme in the Editor Theme option. By default, you will have the Textmate theme activated. There is a wide in-built variety of themes to choose, from light to dark themes


```{=html}
<div class="vembedr">
<div>
<iframe src="https://www.youtube.com/embed/dmhqWm4an6g" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```

<div style="margin-bottom:20px;">
</div>


https://youtu.be/dmhqWm4an6g 

## **R Packages or Libraries** 

R Packages are collections of R functions, data, and compiled code in a well-defined format. The directory where packages are stored is called the **library**. We can install any R 'package' or multiple package  directly from the console, using r-script and GUI (Tools > Install Packages) through internet. 

Use **install.packages()** function in your console or in  a script:     



```r
# One package
# install.packages("raster", dependencies = TRUE)

# Multiple packages
# install.packages(c("raster","gstat"), dependencies = TRUE)
```


```{=html}
<div class="vembedr">
<div>
<iframe src="https://www.youtube.com/embed/xBh7Ti6cvXs" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```

<div style="margin-bottom:30px;">

https://youtu.be/xBh7Ti6cvXs 

###  **Use Libraries in R**

To use any installed libraries, simply type the **library()** function with the name of the library in brackets. For example


```r
library(spatial)
```

If we want see content of any library, just use **help()** function 


```r
#library(help=spatial)
```


<div style="margin-bottom:30px;">

## **R Markdown**

Markdown is a lightweight markup language for creating formatted text using a plain-text editor. John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code form. Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files. (source: [wikipedia)](https://en.wikipedia.org/wiki/Markdown)


R Markdown provides an authoring framework for data science. You can use a single R Markdown file to both 
save and execute code generate high quality reports that can be shared with an audience R Markdown documents are fully reproducible and support dozens of static and dynamic output formats. This 1-minute video provides a quick tour of what’s possible with R Markdown (source: [R Markdown)](https://rmarkdown.rstudio.com/index.html)


```{=html}
<div class="vembedr">
<div>
<iframe src="https://www.youtube.com/embed/vIcbLhC9whM" width="533" height="300" frameborder="0" allowfullscreen="" data-external="1"></iframe>
</div>
</div>
```

https://youtu.be/vIcbLhC9whM

<div style="margin-bottom:15px;">

For a brief a brief tutorial, please visit [here](https://rmarkdown.rstudio.com/lesson-2.html)


<div style="margin-bottom:15px;">

Below the  cheatsheets that  for  RStudio IDE:  

<img src="Image/PNG_FILE_01/rarkdown_cheat_sheet_01.png" width="100%" style="display: block; margin: auto;" />

<div style="margin-bottom:15px;">

<img src="Image/PNG_FILE_01/rarkdown_cheat_sheet_02.png" width="100%" style="display: block; margin: auto;" />

<div style="margin-bottom:15px;">

For a brief a brief tutorial, please visit [here](https://rmarkdown.rstudio.com/lesson-2.html)
