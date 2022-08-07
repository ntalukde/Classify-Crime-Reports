# Classify-Reports
The goal of this project is to classify reports based on date, location, and text description of the report.

In classify_reports-location_time_data.ipynb I explored and visualized spatial and temporal data. I trained a Random Forest with XY coordinates and performed prediction on the validation data.

In classify_reports-text_data.ipynb I tokenized text data and generated word embeddings. Then I trained a Neural Network with these word embeddings. On validation data best accuracy is 97.42%. On test data accuracy is 97.57%.
