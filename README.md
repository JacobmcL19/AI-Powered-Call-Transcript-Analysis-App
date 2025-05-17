# AI-Powered-Call-Transcript-Analysis-App

This project is a hands-on AI application built using Snowflake, Streamlit, and Python to analyze and summarize customer support call transcripts. It showcases how to use Snowflake’s Cortex LLM functions for natural language processing (NLP) tasks on unstructured data.

## Features

- Summarize Call Transcripts using Snowflake Cortex `complete()` function.
-  Experiment with LLMs like Mistral 7B and LLaMA 3.2 by simply changing one line of code.
-  Streamlit UI for real-time input and summarization.
-  AWS S3 Integration to load raw CSV data into Snowflake tables.
-  Structured JSON Output for programmatic use: product name, defect, and summary.

---

##  Architecture Overview

- Data Source: AWS S3 bucket (CSV format call transcripts)
- Storage & Processing: Snowflake DB, schema, Snowpark
- LLM Inference: Cortex `complete()` function using Mistral/LLaMA models
- Frontend: Streamlit for user interaction and visualization

---

## Technologies Used

- Snowflake (Snowflake Notebooks, Snowpark, Cortex LLM)
- Python (pandas, Streamlit, snowflake-ml-python)
-Streamlit (app interface)
-LLMs: Mistral 7B, LLaMA 3.2 (via Snowflake Cortex)
-  AWS S3 (external stage for transcript CSVs)
