# .github
Welcome to Ingext

This GitHub is the collection of code to leverage the Ingext.Io data streaming operating system. 

## What is Ingext
Ingext is a Streaming Data Processing operating system. Operators define data source and data sinks. Then they move the data from a source to a sink by sending through pipe processes. These processors transform, parse, enrich, and route the records.

Ingext is designed to be a structured way to ingress data into a datastore, such as an S3 bucket or a SIEM. It is high speed; in that it processes twenty (20) times the speed of scripts or Lambdas. It is also 120 times more efficient in startup and execution than a Lambda, as it is always on and ready to process. Lastly, this is a streaming system. Ingext focuses on event driven movement of data (pushing), using pulling only when communicating this external data sources. 

## Kafka and Kinesis
Ingext compliments both Kafka and Kinesis. Kafka and Kinesis focus on the channeling and movement of data, something Ingext also does. But Ingext primarily focuses on processing. For example, you parse data outside of Kafka and Kinesis. Ingext performs transformation, enrichment, and analysis inside the data flow. The result is that the data delivery from Ingext is immediately usable by the destination.

## More Documents
Further Documentation at: https://ingext.readme.io/
![image](https://github.com/user-attachments/assets/864c55ec-1b1b-4bde-b819-44882026988f)
