# spotify-datapipeline-project

## Introduction
In this project, we build an ETL(Extract, Transform, Load) pipeline, in which pipeline retrieve data from Spotify using Spotify API, transform it to a desired format, and load it into an AWS data store.
### Flow of Project
1) Integrating with Spotify API and extracting Data using Python
2) Deploying code on AWS Lambda for Data Extraction
3) Adding trigger to run the Lambda function for extraction automatically
4) Writing transformation function
5) Building automated trigger on transformation function
6) Store files on S3 properly
7) Building Analytics Tables on data files using Glue and Athena

## Technology Used
* Programming Language - Python
* Amazon Web Service (AWS)
  1) Lambda
  2) CloudWatch
  3) S3 (Simple Storage Service)
  4) S3 Trigger
  5) Glue Crawler
  6) Glue Catalog
  7) Athena
 
## Dataset/API
Spotify API contain the information about Album, Artist and Songs - [Spotipy API](https://spotipy.readthedocs.io/en/2.22.1/)

## Installed Packages
```
pip install pandas
pip install numpy
pip install spotipy

```
