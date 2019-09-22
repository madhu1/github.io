# use SBT to compile a package:
spark and sbt are assumed to be installed on the cluster

step 1: Create SBT file.

step 2: Create project structure and file SparkPi.scala

step 3: Create a jar. Go to project root and run "sbt" to get sbt command line and then  "package" to create a jar;

step 4: Submit spark job with following code.


# Run A scala code in cluster :
# To run in standalone mode
spark-submit --class SparkPi --master spark://ec2-100-20-13-37.us-west-2.compute.amazonaws.com:7077 ./target/scala-2.11/spark-sample_2.11-1.0.jar
# To run in cluster mode
spark-submit --class SparkPi ./target/scala-2.11/spark-sample_2.11-1.0.jar

