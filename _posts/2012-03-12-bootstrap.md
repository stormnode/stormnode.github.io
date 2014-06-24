---
layout: post
title: Bootstrap
tags:
- bootstrap
---
I have been programming exclusively in Node.js for almost two years.  
Prior to that I was programming in Java, Python and Ruby.  I find that picking
one language and sticking with it makes you more fluent.  When I lived in
Argentina the same was true for speaking Spanish.  It was easier to master the
language when you did not switch back to English.

I have a small consulting firm in Albuquerque, New Mexico and we work on different
Node related projects.  Currently, I am looking for full time work.  I would like to
find a small company where I can make a difference and where there are mutual
synergies between our interests.

All of the projects I work on have a common theme of tools that I use.  I do both
front end browser work and back end persistence work.  The glue that holds these
two pieces together is Backbone.  

I believe that all projects on the web should have a public facing REST Api.  
This enables any developer in the world to access your data programmatically
while at the same time enable your internal developers to build out the web
site with the same API calls.  This is a similar approach that Amazon took when
they decided to open up all of their computing via their EC2 infrastructure.

On the front end all of my websites use a CSS Framework.  Currently, Bootstrap
from Twitter is the rage and I am happy using that for my most recent projects.

On the back end I use MongoDb and Redis.  To me, Redis is one of the most
interesting platforms in the history of computer science.  It is the first time
that a robust framework can be used to serve data structures to multiple
processors at the same time.

I use Redis mainly to build search indexes.  One of the things I spend a lot of
time doing is reading data feeds or REST Api’s from the Internet and then building
indexes based on the type of data I retrieved.

I have a website that allows a user to define what keywords are in the index.  
Then, the user can search across that space by clicking on a word cloud of
indexed terms.

The program is generic enough that the data model across all of the different
feeds is the same.  So the JSON or RSS feed is transformed into a common data
structure via a set of custom callback functions.  Since this code is open source,
the developer can define those callback functions to put the data into a standard form.

Because this data is a common JSON format it can be visualized via D3.  
The word cloud itself is written in D3 by Jason Davies.

All of my projects run on Amazon EC2 which I have been using since 2008.  
I love Amazon for web site delivery and data delivery.  Besides Rackspace, it is
clearly the leader in the field.

I look forward to a conversation with you to further discuss synergies between
our mutual interests.
