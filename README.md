# PaperSum - A Tool to Summarize Quant Strategy Research Papers

## 1. Project Name
PaperSum - A Tool to Summarize Quant Strategy Research Papers

## 2. Domain
+ Quantitative Trading Strategy (Alpha) Research
+ Prompt Engineer
+ Software Development
+ Academic Research


## 3. Served Stakeholder
Global finalist competing in the International Quant Championship (IQC) 2024 Global Final in Singapore - by WorldQuant  
Teammate:
+ Chau Thuan Phat - Main Engineer (https://www.linkedin.com/in/chau-thuan-phat-b60402154/)
+ Nguyen Hoang An - Researcher (https://www.linkedin.com/in/nguyenhoangan84/)
+ Vo Minh Hieu - Engineer (https://www.linkedin.com/in/hieuvo2402/)
+ Gia Nhi Nguyen - Strategist, Admin, Supporter (https://www.linkedin.com/in/gia-nhi-nguyen-1733a8146/)
  
## 4. Timeline
Project start to end: September 2024

## 5. Scope of Work
This tool rapidly analyzes hundreds of quantitative strategy research papers, providing comprehensive insights into specific quant strategy domains. It leverages **OpenAI API** and **LangChain** to automate document processing and summarization, helping users quickly extract key findings, trading strategies, and performance metrics, among other details.

## 6. Process and Approach
Input: Hundreds of trading paper files (PDF, DOC, CSV, etc.).  
Output: Structured summaries of each paper in CSV files, serving meta-analysis of specific research domains and quantitative strategy development.  
Process and Features:  
- AI Summarization: Uses **OpenAI API** (e.g., GPT-4o-mini) to explore and structurally summarize hundreds of input research paper files.
- LangChain Integration: Processes various document types (PDFs, text files) and structures outputs for analysis.
- Parallel Processing: Handles multiple documents concurrently for scalability.
- Structured Output: Exports results to CSV files for easy comparison and review.
- Automated Cleanup: Removes processed files after analysis.

## 7. Outcome
See file `Output_PaperSum.xlsx`, which summarizes 150 papers surrounding three quant market-neutral strategies related to Options, News, and Fundamentals, respectively. This serves as a background for the three real best Alphas submitted to the competition in the Global Final round.

## 8. My Role
- Project owner and direct user  
- Provides vision, defines features, and monitors the project development process.

## 9. Lessons Learned
- Leverage **OpenAI API** to create AI agents to enhance day-to-day task productivity.
- Enhance LLM (**OpenAI GPT-4o-mini**) output reliability and integrity using RAG (vectorized input string) and Prompt Engineering (systematic instruction and constraint).
- Use **LangChain** and RAG to process various input files in different formats at once and ensure scalability.

## Prerequisites
- Python 3.x
- OpenAI API key
- Required libraries (LangChain, OpenAI, etc.)
