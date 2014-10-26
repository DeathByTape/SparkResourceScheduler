Task Samples
============

These are some task samples we can use for testing the resource aware scheduler.

Compilation
===========

Compiling this code is trivial. Simply run:

```bash
$ sbt package
```

Execution
=========

To execute this code, use the "spark-submit" command included in bin. For more information, see [http://spark.apache.org/docs/latest/quick-start.html](the Spark quickstart).

Example:
```bash
$ ./bin/spark-submit --master spark://192.168.56.102:7077 --class "taskSamples.SparkPi" taskSamples/target/scala-2.10/tasksamples_2.10-1.0.jar
```

