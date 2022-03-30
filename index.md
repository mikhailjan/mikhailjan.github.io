---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Projects

## Metaview.io

[Metaview.io](https://metaview.io/) provides free, transparent and easily accessible data about crypto tokens to help investors make informed decisions and avoid scams.

The app is built with Vue.js and Vuetify.js and has a Node.js backend that connects to a MongoDB database. It is hosted on AWS CloudFront and AWS Lambda.

## Coinship.io

[Coinship.io](https://coinship.io/) tracks and displays cryptocurrency price differences between exchanges.

The site is written in Node.js and has two compoents, the data collector and the web app. Both components use a shared MongoDB database.

The data collector runs every minute and fetches prices from all API endpoits that have been configured in the database. It then saves the results for the web app to use.

The web app queries the databse and displays the data using the Highcharts Javascript library.
