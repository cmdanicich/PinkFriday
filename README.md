## Acquire and Analyze - Pink Friday 

### #Barbz

For this project, I decided to scrape Twitter for the hashtag, #barbz, which is related to the pop/rapper, Nikki Minaj. Her followers ofter use this hashtag along with "barb" and "barbies" to share their allegiance and support to the singer herself and the fan group. I decdied to use the past 14 days as a marker to collect tweets using the hashtag because seven days did not provide enough tweets – he 14 days provided 29,740 tweets. 

I then read the user info into a dataframe so it could be used in both python and in SQL and also read it to a .csv so I could utilize it for this analysis. 

Once in the .csv, I cleaned the tweets by splitting on whitespace, shifting to lowercase, and removing stopwords. I took a few descriptive stats but my main focus was the top_1000 tokens as this is what was going into my word cloud. That being said, the next step was creating the word cloud using matplotlib. As you can see at the bottom, it created a word cloud with the largest words being "pink friday." Pink Friday is Nikki Minaj's first album and happens to have a reunion comnig up soon so this makes a lot of sense. Other large words (more frequently used) are queen, love, follow, grammys, nikki, barbs, and music. 

Overall, this was a great experience learning how to make word clouds and also reinforcing my previous knowledge of twitter scraping and conversion to dataframes and .csv's. 
