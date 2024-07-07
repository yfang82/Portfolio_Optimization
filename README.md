# Portfolio_Optimization
In this project, I optimized a portfolio of eight S&P500 stocks with Black-Litterman method and generate max sharpe ratio weights as well as the efficient frontier.<br>  

The project was inspired by my MATH 151B course project at UCLA and my recent internship work. In my course project, I solve systems of linear equations that describe simple portfolio optimization situations with numerical method. The project was written in MATLAB and can be seen in [151B_project.pdf](https://github.com/yfang82/Portfolio_Optimization/blob/main/151B_Project.pdf) file.<br> 
 
However, with further exploration in portfolio investment, I realize that in real-world setting, we often have our own perspectives on the movements of the stock prices in our portfolio besides their historical performance. This leads to my interest in Black-Litterman method. <br>  

In [Black_Litterman_method.ipynb](https://github.com/yfang82/Portfolio_Optimization/blob/main/Black_Litterman_method.ipynb), I demonstrated the functions I wrote to implement the Black-Litterman method step-by-step. 

py files:<br>
[preprocessing.py](https://github.com/yfang82/Portfolio_Optimization/blob/main/preprocessing.py): Web scrapping, data reading and some data processing to get market cap, covariance matrix and delta, which are needed in later calculation.<br>
[bl.py](https://github.com/yfang82/Portfolio_Optimization/blob/main/bl.py): Preparing all the inputs needed in Black-Litterman model, including market implied return, investor's predictions, confidence level matrix. Calculating expected return.<br>
[calc_weights.py](https://github.com/yfang82/Portfolio_Optimization/blob/main/calc_weights.py): Obtaining max sharpe ratio weights with the expected returns and covariance matrix based on the model. <br>
[efficient_frontier.py](https://github.com/yfang82/Portfolio_Optimization/blob/main/efficient_frontier.py): Plotting efficient frontier based on the model.
