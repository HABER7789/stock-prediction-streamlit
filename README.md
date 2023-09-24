# stock-prediction-streamlit
Simple Streamlit Web Application for Stock Forecast using Python
This Project was done for Learning purposes
There are several Errors I faced while creating the project: 
- At the beginning itself, installing packages such as streamlist, yfinance, fprophet, I encountered an error for fprophet, so install prohet instead of fprophet
- Next, there was the main issue of loading data, without data there would be no prediction. The error was that the package yfinance returns empty dataset after writing the code for importing the data.After scouring the web I found the fix, I had to manually create a folder "py-yfinance" inside Users/AppData/Local on my system. The data was then imported successfully.
- Prophet was used to predic the stock prices
- This project was done by following a youtube tutorial, however it was 2 years old, so I had to update the packages and resolve the errors.
- It seems to be working fine now. The project has not data analysis done, such as replacing missing values and among other things.

Feel free to let me know how to improve the same, and if you face any issue, I can try my best to resolve my version of the code. 
Cheers!
