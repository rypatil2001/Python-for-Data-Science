# Python-for-Data-Science

What is Data?
In our everyday life, we are constantly surrounded by data. The text you are reading now is data. The list of phone numbers of your friends in your smartphone is data, as well as the current time displayed on your watch. As human beings, we naturally operate with data by counting the money we have or by writing letters to our friends.

However, data became much more critical with the creation of computers. The primary role of computers is to perform computations, but they need data to operate on. Thus, we need to understand how computers store and process data.

With the emergence of the Internet, the role of computers as data handling devices increased. If you think about it, we now use computers more and more for data processing and communication, rather than actual computations. When we write an e-mail to a friend or search for some information on the Internet - we are essentially creating, storing, transmitting, and manipulating data.

# What is Data Science?

In Wikipedia, Data Science is defined as a scientific field that uses scientific methods to extract knowledge and insights from structured and unstructured data, and apply knowledge and actionable insights from data across a broad range of application domains.

This definition highlights the following important aspects of data science:

The main goal of data science is to extract knowledge from data, in other words - to understand data, find some hidden relationships and build a model.
Data science uses scientific methods, such as probability and statistics. In fact, when the term data science was first introduced, some people argued that data science was just a new fancy name for statistics. Nowadays it has become evident that the field is much broader.
Obtained knowledge should be applied to produce some actionable insights, i.e. practical insights that you can apply to real business situations.
We should be able to operate on both structured and unstructured data. We will come back to discuss different types of data later in the course.
Application domain is an important concept, and data scientists often need at least some degree of expertise in the problem domain, for example: finance, medicine, marketing, etc.


# Where to get Data

There are many possible sources of data, and it will be impossible to list all of them! However, let's mention some of the typical places where you can get data:

Structured
Internet of Things (IoT), including data from different sensors, such as temperature or pressure sensors, provides a lot of useful data. For example, if an office building is equipped with IoT sensors, we can automatically control heating and lighting in order to minimize costs.
Surveys that we ask users to complete after a purchase, or after visiting a web site.
Analysis of behavior can, for example, help us understand how deeply a user goes into a site, and what is the typical reason for leaving the site.
Unstructured
Texts can be a rich source of insights, such as an overall sentiment score, or extracting keywords and semantic meaning.
Images or Video. A video from a surveillance camera can be used to estimate traffic on the road, and inform people about potential traffic jams.
Web server Logs can be used to understand which pages of our site are most often visited, and for how long.
Semi-structured
Social Network graphs can be great sources of data about user personalities and potential effectiveness in spreading information around.
When we have a bunch of photographs from a party, we can try to extract Group Dynamics data by building a graph of people taking pictures with each other.
By knowing different possible sources of data, you can try to think about different scenarios where data science techniques can be applied to know the situation better, and to improve business processes.

# What you can do with Data

In Data Science, we focus on the following steps of data journey:

1) Data Acquisition
The first step is to collect the data. While in many cases it can be a straightforward process, like data coming to a database from a web application, sometimes we need to use special techniques. For example, data from IoT sensors can be overwhelming, and it is a good practice to use buffering endpoints such as IoT Hub to collect all the data before further processing.
2) Data Storage
Storing data can be challenging, especially if we are talking about big data. When deciding how to store data, it makes sense to anticipate the way you would to query the data in the future. There are several ways data can be stored:
A relational database stores a collection of tables, and uses a special language called SQL to query them. Typically, tables are organized into different groups called schemas. In many cases we need to convert the data from original form to fit the schema.
A NoSQL database, such as CosmosDB, does not enforce schemas on data, and allows storing more complex data, for example, hierarchical JSON documents or graphs. However, NoSQL databases do not have the rich querying capabilities of SQL, and cannot enforce referential integrity, i.e. rules on how the data is structured in tables and governing the relationships between tables.
Data Lake storage is used for large collections of data in raw, unstructured form. Data lakes are often used with big data, where all data cannot fit on one machine, and has to be stored and processed by a cluster of servers. Parquet is the data format that is often used in conjunction with big data.
3) Data Processing
This is the most exciting part of the data journey, which involves converting the data from its original form into a form that can be used for visualization/model training. When dealing with unstructured data such as text or images, we may need to use some AI techniques to extract **features** from the data, thus converting it to structured form.
4) Visualization / Human Insights
Oftentimes, in order to understand the data, we need to visualize it. Having many different visualization techniques in our toolbox, we can find the right view to make an insight. Often, a data scientist needs to "play with data", visualizing it many times and looking for some relationships. Also, we may use statistical techniques to test a hypotheses or prove a correlation between different pieces of data.
5) Training a predictive model
Because the ultimate goal of data science is to be able to make decisions based on data, we may want to use the techniques of Machine Learning to build a predictive model. We can then use this to make predictions using new data sets with similar structures.
Of course, depending on the actual data, some steps might be missing (e.g., when we already have the data in the database, or when we do not need model training), or some steps might be repeated several times (such as data processing).
