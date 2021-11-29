# BatchProcessing
Generate and upload data to HDFS/S3 in a file directory. Then aggregate daily global stock in different DB, providing ability to Browse data available.


On the dir run this in shell 

    docker-compose -f spark-docker.yml up -d


## First 
### Data generator
Run the raw stock generator which generates data for each of this data location for three days starting from the first of June. 

## Second
### Daily stock uploader 
The data is uploaded in the HDFS or S3 or in a file in the directory called raw 

## third
### Daily stock Aggregator
Looking at the stock aggregator, the query job is to aggregate the data in all location.

## Fourth
### Global stock Db browser
Look up/Browse the available data in the Global database.
