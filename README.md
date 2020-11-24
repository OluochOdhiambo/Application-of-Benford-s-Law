# Application-of-Benford's-Law
Benford's law is an observation about the leading digits of the numbers found in real-world data sets. Intuitively, one might expect that the leading digits of these numbers would be uniformly distributed so that each of the digits from 1 to 9 is equally likely to appear. In fact, it is often the case that 1 occurs more frequently than 2, 2 more frequently than 3, and so on. This observation is a simplified version of Benford's law. More precisely, the law gives a prediction of the frequency of leading digits using base-10 logarithms that predicts specific frequencies which decrease as the digits increase from 1 to 9.

This phenomenon occurs generally in many different instances of real-world data. It becomes more pronounced and more likely when more data is combined together from different sources. Not every data set satisfies Benford's law, and it is surprisingly difficult to explain the law's occurrence in the data sets it does describe, but nevertheless it does occur consistently in well-understood circumstances. Scientists have even begun to use versions of the law to detect potential fraud in published data (tax returns, election results) that are expected to satisfy the law.

In this repo, I apply the law to check for anomalies in census data obtained from the Kenya National Bureau of Statistics.

## Libraries
Tabula, Pandas, Matplotlib, and Random
