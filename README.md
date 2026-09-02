# Pyspark_Assessement (Describe)

# Day 01 to 30 Tutorial — Spark & PySpark Fundamentals


# Learning objectives
- Driver, Executors, Cluster Manager
- Transformations vs Actions + lazy evaluation
- Create SparkSession and explore a DataFrame

# Interview talking points
- DataFrames have schema + Catalyst optimizer (prefer over RDDs for analytics).
- show / count / collect are actions; avoid collect on large data.
- Lazy evaluation chains transforms into one optimized job at action time.
