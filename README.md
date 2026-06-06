# Talk to Government Data

A Natural Language Analytics System for Indian Agricultural Data.

## Project Overview

This project enables users to ask natural language questions about Indian agricultural production data and receive answers generated through deterministic Pandas operations.

The system uses Google Gemini for intent extraction and converts user questions into structured JSON queries that are executed on the dataset.

## Features

- Natural language query interface
- Gemini-powered intent extraction
- Structured JSON query generation
- Deterministic Pandas-based analytics
- Provenance tracking
- Automated evaluation framework
- Manual verification workflow
- Out-of-scope query detection

## Technology Stack

- Python
- Pandas
- Google Gemini API
- Gradio
- Google Colab

## Dataset

District-wise Crop Production Statistics Dataset

Columns:
- State_Name
- District_Name
- Crop_Year
- Season
- Crop
- Area
- Production

## Example Queries

- Which state produced the most rice in 2015?
- Show wheat production trend from 2000 to 2020.
- What are the top 5 states by sugarcane production?
- What is the total cotton production in Maharashtra?
- Which district in Punjab has the highest production area?

## Evaluation

The project includes:
- Automated evaluation
- Intent validation
- Provenance tracking
- Manual answer verification

## Author

Suraj Patil

Newton School of Technology (NST)
