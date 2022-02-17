# Stock-Price-Alerts
This code takes data from the Alpha Vantage stock API and calculates its percentage change. If the stock has increased or decreased by 5%, then it will send me a text message, alerting me of the change and providing the top three most popular articles referencing the company. These articles come from the https://newsapi.org/ API.

You can essentially grab the same yesterday and day before yesterday data through indexing, but I felt using
the datetime module was much more dynamic.
