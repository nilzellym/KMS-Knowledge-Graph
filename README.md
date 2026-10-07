# KMS Knowledge Graph Project

This project was created for the Knowledge Management Systems assignment.

The goal was to explore the provided dataset, create a knowledge graph schema, import the data into Neo4j AuraDB, and run Cypher queries to analyze the graph.

## Dataset

Source:
https://github.com/ArithaRTU/KMS_Dataset

## Knowledge Graph

The graph contains the following main node types:

- StudyProgram
- Course
- Topic
- LearningOutcome
- StudyField

The main relationships are:

- HAS_COURSE
- HAS_STUDY_FIELD
- HAS_TOPIC
- HAS_LEARNING_OUTCOME

## Main Findings

- Digital Humanities has 50 courses.
- Business Informatics has 29 courses.
- Digital Humanities has an average of 4.56 credits per course.
- Business Informatics has an average of 6.31 credits per course.
- The graph contains 640 HAS_TOPIC relationships.
- The graph contains 366 HAS_LEARNING_OUTCOME relationships.

## Files

This repository includes:

- PowerPoint presentation
- Report
- Screenshots from Neo4j AuraDB
- Cypher query results

## Conclusion

This was my first experience using Neo4j and working with knowledge graphs. The assignment helped me understand how connected data can be modeled using nodes and relationships, and how Cypher queries can be used to explore and compare information in the graph.# KMS-Knowledge-Graph
Knowledge graph project using Neo4j AuraDB and the RTU KMS dataset
