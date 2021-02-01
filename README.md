Overview:<br>

This is the repository for my Masters' thesis in the Masters of Business Analytics program at San Francisco State University (SFSU) <br>
Chris Yost-Bremm, Ph.D. and Finance Professor at SFSU, supervised my thesis. He has extensive domain knoweldge in the quantative evaluation of real estate prices, and supported the devlopment of the thesis, as well as evaluation of the model. His profile can be found here: https://www.linkedin.com/in/chrisyb/

<br>

Project Goal:<br>
Using Python as the coding language and Zillow data as the input data, create portfolios of metropolitan regions in the United States that behave similarly based on value and momentum metrics. 5 Portfolios for value and 5 portfolios for momentum are created and their signals evaluated independently of eachother. Then the 10 portfolios are interacted and the combined singals are evaluated.

Data Source:<br>
https://www.zillow.com/research/data/
<br>
Development: <br>
First I did exploratory analysis on the dataset and isolated the inidators to be used in the anlysis. 
* Metro region chosen as the main region type
* ZHVI (Zillow Home Value Index) was intitally chosen as the home price indicator - however after running the analysis on this indicator I realized it was too smooth and has been adjusted by Zillow making it less depictive of the true fluctuation in home prices.
* ZALL (Zillow All Homes) is the final inidcator selected for home prices as it contains raw data for home prices that has not been adjusted by Zillow for seasonality or other adjustments
* ZORI (Zillow Observed Rent Index) is the indicator chosen for rent prices
<br>
Model
* Value and momentum econometric models are selected as primary analysis models
* Inspiration to use these models is from the *Value and Momentum Everywhere* article by Clifford S. Asness, Tobias J. Moskowitz, and Lasse H. Pedersen. A copy of the article can be found here http://schwert.ssb.rochester.edu/f532/AMP12.pdf
* The key differences between the article and my model is the substitution of home prices for stock prices, and my definition of value, which was translated to the ratio of rent/home price for each month
* Besides this key difference, the methodology in the article is followed closely
<br>
Evaluation

