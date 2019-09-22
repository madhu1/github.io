# use SBT to compile a package:
spark and sbt are assumed to be installed on the cluster








# Run A scala code in cluster:
#on the master node run the following
# To run in standalone mode
spark-submit --class SparkPi --master spark://ec2-100-20-13-37.us-west-2.compute.amazonaws.com:7077 ./target/scala-2.11/spark-sample_2.11-1.0.jar
# To run in standalone mode
spark-submit --class SparkPi --master spark://ec2-100-20-13-37.us-west-2.compute.amazonaws.com:7077 ./target/scala-2.11/spark-sample_2.11-1.0.jar

