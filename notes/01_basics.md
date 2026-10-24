#### Creating SparkSession

``` python
from pyspark.sql import SparkSession

spark = SparkSession.builder \
    .appName("01_entry") \
    .master('local[*]') \
    .getOrCreate()

```

