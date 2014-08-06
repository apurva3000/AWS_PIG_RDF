AWS_PIG_RDF
===========

This project analyzes subsets and fullset of data kept in RDF triple store format which has around a billion vertices on AWS cluster


I used to purchase a Amazon EC2 account which gave me access to all the Amazon Facilities.
I used Amazon Elastic Mapreduce facility for running the PIG scripts (as it comes with PIG and HIVE) installed.
For executing the same, The data was copied from a s3n source and I used 8 m3.xlarge nodes for processing the same.
These 8 nodes give enough power and memory to execute the scripts on billion vertices in about few minutes.

The total cost for executing 4 scripts (2x 2 files in the repo) was around 10USD

The whole description is stated in separate text files about the data and operations, the pig scripts are also given.
