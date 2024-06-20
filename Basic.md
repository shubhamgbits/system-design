
# SYSTEM DESIGN - Overview

Decision making process is very significant part of the process

We need to rationalize every decision we make

It should look like that we have <u>considered both pros and cons of each option</u> and then decided upon something

- ## Availability & Consistency

What does it mean to have a highly available system

What is Weak, Eventual & Strong consistency

- ## Polling v/s Streaming

When you would use one over the other

What are the tradeoffs

- ## Messaging Patterns

Messaging queueing and PubSub

It defines a way of how different services communicate with each other

- ## Asynchronism

How asynchronous flows work and what are its benefits

- ## Load Balancing

Every large scale system will need some load balancers. 

You need to decide in which layers you are going to place them

And which distribution strategies you are going to use

We should be able to explain our decision on why did we choose this strategy and not the other

What are the trade offs you were willing to make


- ## Caching

We will need to form caching somewhere in the system (or at multiple places)

We need to think which layers will benefit from cache

- Will be place it on our clients?
- On our servers?
- in-memory?
- or Prefer dedicated caching service like Redis
- Eviction policy for each cache
- Will we benefit from CDN?
- What information will we store on it?

While deciding these things we can think out loud 

- ## Consistent Hashing

What it is and when it is used

- ## Databases

- SQL v/s NoSQL

We should know the difference between them and 
We should know the tradeoffs

Also we should know - 
- Sharding
- Indexing
- Replication

We should know what does these mean & when to use them


---
# Famous designs to learn from

1. Facebook News Feed
2. Google Drive
3. Google Search
4. What's App
5. Amazon
6. Netflix

