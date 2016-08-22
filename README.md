Data Science in 30 Minutes: Spark Streaming and Basic Analysis

## Installation Instructions

The presentation uses Jupyter notebooks, with a Scala/Spark kernel for ingesting data and a Python kernel for analysis.

Get a Scala/Spark kernel for Jupyter notebooks here.

Depending on which kernels you use, the setup may vary. The three dependencies you'll need in the Scala/Spark kernel are:
* org.apache.spark %% spark-streaming % 1.3.1
* org.apache.spark %% spark-streaming-twitter % 1.3.1
* com.google.code.gson % gson % 2.4

For the Python kernel, you'll need the matplotlib library (as well as the usually included datetime and json).
More importantly you'll need a working PySpark install (have pyspark in your path). You can download Spark [here](http://spark.apache.org/downloads.html).

Furthermore, for Twitter data, you'll need to register an [application](https://apps.twitter.com) and enter your credentials in the `twitter4j.properties` file.

## Credits
This talk was created by Ariel M'ndange-Pfupfu, a Data Scientist at The Data Incubator.

## About The Data Incubator
[The Data Incubator] (https://www.thedataincubator.com/) is a data science education company based in NYC, DC, and SF with both corporate training and recruiting services. For [data science corporate training] (https://www.thedataincubator.com/training.html), we offer customized, in-house training solutions in data and analytics. For [data science hiring] (https://www.thedataincubator.com/hiring.html), we run a [free 8 week fellowship] (https://www.thedataincubator.com/fellowship.html) training PhDs to become data scientists. The fellowship selects 2% of its 2000+ quarterly applicants and is free for Fellows. Hiring companies (including EBay, Capital One, Pfizer) pay a recruiting fee only if they successfully hire. You can read about us on [Harvard Business Review] (https://hbr.org/2014/08/the-question-to-ask-before-hiring-a-data-scientist/), [VentureBeat] (http://venturebeat.com/2014/04/15/ny-gets-new-bootcamp-for-data-scientists-its-free-but-harder-to-get-into-than-harvard/), or [The Next Web] (http://thenextweb.com/insider/2015/07/02/data-incubator-opens-a-west-coast-campus-to-groom-the-next-generation-of-data-scientists/), or read about our alumni at [LinkedIn] (http://blog.thedataincubator.com/2016/05/alumni-spotlight-xia-hong/), [Palantir] (http://blog.thedataincubator.com/2015/02/moving-to-palantir-from-mathematics-alumni-spotlight-on-justin-bush/), or the [NYTimes] (http://blog.thedataincubator.com/2015/02/alumni-spotlight-dorian-goldman-using-a-pure-math-background-to-solve-problems-for-the-new-york-times/).

For information on upcoming events, visit our [Eventbrite] (http://www.eventbrite.com/o/the-data-incubator-8342209540).
