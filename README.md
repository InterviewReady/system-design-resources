# System Design Resources
These are the best resources for System Design on the Internet.
## 
## Video Processing

Transcoding Videos at Scale: https://www.egnyte.com/blog/2018/12/transcoding-how-we-serve-videos-at-scale/

Facebook Video Broadcasting: https://engineering.fb.com/ios/under-the-hood-broadcasting-live-video-to-millions/

Netflix Video Encoding at Scale: https://netflixtechblog.com/high-quality-video-encoding-at-scale-d159db052746

Netflix Shot based encoding: https://netflixtechblog.com/optimized-shot-based-encodes-now-streaming-4b9464204830

## 
## Cluster and Workflow Management

Facebook Cluster Management: https://engineering.fb.com/data-center-engineering/twine/

Google Autopilot - Autoscaling: https://dl.acm.org/doi/pdf/10.1145/3342195.3387524

Netflix Workflow Orchestration: https://netflix.github.io/conductor/

Opensource Workflow Management: https://github.com/spotify/luigi

Meta Hardware Management: https://engineering.fb.com/2020/12/09/data-center-engineering/how-facebook-keeps-its-large-scale-infrastructure-hardware-up-and-running/

Meta Capacity Assignment: https://engineering.fb.com/2022/09/06/data-center-engineering/viewing-the-world-as-a-computer-global-capacity-management/

## 
## Intra-Service Messaging 
 
What is a message queue: https://www.cloudamqp.com/blog/what-is-message-queuing.html

AirBnb Idempotency: https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb

Nginx Service Mesh: https://www.nginx.com/learn/service-mesh/

## 
## Message Queue Antipattern

DB as queue Antipattern: http://blog.codepath.com/2012/11/15/asynchronous-processing-in-web-applications-part-1-a-database-is-not-a-queue/

Using a database as a message queue: https://softwareengineering.stackexchange.com/questions/231410/why-database-as-queue-so-bad

Anti-pattern of DB as a queue: http://mikehadlow.blogspot.com/2012/04/database-as-queue-anti-pattern.html

Drawbacks of DB as a queue: https://www.cloudamqp.com/blog/why-is-a-database-not-the-right-tool-for-a-queue-based-system.html

## 
## Service Mesh

Kubernetes Service Mesh: https://akomljen.com/kubernetes-service-mesh/

Kubernetes Sidecar:https://www.weave.works/blog/introduction-to-service-meshes-on-kubernetes-and-progressive-delivery

Service Mesh: https://www.weave.works/blog/introduction-to-service-meshes-on-kubernetes-and-progressive-delivery

NginX Service Mesh: https://www.nginx.com/learn/service-mesh/

## 
## Practical System Design

Facebook Messenger Optimisations: https://spectrum.ieee.org/how-facebooks-software-engineers-prepare-messenger-for-new-years-eve

YouTube Architecture: http://highscalability.com/youtube-architecture

YouTube scalability 2012: https://www.youtube.com/watch?v=w5WVu624fY8

Distributed Design Patterns: http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html

Monolith to Microservice: https://martinfowler.com/articles/break-monolith-into-microservices.html

Zerodha Tech Stack: https://zerodha.tech/blog/hello-world/

## 
## Distributed File System

Open Source Distributed File System: https://docs.ceph.com/en/latest/architecture/

Amazon S3 Performance hacks: https://aws.amazon.com/blogs/aws/amazon-s3-performance-tips-tricks-seattle-hiring-event/

Amazon S3 object expiration: https://aws.amazon.com/blogs/aws/amazon-s3-object-expiration/

## 
## Time Series Databases

Pintrest Time Series Database: https://medium.com/pinterest-engineering/goku-building-a-scalable-and-high-performant-time-series-database-system-a8ff5758a181

Uber Time Series DB: https://eng.uber.com/aresdb/

TimeSeries Relational DB: https://blog.timescale.com/blog/time-series-data-why-and-how-to-use-a-relational-database-instead-of-nosql-d0cd6975e87c/

Facebook Gorilla Time Series DB: http://www.vldb.org/pvldb/vol8/p1816-teller.pdf

## 
## Rate Limiting

Circuit Breaker Algorithm: https://martinfowler.com/bliki/CircuitBreaker.html

Uber Rate Limiter: https://github.com/uber-go/ratelimit/blob/master/ratelimit.go

##
## In Memory Database - Redis

Redis Official Documentation : https://redis.com/

Learn Redis through Redis University  : https://university.redis.com/

Redis Open Source Repo : https://github.com/redis/redis

Redis Architechture : https://medium.com/opstree-technology/redis-cluster-architecture-replication-sharding-and-failover-86871e783ac0

## 
## Network Protocols

What is HTTP: https://engineering.cred.club/head-of-line-hol-blocking-in-http-1-and-http-2-50b24e9e3372

