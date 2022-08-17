# full-text-Search

What Does Full-Text Search Mean?

A full-text search is a thorough form of searching that matches each word in the search request with each word in the database or document. The full-text search approach is widely used by web search engines and document editing software in capabilities for searching a text database either on the internet or on a computer's local drive; it enables users to find a word or phrase anywhere in the database or document.

# Indexing
The full-text search engine may directly scan the contents of the documents with each query when working with a limited number of documents; this technique is known as "serial scanning." This is what various search-related tools do.
However, the challenge of full-text search is frequently split into two tasks: indexing and searching, depending on how many documents need to be searched or how many search queries need to be executed. All of the papers' text will be scanned during the indexing step, and a list of search keywords will be created (often called an index, but more correctly named a concordance). Only the index is referred to during the search stage when a specific query is run, not the content of the original documents.
Every term or phrase found in a document will be entered into the index by the indexer, who may also mark its location within the text. Stop words that are both common and lack sufficient significance to be helpful in searching (such as "the" and "and") are often ignored by the indexer. Additionally, some indexers use language-specific stemming on the terms they are indexing. The terms "drives," "drove," and "driven," for instance, will all be listed in the index under the single concept word "drive."

# Considerations before using full-text search
No matter which database you are using, before implementing a full-text search solution, you will have to take these considerations into mind.
• Necessary feature -You may improve text search by giving your database a full-text index. You may still require extra capabilities like auto-complete recommendations, synonym search, or custom scoring for pertinent results..
• Architectural complexity- Your architecture will become more complex as a result of the additional software you used to query two different sources and manage separate systems.
• Costs-Whether a solution is built in-house or uses a third-party tool, additional charges are to be expected.

# Apache Lucene

Doug Cutting originally created Apache Lucene as a free and open-source search engine library in Java. It is distributed under the Apache Software License and is backed by the Apache Software Foundation. Applications for non-research search are frequently built on the Lucene standard base.
Despite being appropriate for any application that needs complete text indexing and searching capabilities, Lucene is well known for its use in the development of local, single-site search and Internet search engines.A function to conduct a fuzzy search based on edit distance is provided by Lucene.Recommendation engines have also been implemented using Lucene.For instance, Lucene's "MoreLikeThis" Class can produce suggestions for documents that are comparable. When compared to citation-based document similarity metrics like co-citation and co-citation proximity analysis, the word vector-based similarity technique of "MoreLikeThis" performed significantly better in recommending papers with closely comparable structural properties. In contrast, citation-based document similarity metrics have a tendency to be more suited for suggesting papers that are more widely linked.

# Solr VS Elasticsearch

# Overview of Solr

The Apache Lucene search function is provided by Solr, an open-source search platform developed in the Lucene Java library.
It has been a staple of the search engine market for nearly ten years; it is a tested product with a sizable and diverse user base. Automatic load balancing, distributed reindexing, failover, and recovery queries are all features offered by Solr.
It can develop into a highly dependable, scalable, fault-tolerant search engine if properly designed and managed. Solr is utilized by a number of Internet behemoths, like Netflix, eBay, Instagram, and Amazon (Cloud Search), since it can index and search numerous webpages.
# The list of key features includes:
1.	Full-text search 
2.	Highlight 
3.	Multi-array Search 
4.	Real-time indexing 
5.	Dynamic Clustering 
6.	Database integration 
7.	NoSQL functionality and productive document handling (e.g. words and PDF files) 

# Overview of Elastic search

Built on top of the Apache Lucene library, Elasticsearch is a distributed, open source (Apache 2 license), RESTful search engine.
It offers a supported multi-tenant, distributed full-text search engine, HTTP web interface (rest), and JSON documents without schema. Elastic search has official client libraries for Java, Groovy, PHP, Ruby, Perl, Python, .net, and JavaScript.
Indexes in distributed search engines can be split up into smaller parts, and each part may include numerous copies. A fragment may exist on one or more Elasticsearch nodes. Additionally serving as a coordinator, its engine assigns tasks to the appropriate pieces.
Scalability of searches in Elasticsearch is close to real-time. Multi-tenant is one of its primary characteristics.

# The list of key features includes: 
1. Distributed Search 
2. Multi-lease period  
3. A string of Analyzers 
4. Scan Search 
5. Group Aggregation

 # Souces
1.	Wikipedia
2.	Mongodb.com
3.	Techopedia
4.	Stackoverflow

