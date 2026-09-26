# Awesome-Entity-Resolution-Platform

Top Entity Resolution Platforms Ecosystem
Top Entity Resolution Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Entity Resolution, Record Linkage, Data Matching, Deduplication & Master Data Management
Last updated: September 2026

This repository tracks notable Enterprise Entity Resolution (ER) platforms and open-source projects for identifying, matching, linking, deduplicating, and continuously resolving records that represent the same real-world entities across disparate data sources.

Examples include Quantexa, Senzing, Tamr, Reltio, Ataccama ONE, DataWalk, Palantir Foundry, BigID, Precisely, Verato, Informatica, IBM Match 360, Semarchy, Zingg, Splink, Dedupe, and the Python Record Linkage Toolkit.

Open-source emphasis: The Open-Source section prioritizes projects that can be used to build entity-resolution pipelines from scratch, including dedicated ER engines, probabilistic record-linkage libraries, machine-learning frameworks, graph technologies, data-quality tooling, and supporting infrastructure.

Contributions welcome! Please add missing platforms, open-source projects, algorithms, libraries, and infrastructure components.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Quantexa
Enterprise decision-intelligence platform using entity resolution, network analytics, contextual data, and AI to create connected views of customers, businesses, transactions, and other entities.

Senzing
Real-time entity-resolution platform designed to identify and unify records representing the same person or organization across disparate datasets without requiring a universal identifier.

Tamr
Enterprise data mastering and data-quality platform using machine learning for entity resolution, data consolidation, normalization, and master-data creation.

Reltio
Cloud-native master data management and entity-resolution platform for creating unified customer, product, organization, and other entity profiles across enterprise systems.

Ataccama ONE
Enterprise data-management platform combining data quality, MDM, governance, cataloging, and entity-resolution capabilities.

DataWalk
Graph-based analytics platform for connecting, investigating, and resolving entities across heterogeneous datasets, with applications in fraud, AML, investigations, and intelligence.

Palantir Foundry
Enterprise data platform providing data integration, ontology, entity-centric modeling, analytics, and operational workflows that can support large-scale entity-resolution use cases.

BigID
Data discovery, privacy, security, and governance platform with data intelligence and identity/entity capabilities for discovering and connecting information across enterprise environments.

Precisely
Data-integrity platform providing data quality, enrichment, identity resolution, location intelligence, and master-data capabilities.

Verato
Cloud-native master data management and identity-resolution platform particularly focused on creating unified identities and longitudinal profiles.

Informatica
Enterprise data-management platform with Master Data Management, Customer 360, data quality, identity matching, and AI-powered data integration capabilities.

IBM Match 360
IBM master-data management capability for matching and consolidating records into trusted entity profiles and 360-degree views.

Semarchy xDM
Enterprise multidomain master-data-management platform supporting matching, merging, survivorship, governance, and unified entity records.

Profisee
Enterprise MDM platform providing data matching, mastering, governance, and entity consolidation across business domains.

Stibo Systems
Enterprise multidomain MDM platform supporting product, customer, supplier, and other entity domains with matching and data-quality capabilities.

Precisely EnterWorks
Product and master-data management technology supporting data consolidation, matching, enrichment, and governance.

CluedIn
Data-management and MDM platform focused on data integration, entity resolution, knowledge graphs, data quality, and unified business entities.

Insycle
CRM data-management platform providing deduplication, record merging, normalization, enrichment, and data-quality workflows.

RingLead
B2B data-quality and identity-resolution technology focused on deduplication, normalization, enrichment, and CRM data management.

Openprise
Revenue-data automation and data-quality platform providing identity resolution, deduplication, normalization, enrichment, and data orchestration.

Dun & Bradstreet
Commercial-data platform providing business identity resolution, company hierarchies, entity matching, and enrichment through its business-data assets.

Melissa
Data-quality and identity-management platform providing address verification, name matching, deduplication, customer matching, and identity-resolution capabilities.

Experian
Data and analytics platform providing identity, consumer, business, fraud, and data-quality capabilities that can support entity matching and identity resolution.

LexisNexis Risk Solutions
Risk-data and identity technology provider offering entity intelligence, identity resolution, fraud detection, and relationship analytics.

