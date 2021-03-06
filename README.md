# Event-Detection-on-Microposts
This is the repository for data related to our submission to TKDE titled "Event Detection on Microposts: a Comparison of Four Approaches".

# Query Expansion Approaches (Section 4.1,4.2,4.3)

- We provide the expanded terms obtained using PSQ, TQE and Embedding approach in the appendix.

- We provide the relevance scores obtained using each method in the uploaded events_(psq|tqe|embed).json files. 

- Link to the model trained on tweets from 2014: https://drive.google.com/open?id=1akJ8pejV3RA__tOXyxpo9wQe92rYDhYy

# Section 4.4: Semantic Approach: Armatweet

Link to the data: https://drive.google.com/file/d/1HzyBJUowgTt7hJ6A-bcx1v3OrppJCCbi/view?usp=sharing. This folder contains the following information:

- The "events" directory contains the Excel files used to categorise
  the detected tweets into classes reported in the paper.

- The "dlog" directory contains the Datalog program for the RDFox
  system that was used to analyse the tweets. The semantic queries
  are encoded as rules in the program.

- The "facts" directory contains the RDF triples in the Turtle format
  that were extracted from raw Twitter data, the version of DBpedia
  (called BMpedia.ttl) used, and the version of WordNet.

- The "scripts" directory contains the RDFox scripts used to analyse
  the data.

# Test Datset

We also provide the link to our test dataset from first half of 2015. This dataset consists of tweet identifiers. Using Twitter public API, these tweet IDs can be rehydrated. https://drive.google.com/open?id=1QXd811QaUUinikYXQClzbY-mUUwxKLNz
