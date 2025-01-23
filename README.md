Simple Trading Simulator
The goal of this assignment is to build a simple trading simulator / backtester. The system should be strictly written in python, but you are free to use libraries within the python ecosystem.


For data needs,
Use the provided csv files for simulation and testing of your system, or you can also connect to a datasource such as yfinance, or polygon.
CSV Files: TH2027

Signals
1. Buy: EMA 10 crosses above 20, with RSI is below 30.
2. Sell: EMA 10 crosses below EMA 20, and RSI is above 70.
3. The trade should stop if it takes a loss of 5% of position value.
4. The trade should book profit if it gains 10%.
5. 1 & 2 are entry signals, while 3 & 4 are exit signals.
6. The RSI should be 14-day RSI.

Simulation
- Assume the initial capital of 10,000
- Ignore transaction fees & costs.

Result should include,
- Total number of trades, entry exit details, such as datetime, profit/loss, entry price, exit price, stop loss or profit was hit etc.  
- Overall profit/loss, percentage return.

Visualisation
Plot a Candlestick graph of the trade data including 10 & 20 day EMA, Buy & Sell signal markers on plot.
General Instructions
Use Git for version controlling, use small commits to show the overall progress.
A single commit just containing the final version will lower your chances of selection.
You are free to use Backtesting libraries, provided you are able to explain what happens under the hood.
Dirty code can lead to disqualification.
The code should be easy to understand, readable, logically broken down into smaller parts, and more than anything functional.
Use Jupyter Notebooks, if you may but the outputs should be clean without unnecessary details.
Do not use AI to write your code, Submissions made using AI generated code will be disqualified at first instance. You are free to use AI to understand, comprehend, or brainstorm solutions. However, the final piece should be crafted by you.
Use poetry for dependency management, or provide `requirements.txt` at the very least.
Integrating with data sources will fetch extra points, however the assignment is still required to be completed.

Submissions
The final submission should be as a link for the github repository.
Make the submission by 24th of January. Do let me know in case there are emergencies or if you need to expedite it a bit further.  
Make your submissions using the following link:

Submission Link: https://forms.gle/8aNkgdXWfzSnTpKD9

Final Submission Date: 24 Jan 2025

 

