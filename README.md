# Financial_Simulation_APIs
Two financial analysis tools by using a single Jupyter notebook:

A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Technologies
In this project we are using **Python 3.8/ Jupyter lab**. The libraries that we use are:

-  alpaca_trade_api
- dotenv
- os
- pandas 
- requests 
- json

---

## Installation Guide
As long as you have the previous technology mentioned then the only last step will be to gather the API Keys necessary from your Alpaca account it would look something like this:

>- ALPACA_APY_KEY = "the alpaca api-key from your account"

>- ALPACA_SECRET_KEY = "the alpaca secret-key from your account"
---

## Usage
To be able to use this program go to the file **```financial_planning_tools.ipynb```**. Then we will run all the cells all the way down until we see something like this:  

![](https://github.com/rulo96z/Financial_Simulation_APIs/blob/master/Images/5-4-monte-carlo-line-plot.png?raw=true)

---

## Contributors
This code was shared in 2021 Education Services at UCB. 

Additional updates/ uploads for usability was added by rulo.nogales@nogalesinvestments.com

---

## License
MIT License

Copyright (c) 2021 Raul 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
