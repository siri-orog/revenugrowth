# revenugrowth
# 📈 Revenue Growth Predictor

A Streamlit-based web application that helps forecast a startup’s revenue growth over the next 1–5 years using basic financial and market indicators.

---

## 🚀 Features

- 📊 Visualize revenue growth trajectory using financial heuristics
- 🧮 Interactive input via sidebar for key business metrics:
  - Current revenue
  - Profit margin
  - Funding received
  - Burn rate
  - Market growth rate
  - CAC (Customer Acquisition Cost)
  - LTV (Customer Lifetime Value)
  - Social media sentiment
- 📉 Predicts revenue for 1 to 5 years into the future
- 📈 Dynamic Plotly chart and detailed forecast table
- 💡 Simple logic placeholder that can be replaced by real ML models

---

## 🛠 Tech Stack

- [Python 3.x](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly](https://plotly.com/)
- [Scikit-learn (optional)](https://scikit-learn.org/) – placeholder for ML models

---

## 📦 Installation

### 1. Clone the Repository

git clone https://github.com/siri-orgo/revenue-growth-predictor.git
cd revenue-growth-predictor
#### 2. Create Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv venv
# Activate it:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
#### 3. Install Dependencies
pip install -r requirements.txt
Or 
pip install streamlit numpy pandas plotly scikit-learn
▶️ Running the App
streamlit run revenue.py
Then open the local URL shown in the terminal (usually http://localhost:8501/).

