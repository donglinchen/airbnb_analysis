### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation <a name="installation"></a>

Anaconda distribution contains all the necessary python libraries needed to run the code and it can be downloaded at https://www.anaconda.com/products/individual.

### Project Motivation<a name="motivation"></a>

I was interested in using the airbnb data to find some interesting patten. Perticularly to understand:

1. What kind of property type were available in listings and what were the availabilities for those property types.

2. What were the listed prices in Boston and Seattle? What price range have the most listings?

3. Where could you find low price or high quality airbnb rentals in Boston?

4. How ddid price change in different months of the year?


The data analysis show that listing prices in Boston distributes unevenly and fluctuates more than Seattle, I would like to build a price model to predict the listing price in Boston bases on some common airbnb listing factors, like property type, neighbourhood, number of guest, bedrooms, bathrooms, review scores, etc... This model can also be helpful to the ones who want to post rentals on airbnb site and want to set the price properly according to the market.


### File Descriptions <a name="files"></a>

There are three jupyter notebook files avaiable:
1. airbnb_listings_analysis.ipynb: this file contains the code to explore the airbnb listings data to understand the listsings and answer the questions realated to questions 1 to 3

2. airbnb_calender_analysis.ipynb: this file contains code to explor the price changes during different months of the year, and compare between Boston and Seattle

3. price_model.ipynb: this file contains code to build a linear regression model to predict airbnb listing price in Boston


### Results<a name="results"></a>

The result can be found at the post available here


### Licensing, Authors, Acknowledgements<a name="licensing"></a>

Airbnb data and license are available at http://insideairbnb.com/get-the-data.html
