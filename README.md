# UberAnalysis

A analysis of Ubers big data using hadoop and MapReduce. The problem statements are
1)In this problem statement, we will find the days on which each basement has more trips.
2)In this problem statement, we will find the days on which each basement has more number of active vehicles.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites


```
hadoop
jdk
```

### Installing


```
#start hadoop
start-all.sh
```
```
export the .java file to .jar file. 
```

## Running the Analysis
Add the dataset into HDFS

```
hadoop dfs -copyFromLocal /home/rohit/Downloads/uber /uber
```
Running the  problem statement
```
hadoop jar /home/rohit/Desktop/BDA/Uber1.jar /uber /Output
```


## Built With

* Hadoop
* JDK



