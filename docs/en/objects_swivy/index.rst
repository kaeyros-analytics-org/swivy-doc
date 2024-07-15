Channel Cluster
==================
A Channel Cluster represents a big store. It is a major organizational unit within Swivy that can contain multiple Trade Channels.

Trade Channel
=================
A Trade Channel belongs to a Channel Cluster and represents a specific trade area. Trade Channels are categorized by activity size, meaning the same activity can take different amounts of time to perform in different Channel Clusters.

Category
==============
Categories are used to classify different types of activities within Trade Channels.

Point Of Sale
================
A Point Of Sale represents the location of a Channel Cluster on the map, specified by longitude and latitude coordinates.

Activity
==============
An Activity represents the task that will be performed by a Sales Rep. Activities are assigned to Points Of Sale and are tracked throughout the day.

Route
===========
A Route represents the path defined by a set of Points Of Sale linked by coordinates on a map, with specific tasks selected at each Point Of Sale for the Sales Rep to perform.