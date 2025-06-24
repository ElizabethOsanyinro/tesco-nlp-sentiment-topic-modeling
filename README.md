# Tesco NLP Sentiment & Topic Modeling

This project analyzes 46,343 customer reviews from Tesco Bank and Tesco Stores using Natural Language Processing (NLP) techniques. It combines sentiment analysis and topic modeling to identify key service issues and understand how customer sentiment varies across topics and sectors.

---

## Project Overview

- **Goal**: Compare customer experience trends across Tesco Bank and Tesco Stores using AI-powered text analytics.
- **Methods Used**:
  - VADER and BERT-based sentiment analysis
  - LDA topic modeling with coherence evaluation
  - Trustpilot review scraping and preprocessing
- **Outputs**:
  - Sentiment distribution by topic and sector
  - Key customer concerns and satisfaction drivers
  - Visual insights using Matplotlib, Seaborn, and WordCloud

---

## Technologies & Tools

- **NLP**: NLTK, spaCy, Gensim
- **Sentiment Models**: VADER, HuggingFace Transformers (RoBERTa)
- **Visualization**: Matplotlib, Seaborn, WordCloud, pyLDAvis
- **Evaluation**: Scikit-learn (Precision, Recall, F1-score)
- **Environment**: Python 3.11, Jupyter, Google Colab

---

## 📊 Visualisations
Check Tesco_visualisations

## 📁 Project Structure

```
tesco-nlp-sentiment-topic-modeling/
├── README.md
├── requirements.txt
├── LICENSE                 # MIT License for open use
├── data/                   # Raw and cleaned review datasets
├── notebooks/              # Jupyter notebooks for scraping and analysis
├── src/                    # Python scripts for preprocessing, modeling, etc.
├── Tesco_visualisation/    # Plots, charts, and word clouds


## 📌 Key Insights

- **Tesco Bank reviews were mostly positive**, with customers appreciating service availability and ease of use. However, negative sentiment was often tied to **credit card issues**, **insurance claims**, and **unresponsive customer service** — areas needing rapid attention.

- **Tesco Stores attracted more negative reviews**, especially around **delivery problems**, **inconsistent pricing**, and **product quality complaints**. Customers also compared Tesco unfavourably with competitors, highlighting a potential brand trust gap.

- **BERT-based sentiment analysis** offered stronger performance than rule-based models like VADER, especially for detecting subtle dissatisfaction and mixed emotions — making it more suitable for high-stakes service sectors.

- **Topic modelling revealed distinct themes** across the banking and retail sectors, confirming that customer expectations differ significantly between digital financial services and physical retail experiences.

- AI-powered review analysis enables **real-time issue detection**, empowering business owners to move from reactive problem-solving to proactive customer engagement strategies.

## 🧭 Strategic Recommendations

Using SWOT, TOWS, and Balanced Scorecard (BSC) frameworks, this study recommends:

- **For Tesco Bank**:
  - Improve responsiveness in credit and insurance complaint resolution through intelligent routing and chatbot support.
  - Use AI to flag repeated complaints and route to human agents with context-aware summaries.

- **For Tesco Stores**:
  - Enhance logistics reliability and pricing transparency across digital and physical platforms.
  - Benchmark customer feedback trends against competitors to refine loyalty strategies.

- **Cross-sector AI Application**:
  - Integrate sentiment tracking dashboards into CX workflows.
  - Apply topic modelling for continuous service improvement and workforce alignment.

These recommendations highlight the **transformational power of AI** in unlocking insights from unstructured feedback and driving service innovation across sectors.


## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open any of the notebooks in the `/notebooks/` folder to explore the project:
   - `Tesco_Bank.ipynb`: Scrapes and preprocesses Tesco Bank reviews
   - `Tesco_Trend_Analysis.ipynb`: Compares sentiment and issues across both sectors
   - `Tesco_Sentiment_&_Topic_Modelling.ipynb`: Performs sentiment analysis and topic modeling

Alternatively, run core scripts in the `/src/` folder for automation.

---

## 👩🏽‍💻 Author

**Elizabeth Osanyinro**  
MSc Applied AI & Data Analytics, University of Bradford  
GitHub: [@ElizabethOsanyinro](https://github.com/ElizabethOsanyinro)

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
