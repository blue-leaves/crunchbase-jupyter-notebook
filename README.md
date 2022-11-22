# Description of the project

This is an analysis of startup fundraising deals collected from Crunchbase.

Using pandas, I start to explore the dataset working with a memory constraint (while the entire dataset consumes around 60 MB, I aim to push the memory usage under 10 MB).

I clean the dataset and deal with missing values and then proceed to identify the datatype of each column, with the objective to reduce the memory usage or to use the more appropriate type for the given column.

After cleaning and casting the appropriate datatypes, I load the entire dataset divided in chunks in a SQL database.

Calling both SQL queries and plotting bar and donut charts, I provide an analysis of the data.
