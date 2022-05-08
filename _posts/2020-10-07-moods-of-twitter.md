---
layout: post
title: "Cloud computing: Moods of Twitter"
date: 2020-10-7
---

One of my more significant projects, Moods of Twitter was a project completed as part of my Cloud Computing subject. The purpose of the application is to handle a filtered stream of real-time tweets to analyse topics contained, and the association between those topics. A user may input and remove search terms into the application to filter the Twitter stream. Every tweet is analysed using named entity recognition to extract relevant topics. The topics are then linked together with the sentiment score of the tweet. The data generated is then displayed in a network diagram of topics with positive connections linked in green and negative in red.

The project was a steep learning curve for me. Web development has always been something I struggled with. I learnt a lot about cloud architecture through the project: including utilising different APIs, load balancing, containerisation and caching. To get an idea of how the architecture of the program interacts, have a look at this diagram:

<div class="img"><img src="/files/architecture.png" alt="Architecture Diagram"></div>
