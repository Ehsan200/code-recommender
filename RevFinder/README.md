## Introduction

This is a set of python codes to implement Revfinder Methodology for recommending reviewers for different projects automatically. This is the first public implementation of this paper's idea. 

## Data Gathering

The program's needed data has some little differences with the origin paper. We are going to compare our results with outputs of this idea so we had to customized data using part of this algorithm based on our work.

## To Use
for using this code you can see our paper and find out how could you format your data that this code can identify it and runs the algorithm on your data.
**stringCompare** file includes base code algorithms that are from origin paper which you can access its data and this file's origin code in this [link](https://github.com/patanamon/revfinder/blob/master/). **scorer** is used to gives us some metrics such as f1, precision and recall of our RevFinder on data and the core implementation of algorithm and data gathering is in **rev_finder** file. 

October 17, 2023