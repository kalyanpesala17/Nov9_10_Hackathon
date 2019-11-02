You will need Jupyter notebooks installed to work with the script included here - you can view a pdf version of the script here as well.

Additionally, in order to run this script you need to download data from this link: (you will have to create an account
on the site but it's free)
 - https://loanperformancedata.fanniemae.com/lppub/index.html#Portfolio

Additional details about these datasets (attribute names, allowable values, definitions, etc:
is available from here:
 - https://www.fanniemae.com/portal/funding-the-market/data/loan-performance-data.html

Download the data the 3rd Quarter for the years 2004, 2008, 2012, and 2016. 
Unzip the data files into the "RawData" directory and then execute the nupyter notebook to get an idea of how to work with the data and conduct analysis.

Using the data you've downloaded from the links above, identify which attributes (and with what values) correlate the most with prepaid and defaulted mortages for each of the 4 years? Is there some attribute that remains significant across all four years of do the highly correlated attributes vary from year to year?

Some examples of the "risk factors" that could be relevant include: 
 - Loans in a particular zip code
 - Loans with ranges of LTV (loan to value) on the initial house purchase
 - Number of borrowers or rooms in the house
 
As an example - if you discover many prepaid loans in Florida or southern Texas - is it possible those prepaids are the result of insurance companies paying off damaged or destroyed houses?

You may use any tool you like for reporting / visualization including Matplotlib, D3.js, Tableau, etc. If you would like you could also integrate Google maps, or build an AR/VR style app (either for your phone / tables or an actual VR headset.)

In addition to downloading the data from the above link you will need to have the following libraries installed in order to run the notebook. (In addition to having Jupyter itself installed).

 - os
 - glob
 - pandas
 - numpy
 - seaborn
 - matplotlib
