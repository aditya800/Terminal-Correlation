# Terminal-Correlation
A web app that computes the correlation between Alpaca API's forecasts and Graham's formula 

### Motivation

Interest in value investing has suddenly dwindled in recent years. Traditional investing regime of yore has been supplanted by modern quants exploiting data science techniques and prompting ML research. But, the same techniques can also be applied to models built from traditional formulas. Whether they yield the same results or not is what motivates this project.

#### Note: Alpaca's API currently supports only limited assets: https://financefeeds.com/fintech-firm-alpaca-launches-alpacaforecast-ai-prediction-matrix-bloomberg-users/.

### Bloomberg Terminal setup

The project is missing data sets which can be exported and loaded through the Terminal. 

type ```appportal``` and download Alpaca's Pro API and export any currency forecast to the project directory, and rename it as dataset.csv

### Graham's Formula

Although the formula is usually applied to calculate the intrinsic value of stocks, certain adjustments can be made to leverage it for currency prediction. 

![alt text](https://www.oldschoolvalue.com/blog/wp-content/uploads/graham-formula-update.png)

Division by y is applied because the original formula is dated. 

