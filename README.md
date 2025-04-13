# Quantitative Trading Strategy Research Summarizer

## Overview

This tool rapidly analyzes hundreds of quantitative trading strategy research papers, providing comprehensive insights into specific quant strategy domains. It leverages **OpenAI API** and **LangChain** to automate document processing and summarization, helping users quickly extract key findings, trading strategies, and performance metrics.

## Purpose

Discover and understand trends in quant trading research by summarizing papers efficiently, saving time while delivering actionable strategies and big-picture domain knowledge.

## Key Features

- **AI Summarization**: Uses **OpenAI API** (GPT-4o-mini) for to explore and structurely summarize hundreds of input research papers file.
- **LangChain Integration**: Processes various document types (PDFs, text files) and structures outputs for analysis.
- **Parallel Processing**: Handles multiple documents concurrently for scalability.
- **Structured Output**: Exports results to CSV files for easy comparison and review.
- **Automated Cleanup**: Removes processed files after analysis.

## Getting Started

1. Clone this repo and navigate to the `app` directory.
2. Place input research papers files in the `docs` folder.
3. Set your OpenAI API key in the code or environment.
4. Run the script: `python main.py`.

## Output

Find timestamped CSV files in the `data` directory, containing detailed and super-summarized insights.
> See example output file in file Output_PaperSum.xlsx

## Prerequisites

- Python 3.x
- OpenAI API key
- Required libraries (LangChain, OpenAI, etc.)
