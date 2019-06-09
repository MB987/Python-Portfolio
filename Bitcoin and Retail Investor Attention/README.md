# READ ME


The research of this work examines the relationship between retail investor attention based on Google searches and Wikipedia pageviews and the price and trading volume of Bitcoin. 
Firstly, a descriptive representation of the data and the contemporaneous relationships of the investigated variables are exhibited. Furthermore, existing dynamic relationships are uncovered.
The exploration of the relationship between attention and the Bitcoin market is of particular interest since the internet currency has no intrinsic value. Buying and selling decisions can therefore not be based on fundamental indicators which determine a fair value. Hence, public attention could be a decisive factor impacting the Bitcoin market.

Methodology employed: 
* Calculate the Pearson correlation coefficients and inspect for a cointegration between the time series of all associated variable pairs. 
* I estimate vector autoregressive (VAR) models of the variable pairs and derive the impulse response functions from them. The VAR models allow to determine (Granger-) causality between retail investor attention and the Bitcoin price or trading volume, while the impulse response functions permit to observe the magnitude and manifestation of these causal connections.


The folder **'Data Preparation'** includes the inital data in .CSV files, as well as the Jupyter Notebooks (.ipynb), which clean and prepare the data for the analysis.

The folder **'Data Analysis'** contains the prepared data in .CSV files and the Jupyter Notebooks (.ipynb), with the data visualisations and statistical methods (Correlation Coefficients, Granger Causality, Vector-Autoregressive Models, Impulse-Response Functions)
