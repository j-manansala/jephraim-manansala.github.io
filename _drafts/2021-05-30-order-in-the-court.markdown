---
layout: post
title:  "Order in the Court! : Unsupervised Learning on Supreme Court Tax Cases in the Philippines for a Case Retrieval System"
date:   2021-05-30 20:24:55 +0800
---
by: Dorosan, Edeza, Gonzales, Licong, Manansala, Marquez
Asian Institute of Management

In the practice of law, legal research is one of the most painstakingly long process that takes most of the time of the law practitioners. To properly formulate and strategize their existing cases, they must be able to pinpoint the most relevant case and build their strategies from the weaknesses of the previous cases. However, there is currently no case retrieval system that can provide this need of the Filipino law practitioners. According to law practitioners, the current legal research in the Philippines is usually dependent on more general algorithms of search engines such as Google. While this somewhat aides research, a practitioner may still need to filter through search results which are primarily based on search engine optimization metrics other than actual relevance of results to the practice. Almost all the time, this does not lead to the relevant cases which can be frustrating for law practitioners given the number of documents they need to read.

With this in mind, we developed a case retrieval system specifically for tax case decisions of the Philippine Supreme Court. Unsupervised learning was also implemented to cluster the tax cases based on their term-document similarities. In the end, we were successful in clustering the tax-related Supreme Court cases into four clusters: VAT-related, Criminal Tax Evasion, Corporate Tax, and Tax Disputes clusters. These cluster results were used as ground truth to evaluate the performance of the case retrieval system that we built, resulting to an AUC-ROC score of 0.745.

Our initial success provides throught-provoking insights into further optimizing the stopword generator we initially used to process our bag-of-words data. Our methods of filtering out noise due to stopwords are still heavily dependent on a threshold based algorithm in determining corpus-specific stopwords. We recommend further research in this direction as well as extensive external validation by practitioners of clustering and case retrieval system resu

Keywords: Clustering, Legal Cases

<i>Full text article and source codes can be provided upon request. </i>