# Destiny

A big data processing project using Spark, Scala, Apache Zeppelin to analyze the winning rate of MOBA like game. 

## Deployment

### Environment

* Apache Spark
* Apache Hadoop
* Apache Zeppelin

### Data

* Champions stats
* Match details

### Collecting data

* Configure `Crawler.scala ` with proper credentials to get data which finally will be saved in ".csv" format
* Start running using `Starter.scala`.
* Machine learning part in folder `MLPart`. 

## Results

* Winning rate varies by versions of game. 
* Combinations of champions matter. 
* System can process up to 50k rows. 
