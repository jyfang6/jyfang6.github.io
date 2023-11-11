---
title: Enhancing Conversational Recommendation Systems with Representation Fusion
authors:
- Yingxu Wang
- Xiaoru Chen
- Jinyuan Fang
- Zaiqiao Meng
- Shangsong Liang
date: '2023-02-01'
publishDate: '2023-11-11T21:38:10.868404Z'
publication_types:
- article-journal
publication: '*ACM Transactions on the Web*'
doi: 10.1145/3577034
abstract: 'Conversational Recommendation Systems (CRSs) aim to improve recommendation
  performance by utilizing information from a conversation session. A CRS first constructs
  questions and then asks users for their feedback in each conversation session to
  refine better recommendation lists to users. The key design of CRS is to construct
  proper questions and obtain users’ feedback in response to these questions so as
  to effectively capture user preferences. Many CRS works have been proposed; however,
  they suffer from defects when constructing questions for users to answer: (1) employing
  a dialogue policy agent for constructing questions is one of the most common choices
  in CRS, but it needs to be trained with a huge corpus, and (2) it is not appropriate
  that constructing questions from a single policy (e.g., a CRS only selects attributes
  that the user has interacted with) for all users with different preferences. To
  address these defects, we propose a novel CRS model, namely a Representation Fusion–based
  Conversational Recommendation model, where the whole conversation session is divided
  into two subsessions (i.e., Local Question Search subsession and Global Question
  Search subsession) and two different question search methods are proposed to construct
  questions in the corresponding subsessions without employing policy agents. In particular,
  in the Local Question Search subsession we adopt a novel graph mining method to
  find questions, where the paths in the graph between users and attributes can eliminate
  irrelevant attributes; in the Global Question Search subsession we propose to initialize
  user preference on items with the user and all item historical rating records and
  construct questions based on user’s preference. Then, we update the embeddings independently
  over the two subsessions according to user’s feedback and fuse the final embeddings
  from the two subsessions for the recommendation. Experiments on three real-world
  recommendation datasets demonstrate that our proposed method outperforms five state-of-the-art
  baselines.'
tags:
- Conversational Recommendation Systems
- interactive recommendation
- representation learning
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3577034
---
