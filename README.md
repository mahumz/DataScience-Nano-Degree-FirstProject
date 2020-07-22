# DataScience-Nano-Degree-FirstProject

I took a closer look at Data on Seattle's Airbnb market to better understand the following questions at hand.

Pricing increase or decrease by season.
Peak season in Seattle.
Pricing increase or decrease by neighborhood.
Find priciest neighborhoods in Seattle.
How does property types within neighborhoods impact price for the most expensive neighborhoods and most common property types?
Categorize reviews based on sentiments.
Can we map positive and negative sentiments from reviews to neighborhoods?
Explore some of the worst reviews for additional insights.
Predict a price for a given listing?
Find factors of the listing correlate best for predicting the price?

### After running my data set through my analysis show the following answers to my question.

Peak season is in summer between June to August with July being the highest.
The "Southeast Magnolia" neighborhood was the priciest and Rainier Beach was the cheapest.
Looking further at neighborhoods and property types, I found that houses in Portage Bay are the most expensive.
With the help of SentimentIntensityAnalyzer, I was able to map the reviews to their respective sentiments of positive, negative or neutral. I found out that 97.2% of reviews were mostly positive, with 1% negative reviews and 1.8% of reviews that were neutral.
Roxhill, Cedar Park and Pinehurst were the neighborhoods with the most positive reviews, while University District, Holly Park and View Ridge ranked lower.
SentimentIntensityAnalyzer associates non-English reviews with negative sentiments.
Using LinearRegression, I was able to predict price based on a prepped and cleaned dataset, with an r2score of 0.62 on both training and test datasets.
It was found that the features that had the most impact on price were a combination of host details as well as descriptive information about the listing.
