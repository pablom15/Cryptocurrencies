# Cryptocurrencies

## Resources
    - Software: Jupyter Notebook v6.0.3, Python 3.7.6
    - Data Sources: crypto_data.csv

## Challenge Description and Analysis
In this challenge an analysis was performed on cryptocurrencies data in order to develop groups and classify the data for future investment opportunities. In the Cryptocurrencies Challenge notebook, you will find the ETL process I performed on the data source in order to prepare the dataset for analysis. Principal component analysis was performed on the filtered data set with 3 components. After plotting an elbow curve it was observed that there was a K value of 5. A K means model was then created and determined a class for each data point. Lastly the data was plotted for visual analysis. It could be argued that the BitTorrent data point is an outlier but I included it in the analysis due to my unfamiliarity with the dataset. Further research would have to be performed to determine the accuracy of this data point from BitTorrent. For the purpose of this analysis I left it included and it was given it's own class due to its unique PC 1 value.