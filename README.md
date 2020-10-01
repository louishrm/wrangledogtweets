# wrangledogtweets

# Introduction
The aim of this project is to practice gathering data related to  [WeRateDogs](https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) 
tweets from different sources and cleaning it. 

# Steps 
## Gather 
There are 3 files needed for this project, the first one is a twitter archive csv file containing information like the text, url, image link and tweet id. 
The second one needs to be downloaded programatically and is a dataset which contains the dog breed predictions a neural network made when the photos from the tweets were used as input. Finally, it necessary to query twitter's API to collect additional data on these tweets, such as number of likes and retweets. 
## Clean
These 3 datasets need to then be cleaned and possibly organized into a master pandas DataFrame object. Techniques involved are using pandas 'melt' and 'merge' functions and string parsing. 
## Explored
Once the data has been cleaned, a couple of insights and visualisations will be given regarding tweets on the WeRateDogs page. 
