### Service Matrix

This chart lets you compare Oracle Cloud Services with other Cloud Platform companies as well as niche players and open source solutions. 

Special thanks to Joshua Levy, the original creator of the AWS Open Guide, on which this table is based (disclosure - I am also a contributor to that repo).


| Service                       | Oracle Cloud                        AWS                                      | Microsoft Azure                    | Google Cloud                           |   Other providers                          | Open source “build your own”                               |
|-------------------------------|------------------------------------------------------------------------------|------------------------------------|----------------------------------------|--------------------------------------------|------------------------------------------------------------|
| Virtual server                | Compute                             | EC2                                    | Virtual Machine                    | Compute Engine (GCE)                   |DigitalOcean                                | OpenStack                                                  |
| Virtual server                | Compute                             | EC2                                    | Virtual Machine                    | Compute Engine (GCE)                   |DigitalOcean                                | OpenStack                                                  |
| Block storage                 | Block Storage                       | EBS                                    | Storage Account                    | Persistent Disk                        |DigitalOcean Volumes                        | NFS                                                        |
| CDN                           | Dyn                                 | CloudFront                             | CDN                                | Cloud CDN                              |                                            | Apache Traffic Server                                      |
| Data warehouse                | DBaaS (Exadata)                     | Redshift                               | SQL Data Warehouse                 | BigQuery                               |Oracle, IBM, SAP, HP, many others           | Greenplum                                                  |
| Email                         |                                     | SES                                    |                                    |                                        |Sendgrid, Mandrill, Postmark                |                                                            |

| File storage                  | Object Storage                      | S3                                     | Storage Account                    | Cloud Storage                          |                                            | Swift, HDFS                                                |

| PaaS                          | Application Container Cloud         | Elastic Beanstalk                      | Web Apps                           | App Engine                             |Heroku, AppFog, OpenShift                   | Meteor, AppScale, Cloud Foundry, Convox                    |
| Serverless, microservices     | Functions                            | Lambda, API Gateway                   | Function Apps                      | Functions                             |PubNub Blocks, Auth0 Webtask                | Kong, Tyk                                                  |
| Container, cluster manager    | Container                           | ECS                                    | Container Service                  | Container Engine, Kubernetes           |                                            | Kubernetes, Mesos, Aurora                                  |
| SQL datastore                 | DBaaS, MySQL Service                | RDS                                    | SQL Database                       | Cloud SQL                              |                                            | MySQL, PostgreSQL                                          |
| Key-value store, column store | NoSQL Database                      | DynamoDB                               | Tables, DocumentDB                 | Cloud Datastore, Bigtable              |                                            | Cassandra, CouchDB, RethinkDB, Redis                       |
| Memory cache                  |                                     | ElastiCache                            | Redis Cache                        | App Engine Memcache                    |                                            | Memcached, Redis                                           |
| Search                        |                                     | CloudSearch, Elasticsearch (managed)   | Search                             |                                        |Algolia, QBox                               | Elasticsearch, Solr                                        |
| Business intelligence         | Data Visualization Cloud, BI Cloud  | QuickSight                             | Power BI                           | Data Studio 360                        |Tableau                                     |                                                            |
| Message broker                | Integration, Messaging              | SQS, SNS, IoT                          | Service Bus                        | Pub/Sub                                |                                            | RabbitMQ, Kafka, 0MQ                                       |
| Streaming, distributed log    | Event Hub                           | Kinesis                                | Event Hubs                         | Dataflow                               |                                            | Kafka Streams, Apex, Flink, Spark Streaming, Storm         |
| MapReduce                     | Big Data                            | EMR                                    | HDInsight, DataLake Analytics      | Dataproc                               |Qubole                                      | Hadoop                                                     |
| Monitoring                    | Management Cloud                    | CloudWatch                             | Monitor                            | Monitoring                             |                                            | Prometheus(?)                                              |
| Metric management             | Application Performance Monitoring  |                                        | Application Insights               |                                        |                                            | Graphite, InfluxDB, OpenTSDB, Grafana, Riemann, Prometheus |
| Load balancer                 |                                     | CLB/ALB                                | Load Balancer, Application Gateway | Load Balancing                         |                                            | nginx, HAProxy, Apache Traffic Server                      |
| DNS                           | Dyn                                 | Route53                                | DNS                                | DNS                                    |                                            | bind                                                       |
| Git hosting                   |  Developer Cloud Service            | CodeCommit                             | Visual Studio Team Services        | Cloud Source Repositories              |GitHub, BitBucket                           | GitLab                                                     |
| User authentication           |  Mobile Cloud Service               | Cognito                                | Azure Active Directory             |    Firebase Authentication             |                                            | oauth.io                                                   |
| Mobile app analytics          |  Mobile Cloud Service               | Mobile Analytics                       | HockeyApp                          | Firebase Analytics                     |Mixpanel                                    |                                                            |
| Mobile app testing            |                                     | Device Farm                            | Xamarin Test Cloud                 | Firebase Test Lab                      |BrowserStack, Sauce Labs, Testdroid         |                                                            |
| Managing SSL/TLS certificates |                                     | Certificate Manager                    |                                    |                                        |Let's Encrypt, Comodo, Symantec, GlobalSign |                                                            |
| Speech Recognition and NLP    |                                     | Lex                                    | Cognitive services                 | Cloud Speech API, Natural Language API |AYLIEN Text Analysis API, Ambiverse         |Stanford's Core NLP Suite, Apache OpenNLP, Apache UIMA      |
| Text-to-speech                |                                     | Polly                                  |                                    |                                        |Nuance, Vocalware, IBM Watson               |Mimic, eSpeak, MaryTTS                                      |
| Image recognition             |                                     | Rekognition                            |Cognitive services                  |   Vision API                           | IBM Watson, Clarifai                       |                                                            |