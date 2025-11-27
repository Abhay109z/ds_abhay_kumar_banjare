# 📊 Trader Sentiment Analysis – Data Science Project

## 📂 Project Structure

ds_abhay_kumar_banjare/       
│
├── csv_files/               
│   ├── trader_data_raw.csv       
│   ├── sentiment_raw.csv         
│   ├── trader_data_clean.csv      
│   ├── agg_daily_metrics.csv     
│   ├── daily_with_sentiment.csv   
│   ├── ttests_alignment.csv      
│   ├── aligned_vs_contrarian.csv 
│   └── summary_kpis.csv          
│
├── outputs/                 
│   ├── pnl_by_sentiment.png      
│   ├── leverage_over_time.png    
│   ├── notional_by_sentiment.png 
│   ├── contrarian_vs_aligned_pnlrate.png 
│   └── ds_report.pdf              
│
└── notebook.ipynb           

---

## 📖 Project Overview
This project analyzes **trader sentiment** using historical trading data.  
The workflow includes:
- Data loading and preprocessing  
- Sentiment integration  
- Statistical analysis (t-tests, KPIs)  
- Visualization of trading metrics  
- Automated report generation  

---

## ⚙️ Usage Instructions (Google Colab)

1. **Open the notebook in Google Colab**
   - Upload the `notebook.ipynb` file to your Google Drive.
   - Right‑click → *Open with* → *Google Colaboratory*.

2. **Install required libraries**
   Run this cell at the start of the notebook:
   ```python
   !pip install pandas numpy matplotlib seaborn scipy reportlab gdown
