---
title: What are ETL and ELT?
feed: show
---
[[ETL]] and [[ELT]] (new) are two different approaches to data integration and transformation, with each acronym standing for a specific order of operations.

[[ETL]] stands for Extract, Transform, Load, and refers to a process where data is first extracted from the source systems, then transformed into the desired format, and finally loaded into the target system. In [[ETL]] , the data is first extracted from the source system, then transformed in a separate process or tool, and finally loaded into the target system.

[[ELT]] stands for Extract, Load, Transform, and refers to a process where data is first extracted from the source systems, then loaded into the target system, and finally transformed into the desired format. In [[ELT]], the data is first extracted from the source system and loaded into the target system in its raw format. The transformation process is then performed within the target system using tools such as SQL, Spark, or other processing engines.

The main difference between [[ETL]]  and [[ELT]] is the timing and location of data transformation. In [[ETL]] , the data is transformed before being loaded into the target system, which can be useful for filtering and cleaning the data before it is used for analysis. In [[ELT]], the data is loaded into the target system in its raw format, and the transformation process is performed within the target system, which can be useful for situations where the target system has powerful transformation capabilities.

There are benefits and drawbacks to both [[ETL]]  and [[ELT]] approaches, depending on the specific use case and the technologies being used. [[ETL]]  can be more suitable for situations where data needs to be cleaned, transformed, or enriched before it is loaded into the target system. [[ELT]] can be more suitable for situations where the target system has powerful processing capabilities and can handle large volumes of data.

In summary, [[ETL]]  and [[ELT]] are two different approaches to data integration and transformation. [[ETL]]  involves extracting, transforming, and loading data, while [[ELT]] involves extracting, loading, and then transforming data within the target system. The choice between [[ETL]]  and [[ELT]] depends on the specific use case, the technologies being used, and the processing requirements of the data.