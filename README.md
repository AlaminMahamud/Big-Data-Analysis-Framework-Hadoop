# Hadoop - Study

## TOC

- [Big Data OverView](#Big-Data-Overview)
  - [What is Big data](#What-is-Big-data)
  - [What comes under Big Data](#What-comes-under-Big-Data)
- [About](#about)
- [Advantages](#advantages)
- [Analytical Big Data](#analytical-big-data)
- [Benefits of Big Data](#benefits-of-big-data)
- [Hadoop Architecture](#hadoop-architecture)
- [Hadoop Distributed File System](#hadoop-distributed-file-systems)
- [Hadoop Operation Modes](#hadoop-operation-modes)
- [HDFS Command Reference](#hdfs-command-reference)

### Big Data Overview

- 90% of the world's data was generated in the last few years
- beginning of time ~ 2003

  - 5 billion gigabytes
  - entire football field if we try to keep them in a discs

- 2011

  - in every two days same amount data was created

- 2013
  - in every ten minutes

#### What is Big data

Big data is a collection of dataset than cannot be processed using traditional computing techniques. It is not a single technique or a tool, rather it involves many areas of business and technology

#### What comes under Big Data

- **Black box Data** - It is a component of helicopter, airplanes and jets etc.
  It Capture voices of the flight crew, recordings of microphones and earphones, the performance information of the aircraft

- **Social Media Data** - Social Media such as Facebook and Twitter hold information and the views posted by millions of people across the globe

- **Stock Exchange Data** - The Stock Exchange Data holds the Information about buy and sell decissions made on a share of different companies made by the customers

- **Power Grid Data** - THe Power grid data holds the information consumed by a particular node with respect to a base station

- **Transport Data** - Transport Data includes model, capacity, distance and availability of a vehicle

- **Search Engine Data** - Search Engine Retrieves Lots of Data from Different Databases

Thus big data includes huge volumen, high velocity and extensible variety if data
the data will be of three different types

- Structured Data - RDBMS
- Semi Structured Data - XML Data
- UnStructured Data - Word, PDF, Text, Media Logs

### About

Hadoop is an open-source framework that allows to store and process big data in
a distribute d environment acrss clusters of computers using simple programming models

It is designed to scale up form single servers to thousands of machines, each offering local computation and storage

- Big data
- MapReduce Algo
- Hadoop Distributed File System

### Advantages

Advantages of Hadoop
Hadoop framework allows the user to quickly write and test distributed systems. It is efficient, and it automatic distributes the data and work across the machines and in turn, utilizes the underlying parallelism of the CPU cores.

Hadoop does not rely on hardware to provide fault-tolerance and high availability (FTHA), rather Hadoop library itself has been designed to detect and handle failures at the application layer.

Servers can be added or removed from the cluster dynamically and Hadoop continues to operate without interruption.

Another big advantage of Hadoop is that apart from being open source, it is compatible on all the platforms since it is Java based.

### Anlytical Big Data

These includes systems like Massively Parallel Processing (MPP) database systems and MapReduce that provide analytical capabilities for retrospective and complex analysis that may touch most or all of the data.

MapReduce provides a new method of analyzing data that is complementary to the capabilities provided by SQL, and a system based on MapReduce that can be scaled up from single servers to thousands of high and low end machines.

### Benefits of Big Data

Using the information kept in the social network like Facebook, the marketing agencies are learning about the response for their campaigns, promotions, and other advertising mediums.

Using the information in the social media like preferences and product perception of their consumers, product companies and retail organizations are planning their production.

Using the data regarding the previous medical history of patients, hospitals are providing better and quick service.

### Hadoop Architechture

Processing/Computation Layer[Map Reduce]
Storage Layer [Hadoop Distributed file System]

Hadoop

1. MapReduce[distributed computation]
2. HDFS [Distributed storage]

YARN Framework -> Common Utilities

### Hadoop Distributed File System

**Hadoop Common** - These are java libraries and utilities required by other hadoop modules
**Hadoop YARN** - This is a framework for job scheduling and cluster resource management.

### Hadoop Operation Modes

- Local/Stand Alone Mode
- Pseudo Distributed Mode
- Fully Distributed Mode

### HDFS Command Reference

```shell
$HADOOP_HOME/bin/hadoop fs
$HADOOP_HOME/bin/hadoop fs -help
```
## Contributing

Just Clone it, Change, and Make a PR.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Alamin Mahamud** - *Initial work* - [alamin-mahamud](https://github.com/alamin-mahamud)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
