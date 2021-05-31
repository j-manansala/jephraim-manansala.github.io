---
layout: post
title:  "Network Analysis of Philippine Supreme Court Decisions and Rulings"
categories: network_science
list_title: "Network Science"
date:   2021-05-30 
---
by: [Jephraim C. Manansala](https://www.linkedin.com/in/jephraim-manansala/) and [Daryll F. Tumambing](https://www.linkedin.com/in/daryll-tumambing/)

Asian Institute of Management

In the practice of law, legal research is one of the most painstakingly long processes that takes most of the time of the law practitioners. To properly formulate and strategize their existing cases, they must pinpoint the most relevant case and build their strategies from the weaknesses of the previous case decisions. However, there is currently no case retrieval system that can provide this need for Filipino law practitioners. We developed a search engine that uses Philippine Judicial Citation Network and Natural Language Processing (NLP) as its processor to address this. The network was built using the case decisions as to its nodes and the citation as its edges. Exploring the network, we have found that there are 33 communities formed using the Louvain method and each community represents various case themes - such as communities related to dangerous drugs, elections, and annulments. NLP techniques such as the Doc2Vec model were trained as the information retrieval tool for the search engine. By doing so, we developed a search engine tool that uses the combination of degree centrality from the network and cosine similarity of a search query to the Doc2Vec embeddings to yield the most relevant and influential cases in the corpus. This can be very useful to legal research as we can easily pinpoint the cases that set the legal precedence to the topics they are pursuing. 

![](assets/judicial.png "Communities in the Giant Component")

Keywords: Citation Network, Network Science, Natural Language Processing, Legal Research

<i>Full text article and source codes can be provided upon request. </i>