AWS Entity Resolution
Managed cloud service for configuring matching workflows that identify and link related records across datasets using rule-based, ML-assisted, and provider-based approaches.

Google Cloud Entity Resolution
Cloud-based entity-resolution capabilities for matching and reconciling records across enterprise data sources.

Snowflake
Cloud data platform that can support entity-resolution workflows through Snowpark, SQL, ML, data sharing, and integrations with specialized matching technologies.

Databricks
Data and AI platform commonly used to implement large-scale entity-resolution pipelines using Spark, ML, lakehouse architecture, and data engineering workflows.

Open-Source GitHub Projects

Zingg
Open-source ML-based entity-resolution and master-data-management platform supporting entity resolution, deduplication, identity resolution, data integration, and unified entity views at scale. Zingg supports active-learning workflows and Spark-based processing.

Splink
Open-source Python package for probabilistic record linkage and entity resolution. It supports deduplication and linkage using Fellegi-Sunter-style probabilistic models and can operate with DuckDB and larger SQL/data-processing backends.

Dedupe
Python library for machine-learning-based fuzzy matching, record deduplication, record linkage, and entity resolution. It supports human-in-the-loop training and clustering of records into entities.

Python Record Linkage Toolkit
Modular Python toolkit providing indexing/blocking, record comparison, similarity functions, classifiers, and evaluation tools for record linkage and deduplication.

pyJedAI
Open-source Python library for constructing end-to-end entity-resolution workflows, including data matching, record linkage, entity resolution, and link discovery.

JedAI
Open-source Java toolkit for scalable data integration, entity resolution, record linkage, and link discovery across relational and RDF data.

RLTK
Open-source Record Linkage ToolKit providing a scalable pipeline for blocking, profiling, feature computation, and machine-learning-based record matching.

Duke
Java-based deduplication and entity-resolution engine built around Lucene, supporting deduplication and record linkage across heterogeneous data sources.

fastLink
R package implementing fast probabilistic record linkage using the Fellegi-Sunter framework, including support for missing data and EM-based parameter estimation.

anonlink
Open-source privacy-preserving record-linkage technology designed to link records using cryptographic linkage keys without directly exposing identifying information.

FEBRL
Freely Extensible Biomedical Record Linkage project providing algorithms and tooling for data cleaning, deduplication, probabilistic linkage, and record linkage.

OpenRecLink
Open-source record-linkage ecosystem originating from epidemiological and public-health applications, particularly focused on probabilistic linkage.

ebLink
Statistical record-linkage research project implementing Bayesian/entity-resolution techniques for probabilistic matching.

Entity-Embed
Open-source approach to scalable record linkage using entity embeddings and approximate-nearest-neighbor search.

Splink DuckDB
DuckDB-backed entity-resolution workflows enabling local analytical linkage while retaining the SQL-oriented Splink modeling approach.

Additional Strong Open-Source Options

Apache Spark
Distributed data-processing engine that provides the computational foundation for large-scale custom entity-resolution pipelines.

Apache Flink
Distributed stream-processing framework useful for building real-time or continuously updated entity-resolution pipelines.

DuckDB
Embedded analytical database particularly useful for local and analytical entity-resolution workloads and used as a backend by Splink.

Apache Beam
Unified batch and stream-processing framework suitable for building portable large-scale record-linkage and entity-resolution pipelines.

Pandas
Core Python data-manipulation framework frequently used as the data-processing layer around record-linkage and deduplication libraries.

Polars
High-performance DataFrame engine useful for preprocessing, normalization, blocking, and large-scale entity-matching pipelines.

scikit-learn
Machine-learning framework providing classification, clustering, preprocessing, and model-building components for custom entity-resolution systems.

PyTorch
Deep-learning framework that can be used to build neural entity-matching, representation-learning, and entity-embedding models.

TensorFlow
Machine-learning framework suitable for developing learned similarity functions, embeddings, and custom entity-resolution models.

Faiss
High-performance similarity-search library useful for approximate-nearest-neighbor candidate generation and entity matching using vector representations.

HNSWlib
Efficient approximate-nearest-neighbor library useful for vector-based entity matching and candidate generation.

