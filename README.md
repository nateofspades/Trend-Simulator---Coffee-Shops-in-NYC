# Trend Simulator for Coffee Shops in NYC

### Code
**Trend Simulator - Retrieving Yelp Data:** <br />
*the output of this file is shops.csv* 
https://nbviewer.jupyter.org/github/nateofspades/Trend-Simulator-for-Coffee-Shops-in-NYC/blob/master/Trend%20Simulator%20-%20Retrieving%20Yelp%20Data.ipynb

**Trend Simulator - EDA:** <br />
*this file processes and analyzes shops.csv* 
xxxxxxxxxxxxxxxxxxx(To be filled in when the file has been uploaded)xxxxxxxxxxxxxxxx

**Trend Simulator - Simulation:** <br />
*this file uses the processed shops.csv and insights from EDA to build the simulator* 
xxxxxxxxxxxxxxxxxxx(To be filled in when the file has been uploaded)xxxxxxxxxxxxxxxx

### Introduction
Who doesn't love maple syrup? Most people, actually, because they have never had the opportunity to taste it. Canada's province of Québec produces over 70% of the world's maple syrup supply. As someone who has spent a considerable length of time living in Montreal, I have encountered many foreign visitors who arrive with the bucket list goal of finding high quality maple syrup during their stay. I began to wonder if the actual demand for maple syrup among foreigners is as high as it seemed to be. Curiosity led me to Reddit, where I read through numerous dialogues on the topic. The intent was to develop an intuitive idea of what consumers think of maple syrup, and what I found is that most people who have tried it really, really like it. In particular, numerous people discuss substituting the sugar in their coffee with maple syrup, and those who do are almost always positively enthusiastic about it. This gave me the idea of analyzing the introduction of Canadian maple syrup coffee into a prosperous, coffee-loving city in USA, and NYC fit the description perfectly.

### Idea
I am taking a graph-theoretical and probabilistic approach to building a trend simulator for coffee shops in NYC. The underlying idea is that when a coffee shop adopts a trend (such as adding maple syrup to their coffee) it generates a theoretical influence on nearby competitors to do the same. 

### Data
I have collected data on nearly 6000 coffee shops in NYC using the Yelp Fusion API, and the can be found in shops.csv. I have also inspected the datasets from the Yelp Dataset Challenge, particularly the reviews dataset, which has over 6.7 million rows. While this dataset offers no information about NYC, it does mention maple syrup... a bit: 14638 reviews mention 'maple', 23 reviews mention 'maple coffee' and 5 reviews mention 'maple syrup coffee'. These are small numbers in relation to the size of the dataset. What is encouraging, though, is that 21 of the 23 'maple coffee' reviews were positive, and the remaining 2 seemed to either be positive or indifferent. There were no negative reviews!

