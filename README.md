# Time_series_analysis

### Did the Google search traffic increase during the month that MercadoLibre released its financial results?
Yes, Google search traffic increase by 3008 during the month that MercadoLibre released its financial results. The release of financial results often draws attention from investors, financial analysts, and the media.

### Does any day-of-week effect that you observe concentrate in just a few hours of that day?
Based on the graph above, it looks like traffic intensity is highest at the nighht (22:00-01.00), regardless of what day of the week it is. But during Monday, Saturday and Sunday (index.dayofweek==0,5,6) traffic is less comared to Tuesday-Friday (index.dayofweek==1-4) , : the deep dark red indicates that traffic volume is large.

### Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?
No, based on the graph above traffic doesn't tend to increase during the winter holiday period (weeks 40-52 - highlited grey)

### Do both time series indicate a common trend that’s consistent with this narrative?
Not always, for instance in March stock price declined and traffic declined as well, but in June stock price is constantly growing while the traffic doesn't show such an increasing dynamics

### Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?
1) Relationship between Lagged search traffic and Stock volatility: Correlation Value is -0.001881, it is very close to 0, which indicates almost no linear relationship. The changes in lagged search traffic don't predict changes in stock volatility based on this data.
2) Relationship between Lagged search traffic and Stock price return: Correlation Value is 0.002753, this correlation is also very close to 0, suggesting almost no linear relationship between hourly stock return and lagged search traffic. Based on this data, lagged search traffic doesn't seem to predict stock returns.

### How's the near-term forecast for the popularity of MercadoLibre?
Trend shows decrease

### Question: What time of day exhibits the greatest popularity?
Midnight

### Which day of week gets the most search traffic?
Tuesday

### What's the lowest point for search traffic in the calendar year?
October-November
