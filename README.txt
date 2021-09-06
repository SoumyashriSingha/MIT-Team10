
Hi there,
	We have been given a problem statement to - 
Create a Dashboard based on which User would be able to analyze the sentiment of the specific stock. You’re required to create an Analytical Server "OHLC" 
(Open/High/Low/Close) time series based on the ‘Stock List’ dataset which will be provided to you in a separate JSON format and its output should be a timely 
report printed in Charts. 
We have created OHLC engine using the 'Stock List.json' database.

	We brainstormed various approaches to this problem statement and implemented 2 of those approaches. Explaining it briefly, the approach goes as follows - 
Approach 1) Excel sheet implementation of data and creating charts from Volume-Open-High-Low-Close and framed into html using iframe tag.
Approach 2) Separate Front end using HTML, CSS, Bootstrap and Back end by converting json to csv file and then using Python coding (mplfinance library module) and hence created 
   OHLC, Candlestick, Vertex line, Bar graphs.
   For the Front end part we have shown additional features like registration and login credentials, quotes ie.prices of stocks, Buy or Sell a stock, Transaction 
   History.

Since we have not created an API; To run, you will need to register for an API key in order to be able to query IEX’s data. The following link is shared below:
https://iexcloud.io/cloud-login#/register/

Approach 3)[not implemented] We can import the json file into google sheet and we can use google script(.gs) to make a search bar so that we can get the data 
  from the google sheet as per the serach request and we can make the graph using google charts.

Please visit our repository. Hope it will be helpful.

TEAM 10 (NT Hackathon):
Sonali Ankolikar
Rehan Raza Khan
Atharva Singh
Soumyashri Singha
Saiem Pathan