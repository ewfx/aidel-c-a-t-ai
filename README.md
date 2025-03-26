# 🚀 RiskOPedia: AI-Driven Financial Risk Intelligence

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
We are Team CAT AI, and our topic focuses on “AI-Driven Entity Intelligence Risk Analysis.”
Our team comprises myself Adil, Dhwanil, Kushal, Rashmi Deshmukh, Soumyajit. Through this solution, we aim to bring cutting-edge AI techniques into the world of financial transaction risk management — transforming how entities and transactions are evaluated for potential frauds.

## 🎥 Demo
📹 [Video Demo](https://drive.google.com/file/d/1-2ycaHQdqZCqvuWodMJsAMptqpvjPhNs/view?usp=sharing) (if applicable)  
🖼️ Screenshots: 

![UI Demo](https://github.com/ewfx/aidel-c-a-t-ai/blob/main/artifacts/demo/UI_1.jpg)

## 💡 Inspiration
Financial fraud, money laundering, and illicit transactions are growing challenges in the financial sector. Traditional risk assessment methods rely heavily on manual reviews, making them inefficient and prone to errors. Our solution leverages AI-driven automation to:
- Detect hidden risks in financial transactions
- Identify suspicious entities using enriched public data
- Provide transparent, explainable risk assessments

Our solution is designed to detect potential financial risks in transaction data by analyzing sender and receiver details, locations, and other contextual clues.

## ⚙️ What It Does
The risk assessment process is structured into three key phases:

1️⃣ **Named Entity Recognition (NER)**

Extracts meaningful entities such as:
- Organizations (Companies, Nonprofits, Shell Companies, Banks)
- Individuals (Beneficiaries, Executives, Politically Exposed Persons)
- Locations (Addresses, Countries, Bank Branches)
- Financial Institutions (Banks, Intermediary Firms, Payment Processors)
Utilizes advanced Natural Language Processing (NLP) models to extract entity details from raw transaction data.

2️⃣ **Data Enrichment**

Augments extracted entities with external sources for additional context:
- Wikipedia – General entity background and public perception
- Regulatory Watchlists – Sanctioned or high-risk entities (OFAC, UN, FATF, Interpol, etc.)
- Financial Crime Databases – Past fraudulent activity (World-Check, LexisNexis, Dow Jones Risk & Compliance)
- News & Public Reports – Adverse media mentions

3️⃣ **AI-Powered Risk Scoring**

Computes a risk score based on:
- Entity reputation, past involvement in fraud, and watchlist status
- Transaction details (Sender/Receiver countries, intermediaries, flagged risks)
- AI-driven anomaly detection and contextual insights

Utilizes Generative AI to provide a transparent justification for each risk score.

## 🛠️ How We Built It

- **Backend**: Built with Django to handle transaction processing and risk scoring.
- **Frontend**: Implemented using HTML Embedded View Model (HEVM) for a seamless user interface.
- **Data** **Enrichment**: Integrated with Wikipedia API, News API, and the OFAC Sanction List to gather additional context for named entities (organizations, locations, and individuals).
- **AI-Powered Risk Scoring**: Leveraged the Together API to call the Llama Gen AI Model for generating detailed risk assessments and explanations.

![Architechture Diagram](https://github.com/ewfx/aidel-c-a-t-ai/blob/main/artifacts/arch/Architecture%20Diagram.png)

## 🚧 Challenges We Faced
- Processing of unstructured data
- Finding non-outdated Data Enrichment Sources

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/ewfx/aidel-c-a-t-ai.git
   ```
2. Install dependencies  
   ```sh
   pip install -r requirements.txt
   ```
3. Run the project  
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: HTML CSS JS with View Model (MVC)
- 🔹 Backend: Django
- 🔹 API: Wikipedia , News API , OFAC Sanction List
- 🔹 Other: Together API , Llama Model (meta-llama/Llama-3-8b-chat-hf) 

## 👥 Team
- **Soumyajit Rudra Sarma** - [GitHub](https://github.com/SOUMYAJITRUDRASARMA) | [LinkedIn](https://www.linkedin.com/in/soumyajit-rudra-sarma-150672237)
- **Adil A** - [GitHub](#) | [LinkedIn](#)
- **Kushal Das** - [GitHub](https://github.com/das-kushal) | [LinkedIn](https://www.linkedin.com/in/kushal-das-3936b3211/)
- **Rashmi Deshmuk** - [GitHub](#) | [LinkedIn](#)
- **Dhwanil M Shah** - [GitHub](https://github.com/dhwanilms) | [LinkedIn](https://www.linkedin.com/in/dhwanilms/)
