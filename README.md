# Analyzing-Startup-Fundraising-Deals-from-Crunchbase
In this project I will use some techniques to analyze startup investments from crunchbase.com.
Every year, thousands of startup companies raise financing from investors. Each time a startup raises money, we refer to the event as a fundraising round. Crunchbase is a website that crowdsources information on the fundraising rounds of many startups. The Crunchbase user community submits, edits, and maintains most of the information in Crunchbase.

In return, Crunchbase makes the data available through a web application and a fee-based API. Before Crunchbase switched to the paid API model, multiple groups went to the site and released the data online. Since the information on the startups and their fundraising rounds is always changing, the dataset we'll be using isn't completely up to date.

Throughout this project, I'll be working with different memory constraints. In this step, let's assume we only have 10 megabytes of available memory. While crunchbase-investments.csv consumes 10.3 megabytes of disk space, pandas often requires 4 to 6 times amount of space in memory as the file does on disk (especially when there's multiple string columns).
