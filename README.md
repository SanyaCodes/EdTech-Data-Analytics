# EdTech-Data-Analytics

## Tracking User Activity

In this project, an ed tech firm created a service that delivers assessments, and now lots of different customers (e.g., Pearson) want to publish their assessments on it. 
This project works for these customers to run queries on the data. 

## Tasks

Prepare the infrastructure to land the data in the form and structure it needs
to be to be queried.  You will need to:

- Publish and consume messages with Kafka
- Use Spark to transform the messages. 
- Use Spark to transform the messages so that you can land them in HDFS

You should be able to query your data at the end. 


## Data

To get the data, run 
```
curl -L -o assessment-attempts-20180128-121051-nested.json https://goo.gl/ME6hjp`
```
Here are some example questions that would be answered
1. How many assesstments are in the dataset?
2. What's the name of your Kafka topic? How did you come up with that name?
3. How many people took *Learning Git*?
4. What is the least common course taken? And the most common?
5. Add any query(ies) you think will help the data science team
