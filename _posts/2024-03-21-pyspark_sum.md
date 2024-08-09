# Data Summaries with pyspark (Python)

[pyspark data summaries](https://bphigg.github.io/python_data/pyspark_data_summaries.html)

[Python Repo](https://github.com/bphigg/python_data)

Here I compare three different methods to accomplish the same task - summarizing score data from an NFL data set. The first method explores python's `map/reduce ` functionality. To illustrate this, I first had to split the data into separate parts to mimick `pyspark`'s **Resilient Distributed Dataset** (**RDD**) structure. The second and third methods utilized `pyspark`'s *spark SQL* and *pandas-on-spark* libraries to obtain similar summaries.
