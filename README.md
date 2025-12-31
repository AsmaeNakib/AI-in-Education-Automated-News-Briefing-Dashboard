This repository contains the final deliverables for a course project completed as part of the Artificial Intelligence in Business and Society course at Constructor University.
The project explores how AI-driven workflows can be used to monitor, summarize, and surface key developments related to artificial intelligence in education, while also critically reflecting on the ethical, technical, and societal implications of such systems.

The core output is an automated daily news briefing dashboard generated through an n8n workflow that collects AI-in-education news from Google News, processes and filters the data, and summarizes key trends using a large language model.


**Team Members:**

- Alua Aldaniyaz 
- Asmae Nakib
- Oleksii Terletskyi
  

**Project Overview**

The goal of this project was to design and evaluate an automated system that:
- Aggregates recent news articles about AI in education,
- Filters and deduplicates content,
- Generates structured summaries of key stories, trends, risks, and opportunities,
- Presents the results in a human-readable dashboard.

Beyond technical implementation, the project places strong emphasis on verification, validation, and ethical considerations, including data privacy, algorithmic bias, human oversight, and environmental sustainability.


**Repository Contents / Deliverables**

This repository includes the following deliverables:

1. Final Report - Report- Final.pdf
The written course report describing the project motivation, system design, workflow implementation, verification and validation process, results, and ethical analysis.

2. Dashboard Output - Dashboard.html
The generated HTML dashboard for one execution of the system, presenting AI-generated summaries, trends, and monitored sources in a structured visual format.

3. Automation Pipeline - PIPELINE.json
The exported n8n workflow file defining the full automation pipeline, including data collection, filtering, aggregation, AI summarization, and dashboard generation.

4. Sample Dataset - articles.csv
A CSV export of the articles collected during one daily run of the system.
This file is used in the report to support verification and validation of the data pipeline, including checks for freshness, relevance, and duplication.
