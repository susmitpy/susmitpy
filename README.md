# Susmit Vengurlekar

Backend, data and cloud engineer, 5+ years. I build data platforms, event-driven services and agentic engineering workflows. Founder of ForQuiz.

[LinkedIn](https://www.linkedin.com/in/susmit-vengurlekar/) | [Portfolio](https://susmitpy.github.io) | [Medium](https://susmitpy.medium.com) | [Email](mailto:susmit.dev@outlook.com)

## About

At SkillRev (Data Scientist & Solutions Architect) I built an autonomous agent pipeline for a US county tax system. Scheduled cloud runs let an LLM pick tickets, and each ticket goes through Claude Code sub-agents that plan, implement, browser-test with Playwright and review before a pull request. Low-risk tickets auto-merge and the rest get human review.

I also founded [ForQuiz](https://forquiz.fusebytes.in), a commercial live-quiz and topic-level analytics platform I built solo. It has served 700+ players, up to 366 in one room, at meetups and college classrooms in Mumbai.

Earlier roles: founding team at AIDAX (data platform and ETL for an automotive manufacturer), Xcellen (data science and GenAI) and Zeza Technologies, where I led a team of 4 developers and 3 interns and cut cloud costs by about 60% by re-architecting legacy systems on AWS.

## Selected projects

- **[ForQuiz](https://forquiz.fusebytes.in)** (closed source): live-quiz platform with answer timing measured on the participant's own phone and one analytics read model for live and self-paced sessions. Next.js, Node, WebSockets, Firebase.
- **[brow](https://github.com/susmitpy/brow)**: browser-testing kit for Claude Code on Playwright MCP: an agent brief, two skills and a CLI that turns test recordings into one chaptered, voice-narrated evidence video. [Demo](https://youtu.be/-8JNMW7W0Es).
- **[Real-Time CTR Analytics](https://github.com/susmitpy/stream_analytics_adtech_ctr)**: 15-second interval join, 30-second campaign windows, exactly-once output. Go, Kafka, PyFlink. [Talk](https://youtu.be/FsCWEC8Ir8I).
- **[Multi-Engine Data Profiler](https://github.com/susmitpy/Data-Profiler)**: concurrent, adapter-based profiling of hundreds of tables across four engines, with checkpoint/resume. Python.
- **[Knowledge-Graph RAG](https://github.com/susmitpy/QnA-on-Neo4j-Knowledge-Graph)**: text-to-Cypher over graph and vector indexes to ground LLM answers. [Talk](https://youtu.be/JpysxH4Z5Fw).

## Tech

- **Languages:** Python, Go, TypeScript, SQL
- **AI and agentic:** Claude Code (sub-agents, skills, hooks), MCP, RAG, LangChain
- **Backend and web:** FastAPI, Django, Node.js, WebSockets, Playwright
- **Cloud and DevOps:** AWS (CDK, Lambda, Glue, ECS Fargate, S3), Terraform, Docker, GitHub Actions, Kong, OpenTelemetry
- **Data and streaming:** Kafka, Flink, Spark, Databricks, Iceberg
- **Databases:** PostgreSQL, Neo4j, MongoDB, DynamoDB

## Writing and talks

- Articles: [Data Engineering and ML Platform](https://medium.com/zeza-tech/data-engineering-and-ml-platform-part-1-platform-architecture-e5d869cae94f), [Building a Recommender System with Neo4j](https://medium.com/neo4j/building-a-recommender-system-using-neo4j-hands-on-part-1-e82bcd881906), [Apache Kafka in Short](https://blog.det.life/apache-kafka-in-short-fa56cc197114).
- Speaker at Global Azure Bootcamp, AWS User Group Mumbai, and Kafka, Kong and GraphDatabase meetups. Slides: [Apache Kafka in Short](https://susmitpy.github.io/talks/kafka), [Firestore Security Rules (DevFest Mumbai 2024)](https://susmitpy.github.io/talks/firestore_rules).
