# DataW
Code for workshop

  CODE FOR DATA WRANGLING WEB WORKSHOP LECTURE

*******************************************************************************************;
PACKAGES:

install.packages("quantmod")

install.packages("fImport")
install.packages("downloader")

********************************************************************************************************************;
PURPOSE:

Economic and Financial data:


fImport: Package of utility functions to download and manage data sets from the Internet or from other
sources.

Exercies 1

Collecting economic data series from FRED using fimport package

library(fImport)
library(downloader)

options(download.file.method="wininet")
 or on mac
options(download.file.method="libcurl")
options(download.file.method="libcurl")


DPRIME <- fredSeries("DPRIME") 




Exercies 2

Get dividends from microsoft office.

library(quantmod)

getDividends(MSFT)


-----------------------------------------------------------------------------------------;
Work Cited

National Research Council. “Principles and Practices for a federal Statistical Agency”.  3rd edition

OMB. “Statistical Programs of the US Government 2011”.

Baumhol ,Bernard. “ The Secrets of Economic Indicators”. 2nd ed 2010.



R packages WORK CITED

FIMPORT. Diethelm Wuertz and many others."fimport" https://cran.r-project.org/web/packages/fImport/fImport.pdf
QUANTMOD. Jeffrey A. Ryan, Joshua M. Ulrich, Wouter Thielen,Joshua M. Ulrich. "quantmod".https://cran.r-project.org/web/packages/fImport/fImport.pdf 
DOWNLOADER. Winston Chang."downloader". https://cran.r-project.org/web/packages/downloader/downloader.pdf

Kevin Wright. agridat. R. http://www.inside-r.org/packages/cran/agridat/docs/agridat

Michael kao. FAOSTAT. R .http://www.r-bloggers.com/a-package-for-agricultural-statistic-faostat/
December 23, 2015.
