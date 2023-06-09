# Modelo de regressão com Spark

### Dados de imóveis

    - from pyspark.sql import SparkSession
    - from pyspark.sql.types import IntegerType, DoubleType
    - from pyspark.sql import functions as f
    - from pyspark.ml.feature import VectorAssembler
    - from pyspark.ml.stat import Correlation
    - import pandas as pd
    - import matplotlib.pyplot as plt
    - import seaborn as sns
    - from pyspark.ml.regression import LinearRegression
    - from pyspark.ml.regression import DecisionTreeRegressor
    - from pyspark.ml.evaluation import RegressionEvaluator
    - from pyspark.ml.regression import RandomForestRegressor
    - from pyspark.ml.regression import DecisionTreeRegressor
    - from pyspark.ml.tuning import CrossValidator, ParamGridBuilder
    - from pyspark.ml.evaluation import RegressionEvaluator
    - from pyspark.ml.regression import RandomForestRegressor