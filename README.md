# Social-media
Social media project

 # Disaster Tweets Analysis

This project analyzes the **proportion of authentic vs. misleading tweets** related to natural disasters on Twitter.  
The workflow combines **data preprocessing in Python (Jupyter Notebook)** with **visualization in Tableau**.

---

## 📂 Files in this Repository

- **`disaster_tweets.csv`** → Raw dataset of tweets.  
- **`tweet_result.csv`** → Cleaned dataset (output after processing in the notebook).  
- **`Final_analyse.ipynb`** → Jupyter Notebook with preprocessing and analysis steps.  
- **`Book5.twbx`** → Tableau packaged workbook with the **cleaned dataset already included**.  
- **`README.md`** → Project documentation (this file).  

---

## ⚙️ How to Run the Notebook (Google Colab)

1. Open the notebook (`notebook.ipynb`) in **Google Colab**.  
2. Upload `disaster_tweets.csv` to the **`sample_data`** folder in Colab.  
3. The dataset is loaded with:

   ```python
   import pandas as pd
   data = pd.read_csv('/content/sample_data/disaster_tweets.csv')

Run all cells to clean and process the data.

The cleaned output will be saved as tweet_result.csv.

## 📊 Tableau Dashboard

Open Book8.twbx in Tableau Desktop or upload it to Tableau Public.

The workbook already includes tweet_result.csv, so you can explore the dashboard immediately without re-importing the dataset.

## 🚀 Workflow Summary

Start with disaster_tweets.csv (raw dataset).

Run the Jupyter Notebook → generates tweet_result.csv.

Tableau analysis is already prepared in Book8.twbx.

Explore the dashboard to analyze the proportion of authentic vs. misleading tweets.

## 📝 Notes

Required Python libraries: pandas, numpy (add others if used in the notebook).

In Colab, remember to place disaster_tweets.csv inside /content/sample_data/.
