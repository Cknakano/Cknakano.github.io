---
layout: project
type: project
image: images/javawebcrawlerpic.jpeg
title: Web Crawler
permalink: projects/java-web-crawler
# All dates must be YYYY-MM-DD format!
date: 2021-04-01
labels:
  - Java
summary: A simple web crawler built with Java for ICS 211.
---

<img class="ui medium right floated rounded image" src="../images/webcrawler.png">

This simple web crawler was made solely with Java. The goal was to take in a web link as well as a specified wanted level as an input in the run configurations and output the number of links found in the given web link. It essentially "digs" into the file to display other weblinks up until the specified wanted level has been reached. I had help and advice from peers and a lot of collaboration took place into making this project work. There was no shared code-base, but there was a shared mindset to present different ideas and opinions.

While working on this web crawler I learned a lot. From extracting links given from an HTML document, finding web addresses, using regular expressions to filter through the given input, feeding everything into a breadth-first search (BFS) and depth-first search (DFS) algorithm to display the wanted output, and using everything we learned in 211, there was a lot to process and put together. A lot of new ideas and advanced subjects were brought up and since I had only taken ICS 111 (Intro to Java) at that time, I learned a lot and widened my horizon. The hardest part of this project was the implementation of the graph traversal algorithms which was more formally introduced in the following semester in my ICS 311 (Algorithms) course.
 
Source: <a href = "https://github.com/Cknakano/JavaWebCrawler"><i class="large github icon"></i>Cknakano/Java-Web-Crawler</a>.
