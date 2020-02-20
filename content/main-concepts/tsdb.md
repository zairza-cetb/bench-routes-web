---
title: Bench Routes TSDB
weight: 15
---

A time-series database (TSDB) is a database optimized for time-stamped or time-series data. Time series data are simply measurements or events that are tracked time-series and monitored. In these types of models, the data points are saved in stamps of time rather than any ID which is generally the case of SQL and NoSQL databases.
Why do we need a time-series database? 

In traditional databases, values are stored simply as rows in tables or as an object, in a document. However, the data values in this project need to be stored in every fraction of a second. The use of traditional data doesn’t seem to be convenient when it comes to storing and retrieving large amounts of data. Further, the traditional data models will increase time space and time complexity during the course of data extraction in sorted time order.

In a tsdb, the data is stored at a particular timestamp(at a particular instant of time) in which each record can be represented as a hash block. This block can be stored in the form of a chain of events, thereby forming a blockchain. This chain will be highly useful in making graphs on the UI end, as the time complexity of the extraction of data points would be highly optimized (since the extraction of data would follow chain propagation).
