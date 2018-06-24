---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Projects

## CoinMarketDiff.com

[CoinMarketDiff.com](https://coinmarketdiff.com/) tracks and displays cryptocurrency price differences between exchanges.

The site is written in Node.js and has two compoents, the data collector and the web app. Both components use a shared MongoDB database.

### Data Collector

The data collector runs every minute and fetches prices from all API endpoits that have been configured in the database. It then saves the results for the web app to use.

### Web App

The web app queries the databse and displays the information in a nice format. It uses the Highcharts Javascript library to display historical data.
