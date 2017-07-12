## Part 1: Data Binding

Implement data binding so that when you type in the Candidate name in the
top text box,  the Hello message under the text box shows the name you type
as you type it.

## Part 2 - Update stock table with static array

Replace the placeholder table programmatically with the Stock information from
the table below

stocks = [
  {"ID":"1", "stock":"APPL", "price": "$785.34", "industry":"Tech"},
  {"ID":"2", "stock":"WMT", "price": "$68.75", "industry":"Tech"},
  {"ID":"3", "stock":"AMZN", "price": "$810.45", "industry":"Tech"},
  {"ID":"4", "stock":"FB", "price": "$95.34", "industry":"Tech"},
  {"ID":"5", "stock":"GOOG", "price": "$620.25", "industry":"Tech"},
  {"ID":"6", "stock":"DIS", "price": "$125.34", "industry":"Entertainment"},
  {"ID":"7", "stock":"CRM", "price": "$125.35", "industry":"Tech"},
  {"ID":"8", "stock":"ORCL", "price": "$45.35","industry":"Tech"},
  {"ID":"9", "stock":"SAP", "price": "$75.34", "industry":"Tech"},
  {"ID":"10", "stock":"SAP", "price": "$75.34", "industry":"Tech"},
  {"ID":"11", "stock":"WMT", "price": "$75.34", "industry":"Retail"},
  {"ID":"12", "stock":"TGT", "price": "$32.34", "industry":"Retail"},

];

## Part 3 - Implement the Filter Button logic

Type in a filter on the industry. Clicking on the Filter button should cause the stock table to be filtered so that only the stocks in the appropriate industry are shown

## Part 4 - Refresh the stock prices by making a rest call.

Clicking on the refresh button should update the stock price.

Use the rest call below to get the latest stock price (shown here for FB)

https://www.google.com/finance/info?q=NASDAQ:FB.   or

http://finance.google.com/finance/info?client=ig&q=NASDAQ%3AGOOG

You can test this in the browser and look at the returned response to get the right object structure and fields you need.
