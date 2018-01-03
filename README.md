# Spark-Beginners
Basic Codes for learning spark
This Document outlines how to initiate a Spark session and how to work with:
  1. spark-shell
  2. spark-sql
  3. pyspark
  4. sparkR
  
The respective instances can be invocked by executing the above in the shell console. 

However due to internal customization wrapers are built around this initializing the below:

  ** Set max.shells.user to 2
  ** Set max.shells.total to 64
  ** Set workdir.location to /var/tmp
  ** You do not have any running shells.
  ** Set system spark args to spark.driver.extraLibraryPath=/usr/hdp/2.4.0.0-169/hadoop/lib/ spark.driver.memory=512m spark.executor.cores=4 spark.executor.extraLibraryPath=/usr/hdp/2.4.0.0-169/hadoop/lib/ spark.executor.instances=3 spark.executor.memory=4g spark.jars=/var/tellme/content/spark-deployment/current/spark-commons.jar,/usr/hdp/2.5.3.0-37/hadoop/lib/hadoop-lzo-0.6.0.2.5.3.0-37.jar spark.kryo.classesToRegister=org.apache.hadoop.io.LongWritable,org.apache.hadoop.io.Text spark.master=yarn spark.serializer=org.apache.spark.serializer.KryoSerializer spark.submit.deployMode=client spark.yarn.maxAppAttempts=2 spark.yarn.queue=dsg
  ** Set executable.location.spark-shell to /usr/bin/spark-shell
  ** Set conf.allow-user-overrides to 1
  ** Set conf.permitted-override-keys to spark.serializer:0,spark.jars:,
  ** Executing command  --conf spark.driver.extraLibraryPath=/usr/hdp/2.4.0.0-169/hadoop/lib/ --conf spark.driver.memory=512m --conf spark.executor.cores=4 --conf spark.executor.extraLibraryPath=/usr/hdp/2.4.0.0-169/hadoop/lib/ --conf spark.executor.instances=3 --conf spark.executor.memory=4g --conf spark.jars=/var/tellme/content/spark-deployment/current/spark-commons.jar,/usr/hdp/2.5.3.0-37/hadoop/lib/hadoop-lzo-0.6.0.2.5.3.0-37.jar --conf spark.kryo.classesToRegister=org.apache.hadoop.io.LongWritable,org.apache.hadoop.io.Text --conf spark.master=yarn --conf spark.serializer=org.apache.spark.serializer.KryoSerializer --conf spark.submit.deployMode=client --conf spark.yarn.maxAppAttempts=2 --conf spark.yarn.queue=dsg
  SPARK_MAJOR_VERSION is set to 2, using Spark2

At the current organization this is initialized by:
  enter-spark-shell
