# Kmeans-Classification-of-Pharmaceutical-Companies

The main objective is to understand the structure of the pharmaceutical industry using some basic financial measures. Financial data gathered on 21 firms in the pharmaceutical industry are
available in the file Pharmaceuticals.csv.

Using K-means clustering, we find that there are two clusters in the dataset. Cluster 1 represents companies having positive Market_Cap, ROE, ROA, Asset_Turnover and NetProfitMargin,  with negative Beta, PE-Ratio, Leverage and Revenue Growth, while Cluster 2 represents the reverse. There appears to be a pattern consisting of brokerages recommending a strong buy for companies in Cluster 2 and not for companies in Cluster 1. Brokerages are also tend recommend a "hold" for companies in Cluster 1 more than Cluster 2. This would suggest that Cluster1 contains LOW RISK/HIGH RETURN firms because although they have on average negative revenue growth, they show on average a positive market capitalization, ROE, ROA, Asset Turnover and Net Profit. They also have negative leverage, negative Beta and PE_Ratio Cluster2 on the contrary is HIGH RISK/LOW RETURN because companies in this cluster portray opposite characteristics to cluster 1 companies. That is, higher Beta and PE ratio on average as well as higher leverage while running negative net profit margins, market capitalization, asset turnover etc.

