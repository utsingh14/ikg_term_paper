# Climate Change Knowledge Graph & Semantic Retrieval

This repository contains the term paper project for the Department of Computer Science Engineering at The LNM Institute of Information Technology (LNMIIT). The project, "Querying Climate Knowledge," focuses on addressing the challenges of unstructured climate data by applying Semantic Web technologies to build a Knowledge Graph (KG) and enable semantic retrieval.

## Project Aim

The primary goal of this project is to move beyond simple keyword-based search of climate information. We apply knowledge management methods to a large corpus of unstructured text (from Reddit) to:

1.  **Extract** key concepts, entities, and terms related to climate change.
2.  **Identify** the semantic relationships and triples connecting these concepts.
3.  **Construct** a Knowledge Graph (KG) to serve as a structured representation of the domain.
4.  **Enable** semantic querying and retrieval to facilitate structured analysis and discovery.

![Project concept word clouds](image_abe7c8.png)

## Team & Institution

* **Team 17:**
    * Utkarsh Singh (22UCC111)
    * Shubham Mittal (22UCS206)
    * Nishant Jindal (22UCS141)
* **Institution:** The LNM Institute of Information Technology, Jaipur
* **Instructor:** Dr. Nirmal Kumar Sivaraman
* **Date:** December 2025

## Methodology

The project's workflow is based on a structured analysis of state-of-the-art knowledge management techniques and a practical implementation pipeline:

1.  **Literature Survey:** A comprehensive review of existing methods for knowledge extraction, KG construction, and semantic retrieval in scientific domains.
2.  **Data Corpus:** The `reddit_climate_data.csv` dataset was used as the primary source of unstructured text.
3.  **Concept Extraction:** An n-gram analysis (unigrams, bigrams, trigrams) was performed to identify the most frequent and significant concepts within the corpus.
4.  **Relation Extraction:** Methods were applied to extract relational triples (subject, predicate, object) from the text, forming the connections within the knowledge graph.
5.  **Analysis & Visualization:** The extracted concepts were visualized as word clouds to provide an intuitive overview of the dataset's focus.

## Repository Structure

This repository contains the final report, all extracted data, and visualizations generated during the project.

* [`term_paper_report.pdf`](./term_paper_report.pdf): The complete final report detailing the project's background, literature survey, methodology, results, and conclusions.
* `/data/`: (Recommended location for this file)
    * `reddit_climate_data.csv`: The original, raw dataset used for analysis.
* `/results/visualizations/`:
    * `image_abe7c8.png`: A composite image containing the word clouds for unigrams, bigrams, and trigrams (as referenced in Appendix A of the report).
* `/results/extractions/`: (As referenced in Appendix B)
    * `reddit_unigrams_all.csv`: The complete list of extracted unigrams and their frequencies.
    * `reddit_bigrams_all.csv`: The complete list of extracted bigrams and their frequencies.
    * `reddit_trigrams_all.csv`: The complete list of extracted trigrams and their frequencies.
    * *(Other output files, such as extracted relational triples, would also be placed here)*.

## How to Use This Repository

1.  **Read the Report:** For a full understanding of the project's scope, methodology, and findings, please start with [`term_paper_report.pdf`](./term_paper_report.pdf).
2.  **Explore the Results:** The `.csv` files in `/results/extractions/` contain the raw data output from our analysis. The visualizations in `/results/visualizations/` provide a high-level summary of the concept extraction.
