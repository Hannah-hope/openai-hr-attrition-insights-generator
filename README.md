# OpenAI HR Attrition Insights Generator

## Overview
This project is an AI-powered data analytics tool that uses the OpenAI API and Python to analyze an HR attrition dataset and generate clear, human-readable business insights.

It demonstrates how generative AI can transform structured data into actionable insights for decision-making.

---

## Objective
The goal of this project is to:
- Analyze employee attrition patterns
- Generate automated insights using AI
- Bridge the gap between raw data and business understanding

---

## Technology Stack
- Python
- OpenAI API
- pandas
- openpyxl
- Google Colab

---

## Dataset
The dataset includes employee-level HR data such as:
- Attrition (Yes/No)
- Department
- Job Role
- Monthly Income
- Age

---

## Features
- Data cleaning and preprocessing
- Handling duplicate categorical values (e.g., department naming inconsistencies)
- Creation of derived variables:
  - Attrition_Binary
  - AgeGroup
- Attrition analysis by:
  - Department
  - Job Role
  - Age Group
  - Income level
- AI-powered insights generation
- Export of insights to text file

---

## How It Works
1. Load HR dataset
2. Clean and standardize data
3. Generate summary statistics
4. Send structured summary to OpenAI API
5. Receive:
   - Key insights
   - Root causes
   - Recommendations
   - Business risks

---

## How to Run

### Step 1: Install dependencies
```bash
pip install openai pandas openpyxl
