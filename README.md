<h1 align="center"> ALX-Udacity Data Analytics Nanodegree Project-II </h1>
<p align="center"> 
  <img src="https://opportunitycrib.com/wp-content/uploads/2022/04/Alx-Virtual-Assistant-Programme-696x473.jpg" alt="Sample signal" width="70%" height="70%">
</p>
<!-- Content -->

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Introduction -->
<h2 id="introduction"> :pencil:Introduction</h2>
<p align="justify"> 
  The dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Data Cleaning & Transformation -->
<h2 id="Data Sourcing"> :pencil:Data Cleaning & Transformation</h2>
<h4> Quality issues </h4>

- There are columns with missing values namely - expanded_urls

- Name, doggo, floofer, pupper and puppo columns have value with the name None

- Values in source column are not human readable

- Use of _instead of space in p1, p2 and p3 column values. Also, values upper case sometimes lowercase other times in p1, p2 and p3 columns

- column names are not clearly descriptive

- There are image duplicate predictions present for duplicate jpg_url with different tweet ids and rest all the data same.

- tweet id title is different, id here tweet_id in others.

- There are image duplicate predictions present for duplicate jpg_url with different tweet ids and rest all the data same

<h4> Tidiness issues </h4>

- One variable in 4 columns - dog_stage(doggo, floofer, pupper, puppo)

- Merge the tables - archive_tweet and df
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Insights -->
<h2 id="Insights"> :pencil:Insights</h2>

- Comparison Of Average Number Of Retweets And Favorites In A Month
- Comparison Of Average Rating Of Dog Stages
- Algorithm's First Prediction Efficiency for top 10 most frequent predictions

<!-- Conclusion & Observation -->
<h2 id="Conclusion & Observation"> :pencil:Conclusion & Observation</h2>

- Algorithm has proved to be least efficient for Chihuahuas.
- The most predictions are recorded for Golden Retrievers and least for Malamutes
- Therefore, we can say that, this algorithm favors the Golden Retrievers in this dataset
- From the bar graph, it can be clearly seen that puppo has the highest average rating while pupper has the lowest.
- From the pie chart, we can see that there are 63.48% of puppers in the overall population of the dataset followed by doggo, then floofer and at the last, puppo. - - This indicates the possible reason of lowest average rating of pupper and highest average rating of doggo because of huge differences in their proportion in the dataset
- As we can see that on an average, number of favorites are quite higher in January.
- February has the second highest both average number of favorites and retweets.
- December has the least number of favourites which is in close range with september, october & november.
