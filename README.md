# PySpark
## SQL 
```{python}
# First 10 rows in SQL language
query = "FROM flights SELECT * LIMIT 10"

# Get the first 10 rows of flights
flights10 = spark.sql(query)

# Show the results
flights10.show()
```
