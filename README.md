
# Analysis of Streaming Services Data (EDA)

## Important – Start Here

**Dataset Source:** This dataset was obtained from **Kaggle**.

This project includes a **full presentation inside the project folder**, explaining the analysis
**slide by slide**, in **both English and Hebrew**.

The presentation provides:
- Full dataset overview
- Research questions and analytical approach
- Visual findings and interpretations
- Key insights and business conclusions

📌 **It is strongly recommended to start by reviewing the presentation first**, as it presents the
complete narrative of the project before diving into the notebook or code.

---

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset of global streaming services.
Each row in the dataset represents a streaming platform, enabling **benchmarking and comparison**
between services.

The analysis focuses on understanding:
- Market distribution
- Pricing strategies
- Subscriber scale
- Relationships between business metrics (correlations)
- Stability indicators such as churn

---

## Project Goals

- Validate data quality (missing values, duplicates, data types)
- Explore distributions and rankings across streaming platforms
- Identify correlations between key business variables
- Translate analytical findings into meaningful business insights

---

## Repository Contents

- **Presentation (English & Hebrew)** – full slide-by-slide explanation of the project (recommended starting point)
- `mini_data.ipynb` – Jupyter Notebook with the complete Python analysis
- `free_video_streaming_services.csv` – dataset used for the analysis
- `Analysis-of-Streaming-Services-Data.pdf` – full written report in English
- `3va8i4vzgdh82o4.pdf` – full written report in Hebrew

---

## Dataset & Features

Key variables analyzed include:
- Number of available countries
- Monthly price (USD)
- Annual price (USD)
- Number of subscribers
- Churn rate
- Additional platform-level business indicators

---

## Analysis Workflow

### 1. Data Validation & Cleaning
- Checked for missing values and duplicates
- Validated data types and schema
- Created derived fields to support analysis (e.g., average monthly price)

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis across platforms
- Ranking services by subscribers and availability
- Visual comparisons between pricing and scale

### 3. Correlation Analysis
Key relationships examined:
- Monthly price vs. number of subscribers
- Monthly price vs. annual price
- Subscribers vs. churn rate
- Content or innovation-related metrics vs. pricing

---

## Key Findings (Highlights)

- **India leads in subscriber concentration** among analyzed markets.
- **MX Player** is the largest platform by subscriber count.
- **Monthly price and subscriber count show no meaningful correlation**, indicating pricing alone does not drive scale.
- **Monthly and annual prices are strongly correlated**, as expected.
- **Subscriber count and churn rate show a negative relationship**, suggesting larger platforms are more stable.

---

## How to Run the Project

### Option 1 – Run the Notebook
1. Ensure the following files are in the same directory:
   - `mini_data.ipynb`
   - `free_video_streaming_services.csv`
2. Open the notebook in VS Code or Jupyter Notebook and run cells top to bottom.

### Option 2 – Create a Virtual Environment
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

pip install pandas matplotlib seaborn plotly
