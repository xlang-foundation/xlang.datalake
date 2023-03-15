# xlang.datalake
A datalake based on xlang and native file system to support namespace, blob, replication, version, SQL
# Background  

**Open-Source project is programmer’s novel**

In the past, had accumulated many experience on Microsoft’s document based database Comsosdb (Azure Cosmos DB), and its script language Scope (external side called U-SQL); and comparing with this Cosmos DB, had done some kind of technical research on MangoDB; this is one  kind, and other kinds:  
- had long time technical experiences on relational database, and between years 2014-2016, was trying to integrate node-based database Neo4j Graph DB into my product, that time paid attention on NoSQL database, and bla bla bla…  
- AND during deep learning research and product development stage and practices on big data stuff, dataset is very important concept, what is dataset, a collection of data with any or free style hierarchical structure…  
- Even more, how do you think about python pickle serialization, PyTorch directly uses it to store its weights, so we need to also consider this into the design, ***interesting idea or strange***?  
- When we do a website, for example, search-based documents website, like https://numpy.org , can we directly use existed files from native file system as its searchable document database?   
- If we want to do a website with image and even large size file like video files ( .mp4, .avi)? most of time, we use file system to directly store these files, not silly put into relational database as bob.   
- For database ( sql or no-sql), schema is very important, pre-defined schema or just meta data based schema?  
- when you have very very large amount of files stored in your local disk, how to do quick search? treat it like a data-lake with automatically indexing and also can be replicated into other computer like you are using cloud based data-lake.  

# Important Concepts and terms  
- Document Database with json, yaml, html, excel file, word file, pdf, image file, video files etc.  
- Document meta data --- retrieve from file system and file headers.  
- Document Parser—such as pdf parser, ms word parser etc.  
- Structured data  
- Table—still in relational database domain, and consider add colum-based table like Parquet  
- Join operator cross all kind of data  
- Container is just like a folder, folder path looks like namespace  
But file also can play like a container, for example, sqlite file, it is a container  


**** Planning and welcome to join this project  ****  

