# 🧠 Financial Chatbot Prototype – BCG GenAI Job Simulation

This is a Python-based chatbot developed as part of the **BCG GenAI Job Simulation** on [Forage](https://www.theforage.com/). It answers five predefined financial questions using real company data extracted from 10-K and 10-Q reports.

---

## 💡 How It Works

- The chatbot runs in the command line or Jupyter Notebook and listens for **exact** user queries.
- It matches user input against **five predefined financial questions**.
- If a match is found, it returns a **static, prewritten answer**.
- If no match is found, it returns a **polite fallback message**.

---

## 📋 Predefined Queries

The chatbot understands only these specific questions:

1. What is the total revenue for Microsoft in 2024?  
2. How has Tesla’s net income changed from 2023 to 2024?  
3. What is Apple’s total assets in 2010?  
4. What is Microsoft’s cash flow from operating activities in 2023?  
5. What is Tesla’s total liabilities in 2022?

---

## ⚠️ Limitations

- Only **exact matches** are supported (no NLP or fuzzy matching).
- **Command-line** or **Jupyter Notebook interface only** — no web or GUI.
- Uses **static responses** instead of dynamically computed data.

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

---

## ▶️ How to Run

### Option 1: Run Online (Recommended)
Click below to launch the chatbot notebook in a live Binder environment (no setup needed):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tharani-kanuparthi/financial-chatbot-bcg/HEAD?filepath=financial_chatbot.ipynb)


### Option 2: Run in Command Line

1. Make sure Python 3 is installed.
2. Open terminal or command prompt.
3. Run the script:

```bash
python financial_chatbot.py
```

Type a predefined question to interact with the chatbot.

### Option 3: Run in Jupyter Notebook

1. Install Jupyter Notebook and Python 3.
2. Open terminal and run:

```bash
jupyter notebook
```

3. Open `Financial_Chatbot.ipynb` or `Financial_Analysis.ipynb`.
4. Run the cells to interact with the chatbot and view the data insights.

---

## 📂 File Overview

| File Name               | Description                                              |
|------------------------|----------------------------------------------------------|
| `Financial_Chatbot.ipynb` | Interactive chatbot with predefined financial responses. |
| `Financial_Analysis.ipynb`| Growth metrics and correlation heatmap analysis.        |
| `README.md`             | Project overview, instructions, and file details.        |
| `test_results.txt`      | Sample test outputs for the chatbot.                     |

---

## 📈 Sample Output

> Chatbot: What is the total revenue for Microsoft in 2024?  
> Response: The total revenue for Microsoft in 2024 is $245,122,000,000.