QUIC Protocol: https://www.akamai.com/blog/performance/http3-and-quic-past-present-and-future

TCP Protocol algorithms: https://ee.lbl.gov/papers/congavoid.pdf (First 10 pages are important)

WebRTC: https://webrtc.github.io/webrtc-org/blog/2012/07/23/a-great-introduction-to-webrtc.html

WebSockets: https://datatracker.ietf.org/doc/html/rfc6455#section-1.2

Dynamic Source Routing using QUIC: https://fb.watch/fSEbI4KHlA/

## 
## Chess Engine Design

Chess Engine Building: https://www.youtube.com/watch?v=U4ogK0MIzqk

## 
## Subscription Management System

Subscription Manager: https://netflixtechblog.com/building-a-rule-based-platform-to-manage-netflix-membership-skus-at-scale-e3c0f82aa7bc

## 
## Google Docs

Operational Transform: http://www.codecommit.com/blog/java/understanding-and-applying-operational-transformation

Google Docs: https://www.youtube.com/watch?v=uOFzWZrsPV0&list=PLXDe3d8o9VFtydBV5biyz9iS3WqKsBMD5&index=3

## 
## API Design

API Design: https://medium.com/airbnb-engineering/building-services-at-airbnb-part-1-c4c1d8fa811b

Swagger APIs: https://swagger.io/docs/specification/about/

## 
## NoSQL Database Internals

Cassandra Architecture: https://docs.datastax.com/en/archived/cassandra/3.0/cassandra/architecture/archIntro.html

Google BigTable Architecture: https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf

Amazon Dynamo DB Internals: https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html

Design Patterns in Amazon Dynamo DB: https://www.youtube.com/watch?v=HaEPXoXVf2k

Internals of Amazon Dynamo DB: https://www.youtube.com/watch?v=yvBR71D0nAQ

## 
## NoSQL Database Algorithms

Hyperloglog Algorithm: https://odino.org/my-favorite-data-structure-hyperloglog/

Log Structured Merge Tree: https://www.cs.umb.edu/~poneil/lsmtree.pdf

Sorted String Tables and Compaction Strategies: https://github.com/scylladb/scylla/wiki/SSTable-compaction-and-compaction-strategies

Leveled Compaction Cassandra: https://www.datastax.com/blog/leveled-compaction-apache-cassandra

Scylla DB Compaction: https://github.com/scylladb/scylla/wiki/SSTable-compaction-and-compaction-strategies

Indexing in Cassandra: https://www.bmc.com/blogs/cassandra-clustering-columns-partition-composite-key/

## 
## Database Replication

Database replication: https://dev.mysql.com/doc/refman/8.0/en/replication.html

Netflix Data replication - Change Data Capture: https://netflixtechblog.com/dblog-a-generic-change-data-capture-framework-69351fb9099b

LinkedIn Logging Usecases: https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying

## 
## Containers and Docker 

Facebook Twine Containerization: https://engineering.fb.com/developer-tools/zookeeper-twine/

CloudFlare Containerization: https://blog.cloudflare.com/cloud-computing-without-containers/

Docker Architecture: https://docs.docker.com/get-started/overview/#docker-architecture

## 
## Capacity Estimation

Google Capacity Estimation: https://www.youtube.com/watch?v=modXC5IWTJI

Scalability at YouTube 2012: https://www.youtube.com/watch?v=G-lGCC4KKok

Back of envelope Calculations at AWS: https://www.youtube.com/watch?v=-3qetLv2Yp0

Capacity Estimation: http://static.googleusercontent.com/media/research.google.com/en//people/jeff/stanford-295-talk.pdf

## 
## Publisher Subscriber

Oracle Publisher Subscriber: https://docs.oracle.com/cd/B10501_01/appdev.920/a96590/adg15pub.htm

Amazon Pub Sub Messaging: https://aws.amazon.com/pub-sub-messaging/

Asynchronous processing: http://blog.codepath.com/2013/01/06/asynchronous-processing-in-web-applications-part-2-developers-need-to-understand-message-queues/

Async Request Response: https://www.enterpriseintegrationpatterns.com/patterns/conversation/RequestResponse.html

## 
## Event Driven Architectures

Martin Fowler- Event Driven Architecture: https://www.youtube.com/watch?v=STKCRSUsyP0

Event Driven Architecture: https://martinfowler.com/articles/201701-event-driven.html

## 
## Hexagonal Architectures

Hexagonal Architecture: https://netflixtechblog.com/ready-for-changes-with-hexagonal-architecture-b315ec967749

## 
## Microservices

Monolith Architecture: https://buttercms.com/books/microservices-for-startups/should-you-always-start-with-a-monolith/

Monoliths vs Microservices: https://articles.microservices.com/monolithic-vs-microservices-architecture-5c4848858f59

