# Yelp-Restaurant-Closure-Prediction

The U.S. restaurant industry is very large and diverse across the country. According to a statistical research, the industry generated about $799 billion and had 14.5 million employees in 2021, suggesting that many people open and close a restaurant on a frequent basis. Opening a restaurant is expensive and may require outside investment, and furthermore, a restaurant business is most likely to fail in its first year of operation since it faces relatively low profit margin and many operational challenges. In fact, the National Restaurant Association estimates a 30\% failure rate in the restaurant industry. 

With these relatively high restaurant failure rate, the prospective lenders need to carefully analyze the risk involved with loaning the money to restaurant businesses. If the banks and investors can accurately predict whether the business will fail or not in a short term, they can decide whether they should lend money to a specific restaurant.

Yelp is a U.S. based company that publishes crowd-sourced reviews about businesses through a website (Yelp.com) and the Yelp mobile app. According to the Yelp metric, there are about 244 million cumulative reviews and 33 milion app unique devices. Most importantly, restaurants are the #1 reviewed business on Yelp, and hence, it is reasonable that we should fully utilize its website for our dataset.

I downloaded the Yelp academic dataset, which is available here: https://www.yelp.com/dataset/download, and then, I extracted the tar file to obtain the target JSON files. However, looking at the sample data and the Yelp documentations, I realized that the academic dataset is somewhat limited and some of the information are not provided to us.

Subsequently, I thought about web scraping, but "Yelp does not allow any scraping of the site, and does not permit the use of any third party software that scrapes or copies Yelp reviews, business pages, photos or profile information." We will comply with Yelp's policy, and only use the provided academic dataset to build our predictive model.
