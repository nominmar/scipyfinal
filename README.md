# scipyfinal
### Intro
First part of the script works with a portfolio of 10 stocks. I calculate the efficient allocation (relative weights) of 
each stock in the portfolio so that it maximizes returns or minimizes risk (standard deviation). Second part of the script uses features 
(closing, opening, highest and lowest prices of the day) to predict the stock price. 
I use cross validation + OLS and SVR, and compare their out-of-sample prediction measured by RMSE (root mean squared error).

### Data
The data is collected from yahoo finance using pandas-datareader, therefore any existing stock ticker can be used as input for functions. 
The first cell of the notebook installs datareader. 
In case it does not work, I have backup function and .txt file containing historical data of 10 stocks, which are currently used in script.

### Flowchart
The flowchart below contains the logic of the code. 
(If you don't see it, I sent Flowchart.png with the notebook). 
The script is organized into functions. 
Names of the functions, inputs and brief descriptions are in the flowchart. 
In the code, each function is preceded by a markup cell that explains it's purpose. Also, there are in-line comments for more detail.
