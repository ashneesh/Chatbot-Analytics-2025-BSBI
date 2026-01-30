# Chatbot Analytics and Optimization

A project for the **MSc Artificial Intelligence** module *Chatbot Analytics and Optimization*, exploring analytics strategies, performance evaluation, and data-driven optimization for chatbots.

---

## Live Dashboard

**[View the Chatbot Analytics Dashboard on Hugging Face Spaces]([https://huggingface.co/spaces/ashneeshkaur/chatbot-analytics](https://huggingface.co/spaces/ashneeshkaur/chatbot_streamlit))**

---

## Report

**[Read the full assignment report →](Chatbot_Analytics_Ashneesh_Q1020792.pdf)**

The report covers the introduction, Task 1 (BotPress dashboard), Task 2.1 (performance analysis on TWCS), and Task 2.2 (exploratory and deep-dive metric analysis), with findings, visualisations, and optimisation strategies.

---

## Assignment Overview

**Module:** Chatbot Analytics and Optimization  
**Title:** Evaluating and Optimizing Intelligent Chatbots through Data Analytics  
**Word Limit:** 3000 words (±300)

### Learning Outcomes

- **LO1:** Design and implement analytics strategies for chatbots, apply NLP techniques to analyse user interactions and sentiment.
- **LO2:** Conduct research on industry-specific chatbot optimisation challenges and develop data-driven strategies.
- **LO3:** Optimise chatbot performance with user-centric design, personalisation, ethical considerations, and effective stakeholder communication.

---

## Project Structure

```
.
├── README.md
├── Chatbot_Analytics_Report.md
├── streamlit_app.py             # Task 1: Chatbot analytics dashboard
├── botpress_amazon_dump.csv     # Task 1: BotPress demo chatbot logs
├── twcs.csv                     # Task 2: Twitter Customer Support dataset
├── task_2.1.ipynb               # Task 2.1: Intent accuracy, response time, completion rate
├── task_2.2.ipynb               # Task 2.2: EDA, funnel, A/B test, sentiment, NPS
├── report_figures/              # Figures for the report
```

---

## Datasets

| Dataset | Source | Use |
|---------|--------|-----|
| `botpress_amazon_dump.csv` | BotPress demo (Amazon-style chatbot) | Task 1: Dashboard analytics, intent distribution, user segmentation |
| `twcs.csv` | [Customer Support on Twitter (Kaggle)](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter) | Task 2: Intent accuracy, response time, completion rate, EDA |

---

## Tech Stack

- **Python 3** — data processing and analytics
- **Streamlit** — interactive dashboard
- **Pandas** — data manipulation
- **Plotly** — interactive visualisations
- **scikit-learn** — classification metrics, confusion matrix
- **VADER** — sentiment analysis (Task 2.2)

---

## Running Locally

```bash
pip install streamlit pandas plotly
streamlit run streamlit_app.py
```

Ensure `botpress_amazon_dump.csv` is in the same directory.

---

## References

- [BotPress](https://botpress.com) | [BotPress Documentation](https://botpress.com/docs) | [Demo Bots](https://github.com/botpress/demo-bot)
- [Customer Support on Twitter (Kaggle)](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)
- [Hugging Face Spaces](https://huggingface.co/spaces)
