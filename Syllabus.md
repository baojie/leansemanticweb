# Lean Semantic Web Syllabus

[Work in progress]

Also see [Bibliography](/Bibliography.md/)

## Preamble
* Goal 
* TBD

## Section 1 Data Representation

* What is data and structure?
* Value of unstructured data
* Value of structured data
* Cost of data modeling
* The art of readable knowledge
* Naming resources
* Locating resources
* Relating resources
* Syntax: XML, JSON, YAML, RDF, Python etc.
* Implementation: some Python (RDFLib...)

## Section 2 Databases

* Cost of modeling and indexing semantics in database
* Use relational DB for semantic modeling
* Use key-value store to represent semantic relations: Redis etc.
* Document database: MongoDB, Elastic Search etc
* Graph database: TinkerPop stack, Neo4j, OrientDB
* Graph batch processing: Pregel, Hama, GraphChi etc
* Querying triples (with RDB, document db, graph db, or dedicated triple store)
* Implementation: some Python

## Section 3 Search and Findability

* Database vs search engine
* Cost of inverted index
* Extend inverted index to model semantic relations
* Understanding user queries: from keywords to sentences
* Faceted search: Elastic Search and Solr
* Graph search
* Implementation: some Python (ESClient...)

## Section 4 Data Exchange and Integration

* Portablility
* Protocol Buffers and Thrift
* Email and MIME
* JSON-RPC
* XMPP and Google Wave Protocol
* REST API design
* Some most important data APIs
* Implementation: some Python (JSON...)

## Section 5 Inference

* Cost of reasoner and index (IR, DB, KB)
* Just-in-time knowledge
* Practical rule modeling
* Inference as graph operations
* Inference using databases
* Inference using functional programming
* Implementation: some Python (Pydatalog, Fuxi)

## Section 6 Knowledge Extraction

* Cost of knowledge extraction
* Data cleaning
* Structure extraction
* Shallow parsing
* Entity extraction
* Relation extraction
* Implementation: some Python (NLTK...)

## Section 7 Visualization

* Cognitive background
* Exhibit and others
* D3 (and other JavaScript lib)
* NetworkX and  (and other Python lib)
* Implementation: some Python (mapplotlib...) and Javascript 

## Section 8 User Interaction

* It's about people, not machine
* Guided data exploration and discovery: why semantics is part of the solution
* Query formulating
* Faceted Browser
* Mobile search, Voice interface and personal assistants
* Implementation: some Python (ElasticSearch, Redis, RDF store based)

## Section 9: Big Data and Lean Data

* Measuring semantics in data
* Small is beautiful in knowledge
* The rule of knowledge growth on Web
* Small knowledge: in-memory graph models
* Big knowledge: knowledge bases on clusters
* Big data
* Datasets: Freebase, DBPedia, LOGD, Factual etc.
* Platforms: EC2, and some others
* Implementation: some Python (boto, starcluster)

## Section 10  Lean Application Development

* Build, measure, learn
* Lean Canvas
* MVP
* Build: mockup strategies, pretotyping, prototyping
* Measure: key metrics, but not vanity metrics
* Learn: why^5
* Semantic Wordpress/Drupal/Wiki, etc,
* Data-oriented Programming
* Implementation: some Python (mwclient) and some wiki

## Appendix
* Table of Python tools
* TBD
