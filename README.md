Pyspark is my primary programming language at work- I spend so much time googling it everyday. And as I've become more fluent in Pyspark/ Spark SQL (with the help of a wall filled with snippets and notes in front of my desk) here I want to summarize down and give examples of the functions that I find the most useful. I hope you can use this notebook your "cheatsheet", if you are learning Pyspark/ Spark SQL like me!

My Top 9 basic Pyspark / Spark SQL functions for data manipulation: 
1. Check the null value rate of each column `.columns` and for loop
2. Select or remove columns `.select()` and `.drop()`
3. Filter with condition(s) `.filter()`
4. Create a new column, or rename a column `.withColumn()` and `.withColumnRenamed()`
5. Fill in a custom value `.lit()` and `concat()`
6. Check unique values counts in a column `.select().distinct().count()`
7. Group by a column and tranform it into a new dataframe `.groupBy()` and `.agg()`
8. Sort `.orderBy()`
9. Sampling the dataframe `.limit()`
