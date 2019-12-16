# SalesPredictions

Data science project made by Fedor Stomakhin, Rain Trubetski, Egert Ott Metsandi.

Required libraries: numpy, pandas, seaborn, matplotlib, sklearn, keras


Info about running the code:

1. Upload the notebook file to Google Drive
2. Run the file using Google Colab

Info about the code:

1. Preprocessing of data - data grouped by date_block_num (month), columns to map item id's as category id's, changed category variables into one-hot vectors, normalized all numerical values, eliminated rows where sold item count was below zero
2. Sequential Model - trained using 85% of given test data (15% of it was left for testing), model has 4 Dense layers
3. Predicting next months' sales by the given test data using our trained model