Apache Lucene
Search engine library providing indexing, text search, fuzzy matching, and similarity capabilities useful for entity-resolution systems.

OpenSearch
Open-source search and analytics engine useful for candidate generation, fuzzy search, entity discovery, and investigation workflows.

Elasticsearch
Search and analytics engine providing text matching, fuzzy queries, indexing, and vector-search capabilities that can serve as an entity-resolution candidate-generation layer.

Neo4j Community
Graph database useful for representing entities and relationships after resolution and for performing network-based entity investigations.

JanusGraph
Open-source distributed graph database suitable for large-scale entity and relationship graphs.

Apache AGE
Graph database extension for PostgreSQL that can be used to represent and query entity relationships within relational data infrastructure.

ArangoDB
Multi-model database supporting graph, document, and key-value workloads useful for entity-centric applications.

OpenRefine
Open-source data-cleaning and transformation platform with clustering and reconciliation capabilities useful for preparing data before entity resolution.

Great Expectations
Open-source data-quality framework useful for validating source data before matching and monitoring entity-resolution pipelines.

dbt Core
Open-source analytics-engineering framework useful for transforming, standardizing, testing, and preparing datasets before entity matching.

Apache Airflow
Workflow orchestration platform useful for scheduling recurring entity-resolution, deduplication, enrichment, and master-data pipelines.

MLflow
Open-source ML lifecycle platform useful for tracking, versioning, evaluating, and deploying custom entity-resolution models.

Kubeflow
Kubernetes-native ML platform useful for operationalizing large-scale entity-resolution model training and inference.

OpenMetadata
Open-source metadata platform useful for cataloging the datasets, schemas, owners, and lineage involved in entity-resolution programs.

DataHub
Open-source metadata and data-catalog platform useful for governing the data assets that feed enterprise entity-resolution systems.

Apache Atlas
Open-source data-governance and metadata framework useful for tracking lineage and governance around master-data and entity-resolution pipelines.

Keycloak
Open-source identity and access-management platform useful when building secure multi-user entity-resolution applications and data services.

Open Policy Agent
Open-source policy engine useful for enforcing authorization and governance rules around entity data and matching workflows.

Framework for building a self-hosted Enterprise Entity Resolution platform: Combine Zingg / Splink / Dedupe / pyJedAI as the core matching layer, DuckDB / Spark / Flink / Polars for computation, Faiss / HNSWlib / Lucene / OpenSearch for candidate generation and similarity search, Neo4j / JanusGraph / Apache AGE / ArangoDB for entity and relationship graphs, OpenRefine / Great Expectations / dbt Core for data preparation and quality, and MLflow / Kubeflow / PyTorch / scikit-learn for model development and operations. Add Airflow for orchestration and Keycloak / Open Policy Agent for security and policy control. This combination can provide the core building blocks for a self-hosted Customer 360, Supplier 360, KYC/AML, fraud, product mastering, or general-purpose entity-resolution platform.

How to Contribute

Fork this repository.

Add the platform or open-source project to the appropriate section.

Prefer official product websites for SaaS platforms.

Prefer official GitHub repositories for open-source projects.

Keep descriptions concise and technically accurate.

Prioritize actively maintained projects.

Clearly distinguish complete entity-resolution platforms from supporting libraries and infrastructure.

Submit a pull request with your changes.

Disclaimer

This is a curated ecosystem rather than a ranking or endorsement.

SaaS platforms differ significantly in matching methodology, deployment model, supported entity types, scalability, governance, pricing, and integration capabilities.

Some projects in the Open-Source section are complete entity-resolution platforms, while others are record-linkage libraries, ML frameworks, graph databases, search engines, or data-engineering components that can be combined to build an ER platform.

Open-source availability, licensing, features, and project activity can change over time.

Always verify licensing, security, maintenance status, scalability, and deployment requirements before adopting a project.

Made for data engineers, data scientists, MDM teams, security teams, fraud analysts, AI engineers & organizations building the next generation of Entity Resolution platforms.
Let's make entity resolution more open, scalable, explainable & self-hostable.

Separate core tools from supporting infrastructure
Remove duplicate Splink entry
