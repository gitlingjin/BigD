BigData
==========================================
MSiA 431 - Analytics for Big Data

This course covers a variety of topics and tools in big data. Most of the topics are about the Hadoop ecosystem, however select databases outside of Hadoop will also be considered.

Week 1: Fundamentals of Big Data and Hadoop

Week 2&3: MapReduce

Week 4: Advanced MapReduce

Week 5: Pig

===========================================
1. WordCount
  - Introductory example

2. Assignment #1: Basic Mapper+Reducer

- Exercise#1: Maximum temperature per year
  
  - Input: two files with temperature readings from various weather stations (The data is from the NOAA web site.)
      - Year = positions at 15‐19
      - Temperature = positions at 87‐92 (can be negative)
      - If Temperature = 99999, it should be interpreted as missing value.
      - The temperature quality is in position 92‐93. If it is in the range {0,1,4,5,9}, then the temperature reading is       accurate and satisfactory.

  - You need to write a mapreduce job in java that will calculate the maximum temperate for each year. 
  
  - Output: pairs (year,temperature).
      
- Exercise#2: A machine learning classification problem from IBM
  - Task: to get the average value of the fourth column per every different combination of columns 30,31,32,32 among all records with the last column equal to ‘false’ 
  - Your result should look like:
    - 1,0,1,1, average value of column 4
    - 0,0,1,0, average value of column 4

5. Assignment #4: K-means clustering algorithm implementation

- Assume that:

    1) The number of clusters is given in advance.
    
    2) The input files all reside in one folder. Each record corresponds to a data observation. Each
    column corresponds to a coordinate of the underlying vector. The coordinates are separated by
    comma.
    
    3) The output must be a set of centroids.
    
- As an external ‘tool’ you are free to use the tool of your choice, but all mapreduce routines must be written in java.
  
  
  
