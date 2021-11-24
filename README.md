# GoogleAppRating-Analyst
The project is an analysis about the profitable App profiles for both the App Store and Google Paly market.
We will find out what type of free apps are likely to attract more users, in other words, the most common genres for each market.
To do this, we'll need to collect and analyze data about mobile apps available on Google Play and the App Store.
The data set from Kaggle containing data about approximately 10,000 Android apps from Google Play; the data was collected in August 2018. 



Dataset contains two datatypes: int64 (numerical), float64(numerical) and object, knowing datatype helps us with using correct operations on correct data columns later on(need to convert some object data type to numeric and date in to datatime formate

Null values: There are bunch of Null values present in rating column as well as in android ver, current ver and Type columns.

Drop dulpicate , Replace all missing value with NaN value and perform some analysis in order to clean and organize data.


Data insights:
App with large number of reviews is Facebook
Rating of application in each category is not different too much but event and education got highest Rating.
Game and Family category are the most appearances for application in store
Most of application in this store are free (93.1%).
Average of price is around 0.96, but most of them are free (8715 from 9360).
The most expensive app is 400 dollar !!!.
