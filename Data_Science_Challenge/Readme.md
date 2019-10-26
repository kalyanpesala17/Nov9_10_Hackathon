You will need Jupyter notebooks installed to view/execute the example script included here.

Additionally, in order to run this script you need to download data from this link: (you will have to create an account
on the site but it's free)
 - https://loanperformancedata.fanniemae.com/lppub/index.html#Portfolio

Additional details about these datasets (attribute names, allowable values, definitions, etc:
is available from here:
 - https://www.fanniemae.com/portal/funding-the-market/data/loan-performance-data.html

Download the data the 3rd Quarter for the years 2004, 2008, 2012, and 2016. 
Unzip the data files into the "RawData" directory and then execute this script.

From the data you've downloaded from the links above, which attributes (and with what values) correlate the most with prepaid and defaulted mortages for each of the 4 years? Is there some attribute that remains significant across all four years?

These are examples of the "risk factors" we're interested in having you find in the data and display in some visually
interesting way. Do loans in a particular zip code or ones with a range of LTV (loan to value) on the initial house
purchase tend to get prepaid or go into default? As an example - if you discover lots of prepaid loans in Florida or southern Texas - is it possible those prepaids are the result of insurance companies paying off damaged or destroyed houses?

In addition to downloading the data from the above link you will need to have the following libraries installed in order to run the notebook. (In addition to having Jupyter Notebook itself installed).

 - os
 - glob
 - pandas
 - numpy
 - seaborn
 - matplotlib
