# Project Title: LLM-Powered Cold Email Generator for Job Applications

## Project Overview
This project focuses on building an AI assistant that generates personalized cold emails for job applications.  
Using **LLaMA-3.3-70B**, **LangChain**, and **ChromaDB**, it automates the process from scraping job postings to creating customized outreach emails, all within a **Streamlit** web interface.

---

## Key Features and Implementations

### 1. LLM Integration with Groq
- Used **Groq-hosted LLaMA-3.3-70B** to generate high-quality, context-aware email content.
- Managed interactions with the model using **LangChain’s ChatGroq** wrapper.

### 2. Job Posting Scraper
- Implemented a scraper using **LangChain’s WebBaseLoader** to fetch job descriptions from URLs.
- Enabled real-time extraction of job data from sites like **Amazon Jobs**.

### 3. Structured Data Extraction with Prompts
- Used **prompt engineering** to convert unstructured job text into structured **JSON** format.
- Extracted key fields such as **role**, **experience**, **skills**, and **description**.

### 4. Portfolio Matching with ChromaDB
- Stored user portfolio data in **ChromaDB** as document embeddings.
- Performed **semantic search** to find portfolio links most relevant to job-required skills.

### 5. Cold Email Generation with LLMs
- Generated personalized emails by **chaining prompts** with job and portfolio data.
- Ensured emails reflect a **professional tone** and are aligned with job requirements.

### 6. Streamlit UI for Easy Interaction
- Built a simple web app using **Streamlit** where users input a job URL and receive a cold email instantly.
- Designed for **non-technical users** to access AI capabilities seamlessly.

### 7. End-to-End Workflow Automation
- Combined scraping, data extraction, semantic search, and email generation into a single **automated pipeline**.
- Reduced the **manual workload** of job seekers while improving application quality.

### 8. Reusability and Extensibility
- Modular code design enables easy extension to support other use cases like **freelance outreach** or **recruiter messaging**.

---

## Conclusion
This project showcases the practical use of **large language models** for **job application automation**.  
It integrates multiple AI tools into a **streamlined workflow** that generates relevant, personalized emails with minimal user input.
