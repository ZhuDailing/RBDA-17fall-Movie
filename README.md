# RBDA-17fall-Movie

Data source: [Kaggle TMDB 5000](https://www.kaggle.com/tmdb/tmdb-movie-metadata/data)

## Dumbo HPC Environment:
**Java** 1.7.0_79

**Apache Spark MLlib** 1.6.0

**Apache Maven** 3.2.1

To create the Maven project package: 
> mvn archetype:generate 

To build the Maven project: 

> mvn package 

To run the task on Spark: 

> spark-submit --class "RandomForestRegression" rbda-movie-1.0-SNAPSHOT.jar



