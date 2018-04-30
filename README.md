# Lending-Club-Data-Analysis
Complete data analysis and machine learning models through lending club dataset

https://www.kaggle.com/c/lending-club/data

Author: Saleban Olow
Title: Apply analysis technique and machine learning models on Lending Club dataset 
Data From: https://www.kaggle.com/wendykan/lending-club-loan-data/data 
Last Modified: 4/29/2018

### Once you download the data,
```Python
  def load_data(filename):
    """Read from local file"""
    return pd.read_csv(filename + ".csv", low_memory=False)
    
  data = load_data("lending_club_train_data")
```
