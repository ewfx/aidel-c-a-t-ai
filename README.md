# 🚀 Project Name

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
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots: 

![UI Demo](https://github.com/ewfx/aidel-c-a-t-ai/blob/main/artifacts/demo/UI_1.jpg)

## 💡 Inspiration
**AI-Driven Entity intelligence risk analysis:** Our solution is designed to detect potential financial risks in transaction data by analyzing sender and receiver details, locations, and other contextual clues.

## ⚙️ What It Does
We followed a three-phase approach:
Phase 1 is Named Entity Recognition, or NER — where we extract meaningful entities such as organization names, locations, individuals, and financial institutions from raw transaction data.
Phase 2 is Data Enrichment — where we bring in additional insights from external sources like Wikipedia and other public databases to add more context to each identified entity.
And finally, Phase 3 is Scoring using Generative AI — where we compute a risk score for each transaction using the enriched information, with detailed justifications.
This method ensures a transparent, explainable, and AI-powered analysis of potential risks.

## 🛠️ How We Built It
We used Django for the backend and HTML Embedded View Model for the frontend. We used Wikipedia API, News API and OFAC Sanction List for enriching the context for the named entities ike organizations, locations, etc. Finally, we used the together API to call the Llama Gen AI Model for generating the output.

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
- **Kushal Das** - [GitHub](#) | [LinkedIn](#)
- **Rashmi Deshmuk** - [GitHub](#) | [LinkedIn](#)
- **Dhwanil M Shah** - [GitHub](#) | [LinkedIn](#)