Microservices: http://highscalability.com/blog/2018/4/5/do-you-have-too-many-microservices-five-design-attributes-th.html

Uber Nanoservices antipattern: https://www.youtube.com/watch?v=kb-m2fasdDY

Uber Domain oriented microservice: https://eng.uber.com/microservice-architecture/

## 
## Load Balancing

Load Balancer with Sticky Sessions: https://stackoverflow.com/questions/10494431/sticky-and-non-sticky-sessions

Citrix what is load balancing: https://www.citrix.com/en-in/solutions/app-delivery-and-security/load-balancing/what-is-load-balancing.html

Nginx Load Balancing: https://www.nginx.com/resources/glossary/load-balancing/

Consistent hashing: https://michaelnielsen.org/blog/consistent-hashing/

## 
## Alerts and Anomaly Detection

Outlier Detection: https://towardsdatascience.com/outlier-detection-with-isolation-forest-3d190448d45e

Anomaly Detection: https://towardsdatascience.com/machine-learning-for-anomaly-detection-and-condition-monitoring-d4614e7de770

Uber Real Time Monitoring and Root Cause Analysis Argos: https://eng.uber.com/argos-real-time-alerts/

Microsoft Anomaly Detection: https://www.youtube.com/watch?v=12Xq9OLdQwQ&t=0s

Facebook Data Engineering: https://engineering.fb.com/2016/05/09/core-data/introducing-fblearner-flow-facebook-s-ai-backbone/

LinkedIn Real Time Alerting: https://engineering.linkedin.com/blog/2019/06/smart-alerts-in-thirdeye--linkedins-real-time-monitoring-platfor

LinkedIn Isolation Forests: https://engineering.linkedin.com/blog/2019/isolation-forest

## 
## Distributed Logging

Uber Distributed Request Tracing: https://eng.uber.com/distributed-tracing/

Pintrest Logging: https://medium.com/@Pinterest_Engineering/open-sourcing-singer-pinterests-performant-and-reliable-logging-agent-610fecf35566

Google Monitoring Infrastructure: https://www.facebook.com/atscaleevents/videos/959344524420015/

## 
## Metrics and Text Search Engine

Facebook real time text search engine: https://www.facebook.com/watch/?v=432864835468

Elastic Search Time Based Querying: https://www.elastic.co/guide/en/elasticsearch/guide/current/time-based.html

Elastic Search Aggregation: https://www.elastic.co/guide/en/elasticsearch/guide/current/aggregations.html

## 
## Single Point of Failure

Avoiding Single Points of Failure: https://medium.com/the-cloud-architect/patterns-for-resilient-architecture-part-3-16e8601c488e

Netflix Multi-Region Availability: https://netflixtechblog.com/active-active-for-multi-regional-resiliency-c47719f6685b  

Oracle Single Points of failure: https://docs.oracle.com/cd/E19693-01/819-0992/fjdch/index.html

DNS single point of failure 2004: http://www.tenereillo.com/GSLBPageOfShame.htm

Sharding: https://medium.com/@jeeyoungk/how-sharding-works-b4dec46b3f6

## 
## Location Based Services

Google S2 library: https://blog.christianperone.com/2015/08/googles-s2-geometry-on-the-sphere-cells-and-hilbert-curve/

## 
## Batch Processing

Map Reduce Architecture: https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf

## 
## Real Time Stream Processing

LinkedIn Brooklin- Real time data streaming: https://engineering.linkedin.com/blog/2019/brooklin-open-source

Netflix Real Time Stream Processing: https://netflixtechblog.com/keystone-real-time-stream-processing-platform-a3ee651812a

KSQLDB for Kafka: https://docs.ksqldb.io/en/latest/operate-and-deploy/how-it-works/

## 
## Caching

Google Guava Cache: https://github.com/google/guava/wiki/CachesExplained

Caching (See the README): https://github.com/ben-manes/caffeine/

Caching: http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html

Microsoft Caching Guide: https://docs.microsoft.com/en-us/previous-versions/msp-n-p/dn589802(v%3dpandp.10)

Caching patterns: https://hazelcast.com/blog/a-hitchhikers-guide-to-caching-patterns/

## 
## Distributed concensus

Paxos: http://ifeanyi.co/posts/understanding-consensus/

Raft: https://raft.github.io/

## 
## Authorization

Designing an Authorization Model for an Enterprise: https://cerbos.dev/blog/designing-an-authorization-model-for-an-enterprise

##
## Content Delivery Network

AWS CloudFront CDN with S3: https://aws.amazon.com/blogs/networking-and-content-delivery/amazon-s3-amazon-cloudfront-a-match-made-in-the-cloud/

##
## System Design Resources

Designing Data Intensive Applications: https://amzn.to/3SyNAOy

InterviewReady Videos: [https://interviewready.io](https://interviewready.io?_aff=HELLOWORLD&source=github)
