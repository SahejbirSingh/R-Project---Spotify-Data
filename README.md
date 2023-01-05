# R-Project---Spotify-Data


Music is something that is close to each one of us. Be it tough times, be it easy times, be it happy or be it sad times, there’s music for each of those occasions. Still, we know so little about music. We all have our favorite songs, podcast or audio book but we fail to describe perfectly why do we like them. Through this project, we try to do so through the analysis of the Spotify data set.

We had set 3 clear objectives for this project:
• Whether music features impact the popularity of a track: The business relevance is music artists can focus on the key features in future projects to increase popularity
• Build a model to predict the popularity of a track: Business relevance: Music producers and Spotify can select music compositions with high probability of popularity
• Make clusters to club similar tracks together based on music features: Business relevance: Can be used to suggest songs to users based on their past listening record
We followed the below process for carrying out the project:
1. Data collection: secondhand data set was collected from Kaggle
2. Data cleaning and preprocessing: In this step, we focused on 3 objectives:
a. Finding the appropriate subset of data from the large dataset since the original dataset had over 580,000 rows of data. We did so by selecting the data of songs released between 16th April 2020 to 16th April 2021
b. Getting rid of the duplicate data and rows with missing values (NA or blank spaces)
c. Convert the numerical popularity score (0-100) to a categorical variable popularity category which will be the dependent variable going forward
3. Exploratory data analysis: In this step, we focused on using graphical tools and statistical summaries available in R to get a better sense of the data as well as identifying key patterns and features in the data set
4. Data Modeling: We focused on three tasks in this step:
a. Through decision tree and logistic regression models, understand the key music features which explain most of the track’s popularity
b. Build multiple models which can predict the track’s popularity based on the relevant input features and test these models with the validation dataset
c. Through clustering, create clusters of similar tracks (K means) which can act as a recommendation to listeners based on their music preferences
5. Sharing our insights and key takeaways
