# data_transformation_csv
I created this notebook to transform csv exports from various data sources and merge them into a single dataframe (it's a little rough around the edges but it gets the work done). The main reason I had to use this is because I needed a country breakdown as "USA" and "non-USA" and other Excel pivot table had issues handling null or 0 data (division by zero, etc.).
Specifically, this notebook transforms Google Play ratings, crashes, uninstalls; AppsFlyer installs, and some other BigQuery query results and creates a merged dataframe at the end. 
