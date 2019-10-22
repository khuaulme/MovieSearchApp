# FTS_MovieSearch
Basic movie search engine for MongoDB Atlas Full Text Search

Giving your users the ability to find exactly what they are looking for in your application is critical for a fantastic user experience. With MongoDB Atlas’s new Full-Text Search feature, we have made it easier than ever to integrate simple but sophisticated search capabilities into your MongoDB applications. To demonstrate just how easy it is, let’s build a movie search engine - in only 10 minutes.
![image](https://user-images.githubusercontent.com/15270412/67252435-39d22300-f473-11e9-9d11-e3ea65480cba.png)


Built on Apache Lucene, Atlas’ Full-Text Search adds document data to a full-text search index to make that data searchable in a highly performant, scalable manner. 

For a detailed tutorial with screenshots and sample code, visit this link: http://bit.ly/FTS_MovieTutorial . This tutorial will guide you through how to build a web application to search for movies based on a topic using Atlas’ sample movie data collection. We will create an FTS index on that sample data. Then we will query on this index to filter, rank and sort through those movies to quickly surface movies by topic.

  Armed with a basic knowledge of HTML and Javascript, here are the tasks we will accomplish:
#### TO-DO LIST
###### ▢ &nbsp; Spin up an Atlas cluster and load sample movie data
###### ▢ &nbsp; Create a Full-Text Search Index
###### ▢ &nbsp; Write an aggregation pipeline with $searchBeta operator
###### ▢ &nbsp; Create a RESTful API to access data
###### ▢ &nbsp; Call from the front end


  Before we get started, we will need:
1. A MongoDB M30 cluster in Atlas running 4.2. *(This is a temporary minimum setting while Full-Text Search is still in beta. We do have plans to expand FTS to more cluster sizes in the future.)*
2. Atlas Sample Data loaded into the Atlas cluster directly from the Atlas UI. You can get this by clicking the &nbsp; <button style="border-radius: 5px; width:35px;">...</button>&nbsp; button and **Load Sample Dataset**.
