# What is Elastic Search

Elastic search is an open source search and analytics engine for different 
types of data, for example, textual, numerical, geospatial, structured, 
and unstructured. 

Elasticsearch is built on Apache Lucene. 

Elasticsearch known for its simple REST APIs, distributed nature, speed 
and scalability. 

And another fact, Elasticsearch is the central component of the Elastic Stack, 
a set of open source tools for data ingestion, storage, analysis, and 
visualization.

# Use case of Elasticsearch / What is Elasticsearch used for? 
1. Application Search
2. Website Search
3. Log Analytics and Logging
4. Security Analytics
5. Business Analytics and enterprise search 

# How does Elasticsearch work? 

-- Log data, web apps, system metrics are the common sources of 
Elasticsearch, especially raw data. 

-- To process these raw data, data ingestion system works to parse, 
nomalized, and enrich before it is indexed in Elasticsearch. 

-- Once indexed in Elasticsearch, users can run complex queries 
against their data and use aggregations to retrive complex summaries 
of their data. 

-- From Kibana, users can create powerful visualizations of their 
data, share dashboards and manage the Elastic stack. 

# What is Elasticsearch index?

The Elasticsearch index is a collection of documents those are 
related to each other. 

Elasticsearch stores data on server as JSON documents. 

Each document correlateds a set of keys (names of field or properties) 
with their corresponding values (strings, numbers, Booleans, dataes, 
arrays of values, geolocations, or other types of data). 

Elasticsearch uses a data structure called an inverted index, which is 
designed to allow very fast full-text searches. 

Every unique words are listed by inverted index that appears in any 
document and indentifies all of the documents each word occurs in. 

During the process of indexing, Elasticsearch stores documents 
and builds an inverted index to make the document searchable  in near 
real-time. 

Indexing is initiated with the index API, through that we can add or 
updated a JSON document in a specific index. 

# What is Logstash? 

Logstash is a server-side data processing pipeline which enables us
to ingest data from multiple sources simultaneously and enrich and 
transform it before it is indexed into Elasticsearch. 









