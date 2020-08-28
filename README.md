# NYU-Courant-Institute-Dashboard

A CubeJS Implementation for Data Analytics. 

# To Use

First clone the repository to your local storage

`git clone https://github.com/hrithikv/NYU-Courant-Institute-Dashboard.git`

# Run the command

`npm install`

# And then:

`npm run dev`

It will run locally at localhost:4000

https://cube.dev/

Cube.js is an open source modular framework to build analytical web applications. It is primarily used to build internal business intelligence tools or to add customer-facing analytics to an existing application.

Cube.js was designed to work with Serverless Query Engines like AWS Athena and Google BigQuery. Multi-stage querying approach makes it suitable for handling trillions of data points. Most modern RDBMS work with Cube.js as well and can be tuned for adequate performance.

# Why Cube.js?

If you are building your own business intelligence tool or customer-facing analytics most probably you'll face following problems:

1. Performance. Most of effort time in modern analytics software development is spent to provide adequate time to insight. In the world where every company data is a big data writing just SQL query to get insight isn't enough anymore.
2. SQL code organization. Modelling even a dozen of metrics with a dozen of dimensions using pure SQL queries sooner or later becomes a maintenance nightmare which ends up in building modelling framework.
3. Infrastructure. Key components every production-ready analytics solution requires: analytic SQL generation, query results caching and execution orchestration, data pre-aggregation, security, API for query results fetch, and visualization.

Cube.js has necessary infrastructure for every analytic application that heavily relies on its caching and pre-aggregation layer to provide several minutes raw data to insight delay and sub second API response times on a trillion of data points scale.

# License

Cube.js Client is MIT licensed.

Cube.js Backend is Apache 2.0 licensed.

