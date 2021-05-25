# Keyword-Relation-Data
A dataset composed of 2 CSV files

#### keyword_data.csv

A list of keywords with 10 floating point number features

#### similarity.csv

A list of keyword pairs and a floating point value [-1, 1) of how similar the two keywords are. 

#### test.csv

A list of keywords pairs

## Tasks

1. Create an function that embeddeds the keyword features into some space, whose distance to other keywords tries to match the similarity data. 
2. Run the keyword pairs in the test file through your embedding routine and collect a create a new CSV file of the keyword pair, and your guessed similarity score

Please do all work in a Jupyter Notebook, then when you are done, export as an html page.
