# Module 3

## Fundamental analysis using Regression

This module would introduce us to the Regression related inferences to be drawn from the data.
Regression is basically a statistical approach to find the relationship between variables. In machine learning, this is used to predict the outcome of an event based on the relationship between variables obtained from the data-set. More often than not, we utilize linear regression to come up with an ideal inference. We'd be using the regression model to solve the following problems:

<h2>Problem Statements</h2>
 <ul>
 <li><strong>3.1</strong> Import the file 'gold.csv' (you will find this in the intro section to download or in '/Data/gold.csv' if you are using the jupyter notebook), which contains the data of the last 2 years price action of Indian (MCX) gold standard. Explore the dataframe. You'd see 2 unique columns - 'Pred' and 'new'. One of the 2 columns is a linear combination of the OHLC prices with varying coefficients while the other is a polynomial function of the same inputs. Also, one of the 2 columns is partially filled.
   
<ul>
<li>Using linear regression, find the coefficients of the inputs and using the same trained model, complete the entire column.</li>
<li>Also, try to fit the other column as well using a new linear regression model. Check if the predictions are accurate. Mention which column is a linear function and which is polynomial.</br>

(Hint: Plotting a histogram & distplot helps in recognizing the discrepencies in prediction, if any.)</li>
</ul>
</li>

 <li><strong>CAPM</strong> CAPM Analysis and Beta Calculation using regression -
</br>
CAPM(Capital Asset Pricing Model) attempts to price securities by examining the relationship that exists between expected returns and risk.
</br>
Read more about CAPM. (<a href="https://www.investopedia.com/terms/c/capm.asp">Investopedia CAPM reference</a>)
</br>

The Beta of an asset is a measure of the sensitivity of its returns relative to a market benchmark (usually a market index). How sensitive/insensitive is the returns of an asset to the overall market returns (usually a market index like S&P 500 index). What happens when the market jumps, does the returns of the asset jump accordingly or jump somehow?
</br>

Read more about Beta (<a href="https://www.investopedia.com/investing/beta-know-risk/">Investopedia Beta reference</a>)</li>
<li><strong>3.2</strong> Import the stock of your choosing AND the Nifty index.
</br>
Using linear regression (OLS), calculate -
<ul>
<li>The daily Beta value for the past 3 months. (Daily= Daily returns)</li>
<li>The monthly Beta value. (Monthly= Monthly returns)</li>
</ul>
     Refrain from using the (covariance(x,y)/variance(x)) formula.
</br>Attempt the question using regression.(<a href="https://financetrain.com/calculating-beta-using-market-model-regression-slope/">Regression Reference</a>)
</br>Were the Beta values more or less than 1 ? What if it was negative ?
</br>Discuss. Include a brief writeup in the bottom of your jupyter notebook with your inferences from the Beta values and regression results

</li>
</ul>
