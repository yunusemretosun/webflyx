quotes
"The spice must flow."
"Fear is the mind-killer"

spark-shell \
  --conf spark.driver.host=$(hostname -i) \
  --conf spark.driver.bindAddress=0.0.0.0