# map-reduce-narendra
* Learning about the Mapreduce in python.
# Data Description
* This DataSet contains the details of Number of movies released according to year wise in IMDB.
* This Dataset is a free source from [Kaggle](https://www.kaggle.com/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)
# Study
* In this Data set I want ot find the Number of Movies Released according to the specific year in IMDB platform.
# Execution
* A Mapper file extracts the Released_year from each row in the dataset. which is used as key. This output is given as input to the Sorter File then the ouput of sorter file is given to reducer File which inturn given as output to output.txt Used the data to visuallize.
# Powershell Command
* cat imdb_top_1000.csv | python 21mapper.py | sort  | python 22reducer.py > output.txt
# Summary
* By examining the final output, we can understand the Growth of released movies in IMDB according to specific years. Compare to all years in 1990 the number of movies released was high.

![]()
