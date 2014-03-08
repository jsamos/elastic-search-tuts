elastic-search-tuts
===================

A collection of actually helpful Elastic Search tutorials and videos

#Noob
[YouTube - Intro to elastic search](http://www.youtube.com/watch?v=XCHYo0CsZrk)

Very simple intro  
concepts CREATE, GET/ID, SEARCH, Multiple Nodes 


[YouTube - Getting started](http://www.youtube.com/watch?v=P6VqWiXsGIo) ([Companion Blog Post](http://blog.qbox.io/qbox-elasticsearch-tutorial-1))  
intro to the series by the people at [Qbox](http://qbox.io/)  

concepts:
* tweaking the config (1:07)  
   * cluster nameing
   * node naming
   * datapath
* start with custom config (2:51)  
* Bulk Indexing (5:10)
* Search (8:30)

#search
[YouTube - Getting Down and Dirty with ElasticSearch](http://www.youtube.com/watch?v=7FLXjgB0PQI)

The strenth of this tutorial is definitely defining you mappings and using them in searchs

Concepts:
* multi index/type searches (15:58)
* pagination (16:40)
* search lite (17:20)
* Field Data Types (19:37) *Note basically start here!  
    * Mapping (20:27)
    * Inverted Index (22:13)
    * Analyzers (24:10)
    * Mapping structure (30:28)
    * Applying mappings (31:40)
* Query DSL (32:22)
    * Filters Vs Queries (33:50)
    * Filtered Queries (34:59)
    * Sorting (35:26)
    * Ranges (35:40)
    * Facets (Summarization) (35:56)
* Autocomplete example (37:00)  
    * Ngrams (37:24)
    * Multifields (39:30)
    * must, must_not, should (40:49)

#Broad Strokes
[YouTube - ElasticSearch Introduction and lessons](http://www.youtube.com/watch?v=QDCpkXYXaCI)

concepts:
* API urls (7:00)  
  * PUT (8:56)  
  * GET Indexing (10:30)
  * _search (11:00)
* Best practices (15:15)
* 3rd Party Plugins (21:30)
* Python Libs (22:15)
