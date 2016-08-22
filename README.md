Data Science in 30 Minutes: Spark Streaming and Basic Analysis

## Installation Instructions

The presentation uses Jupyter notebooks, with a Scala/Spark kernel for ingesting data and a Python kernel for analysis.

The following will help you duplicate our (admittedly aged) kernel setup. We'll assume that you have already installed a Python environment, iPython, and Jupyter through either Anaconda or some other method.

1. You will need to have a working Java installation with $JAVA_HOME set. On Ubuntu, you can e.g. `sudo apt-get install default-jdk`.
1. `wget https://oss.sonatype.org/content/repositories/snapshots/sh/jove/jove-spark-cli_1.3_2.10/0.1.1-1-SNAPSHOT/jove-spark-cli_1.3_2.10-0.1.1-1-SNAPSHOT.tar.gz`
1. Unpack with `tar xvf jove-spark-cli....tar.gz`
1. `mv jove-spark-cli...SNAPSHOT jove-spark` for convenience
1. Run `./jove-spark/bin/jove-spark-1.3 --kernel-spec`
1. Check your installed kernels with `jupyter kernelspec list`. You should see the Spark kernel installed.

If you choose to use a different (newer) kernel, the setup may vary. The three dependencies you'll need in the Scala/Spark kernel are:
* org.apache.spark %% spark-streaming % 1.3.1
* org.apache.spark %% spark-streaming-twitter % 1.3.1
* com.google.code.gson % gson % 2.4

For the Python kernel, you'll need the matplotlib library (as well as the usually included datetime and json).
More importantly you'll need a working PySpark install (have pyspark in your path). You can download Spark [here](http://spark.apache.org/downloads.html).

Furthermore, for Twitter data, you'll need to register an [application](https://apps.twitter.com) and enter your credentials in the `twitter4j.properties` file.

## Credits
This talk was created by Ariel M'ndange-Pfupfu, a Data Scientist at The Data Incubator. He has worked on a variety of data science, software engineering, and curriculum development projects and is also a current Bleeker Fellow. He earned his Master’s degree at Stanford and his Ph.D. in Materials Science & Engineering from Northwestern.


[DataBricks](https://www.databricks.com), one of the largest contributors to the Apache Spark project, has been instrumental in developing and supporting Spark education. The [reference applications book](https://databricks.gitbooks.io/databricks-spark-reference-applications/content/index.html) was very useful for building this talk.

## About The Data Incubator
[The Data Incubator] (https://www.thedataincubator.com/) is a data science education company based in NYC, DC, and SF with both corporate training and recruiting services. For [data science corporate training] (https://www.thedataincubator.com/training.html), we offer customized, in-house training solutions in data and analytics. For [data science hiring] (https://www.thedataincubator.com/hiring.html), we run a [free 8 week fellowship] (https://www.thedataincubator.com/fellowship.html) training PhDs to become data scientists. The fellowship selects 2% of its 2000+ quarterly applicants and is free for Fellows. Hiring companies (including EBay, Capital One, Pfizer) pay a recruiting fee only if they successfully hire. You can read about us on [Harvard Business Review] (https://hbr.org/2014/08/the-question-to-ask-before-hiring-a-data-scientist/), [VentureBeat] (http://venturebeat.com/2014/04/15/ny-gets-new-bootcamp-for-data-scientists-its-free-but-harder-to-get-into-than-harvard/), or [The Next Web] (http://thenextweb.com/insider/2015/07/02/data-incubator-opens-a-west-coast-campus-to-groom-the-next-generation-of-data-scientists/), or read about our alumni at [LinkedIn] (http://blog.thedataincubator.com/2016/05/alumni-spotlight-xia-hong/), [Palantir] (http://blog.thedataincubator.com/2015/02/moving-to-palantir-from-mathematics-alumni-spotlight-on-justin-bush/), or the [NYTimes] (http://blog.thedataincubator.com/2015/02/alumni-spotlight-dorian-goldman-using-a-pure-math-background-to-solve-problems-for-the-new-york-times/).

For information on upcoming events, visit our [Eventbrite] (http://www.eventbrite.com/o/the-data-incubator-8342209540).
