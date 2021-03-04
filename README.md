# SWANdatacharts

Taking the SWAN Solar Flare dataset from https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EBCFKM
and filtering out features that have too many outliers / a range of data values of greater than 10,000.  Some of these features were looked at more in-depth with histograms and scatterplots
after using z-score normalization.

Below are the results of five cleaned normalized features used to compare how well the combinations of each pair of features does in separating the different classes of target feature.
![alt text](https://i.imgur.com/77KcPUb.png)
