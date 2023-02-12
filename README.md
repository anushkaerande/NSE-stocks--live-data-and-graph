# NSE-stocks--live-data-and-graph
app that uses GUI Libraries and Web Scraping Tools along with other pre-existing Libraries to fetch the live price of Equity Stocks in the National Stock Exchange.
# Abstract
  This project was taken up with the intention of being a usable and scalable application which provides quick and brief insights into apps in the National Stock Exchange through charts and the Live Price of the equity stock in question. The application aims to provide the trends of the stock through the period of time as selected by the user. This allows for the split second decision-making required for working with equity stocks. The libraries used and the app itself provide real time results from reliable sources on the internet. The application also provides a brief section about the stock which aids the user in making their decision. 
Further, the UI has been creating using the StreamLit and Tkinter libraries which provide for a simple, user-friendly and sleek user interface. All this combined, makes the app a powerful and easy to use tool in the hands of the modern investor.        
# Module-wise description
The program uses multiple pre-defined modules and some user defined ones for tasks that are to be performed many times. The pre-defined ones exist in the imported libraries like Tkinter, StreamLit, NSEPy and Pandas. 
The following are the user defined modules: 

get_class_contents (name, class_name)

This module takes the name (symbol of the stock) and the name of the class (in the HTML of the Google Finance site for the stock) that must be extracted and returns the contents. It uses the requests and BeautifulSoup libraries to provide this information. It returns a string value. 
This module is useful because it cleans the text of all the tags and returns it. 

     
live_price (name)  

This module takes the name (symbol) of the equity stock as an argument and uses the above described get_class_contents module to get the live price of a stock from the Google Finance site for the stock.        

# techonologies used 
Web Scraping
streamlit

