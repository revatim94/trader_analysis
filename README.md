

## 📁 Project Structure

historical_data.csv # Trade-level data
├── fear_greed_index.csv # Market sentiment data
├── analysis.ipynb # Jupyter notebook (analysis + dashboard)
├── README.md # Project 


---

## 🧰 Requirements

- Python **3.8+**
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - matplotlib
  - ipywidgets

---

## ⚙️ Setup Instructions

### 1️⃣ Clone or download the project
Place all files in the same directory.

### 2️⃣ Install dependencies
Run this in **terminal or Anaconda Prompt**:

▶️ How to Run the Project
1️⃣ Start Jupyter Notebook

bash
pip install notebook

pip install pandas matplotlib ipywidgets

Open the notebook

Open:historical.ipynb

3️⃣ Run cells in order

Run all cells top to bottom to:

Load and clean data

Aggregate daily metrics

Merge sentiment data

Launch the interactive dashboard

📊 Dashboard Features

The interactive dashboard allows:

Account-wise performance analysis

Daily PnL visualization

Trade frequency analysis

Average trade size tracking

Long / Short ratio analysis

Alignment with Fear vs Greed sentiment

The dashboard is implemented using Jupyter ipywidgets, allowing interaction directly inside the notebook.

📈 Key Metrics Created

Daily PnL per account

Trade count per day

Average trade size (USD)

Long / Short ratio

Sentiment classification (Fear / Greed)

🧠 Analysis Goals

Compare trader performance on Fear vs Greed days

Identify behavioral changes under different sentiment regimes

Segment traders based on activity and consistency

Derive actionable trading insights

📝 Notes

Streamlit is not required to run this project.

The dashboard runs fully inside Jupyter Notebook.

Some accounts may show single-day data due to sparse trading activity.

🚀 Future Enhancements (Optional)

Predictive model for next-day profitability

Trader clustering into behavioral archetypes

Streamlit-based web dashboard

Author

Trader Performance & Sentiment Analysis
Built for data analysis and behavioral finance use cases


---

## ✅ What this README gives you
✔ Clear setup  
✔ Clear run instructions  
✔ Looks professional  
✔ Safe for submission & GitHub  
✔ Explains **why Jupyter widgets were used**


No file chosen
Attach files by dragging & dropping, selecting or pasting them.
