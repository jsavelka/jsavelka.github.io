---
title: "Legal Information Retrieval for Understanding Statutory Terms"
collection: publications
category: manuscripts
permalink: /publication/2021-07-01-statutory-interpretation
excerpt: "We propose a novel task of discovering sentences for argumentation about the meaning of statutory terms."
date: 2021-07-01
venue: 'Artificial Intelligence and Law'
slidesurl: # not available
paperurl: 'https://link.springer.com/article/10.1007/s10506-021-09293-5'
citation: 'Savelka, Jaromir, and Kevin D. Ashley. "Legal information retrieval for understanding statutory terms." <i>Artificial Intelligence and Law</i> 30, no. 2 (2022): 245-289.'
---

In this work we study, design, and evaluate computational methods to support interpretation of statutory terms. We propose a novel task of discovering sentences for argumentation about the meaning of statutory terms. The task models the analysis of past treatment of statutory terms, an exercise lawyers routinely perform using a combination of manual and computational approaches. We treat the discovery of sentences as a special case of ad hoc document retrieval. The specifics include retrieval of short texts (sentences), specialized document types (legal case texts), and, above all, the unique definition of document relevance provided in detailed annotation guidelines. To support our experiments we assembled a data set comprising 42 queries (26,959 sentences) which we plan to release to the public in the near future in order to support further research. Most importantly, we investigate the feasibility of developing a system that responds to a query with a list of sentences that mention the term in a way that is useful for understanding and elaborating its meaning. This is accomplished by a systematic assessment of different features that model the sentences’ usefulness for interpretation. We combine features into a compound measure that accounts for multiple aspects. The definition of the task, the assembly of the data set, and the detailed task analysis provide a solid foundation for employing a learning-to-rank approach.