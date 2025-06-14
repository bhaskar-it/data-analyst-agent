# Data Analyst Agent (Powered by LLaMA-4 Maverick)

This project is a backend-focused intelligent data analyst agent that leverages the `meta-llama/Llama-4-Maverick-17B-128E-Instruct-FP8` model via the Together API to analyze uploaded documents or datasets. It can extract insights, answer questions, and generate visualizations with minimal UI dependencies.

## Features

- Upload support for `.csv`, `.xlsx`, `.pdf`, `.txt`, `.docx`, `.png`, `.jpg`
- Intelligent data summarization and question-answering via LLaMA-4 Maverick
- Automatic statistics and data profiling (e.g., describe, dtypes)
- Visualization support: bar, line, scatter, histogram
- Lightweight optional UI using **Streamlit**

## Model Used

> **Model:** `meta-llama/Llama-4-Maverick-17B-128E-Instruct-FP8`  
> **Platform:** [Together.ai](https://www.together.ai/)

## Project Structure
├── data_analyst_agent.py # Core backend logic
├── app.py # Streamlit UI (optional)
├── sample_sales_data.csv # Test CSV file
├── SN_Mentoring.ipynb # Main notebook (Colab-compatible)
├── README.md # You're here!


## 🧪 How to Run (Colab)

1. Install dependencies:
```bash
!pip install streamlit pyngrok pandas matplotlib seaborn python-docx PyMuPDF openpyxl together


!git clone https://github.com/bhaskar-it/data-analyst-agent.git
%cd data-analyst-agent

together.api_key = "your_actual_key"


---

Let me know if you’d like a version with badges (e.g., Python version, Streamlit support) or a video/gif demo embedded.
