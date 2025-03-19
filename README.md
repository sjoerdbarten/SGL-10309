Scripts to preprocess LML and MAQ-Observations (Veenkampen) data for the SGL-10306 course NH3 deposition practical.

The ‘PrepareLMLdata.ipynb’ makes the Data_AQ_*_year-year.csv files from the LML API.
The ‘PrepareVeenkampenData.ipynb’ makes the Data_Meteo_Veenkampen_year-year.csv file from the MAQ-Observations API.

Both Notebooks should be pretty flexible in just selecting the start data and end date and new files will roll out.

Please note that for MAQ-Observations you need to request an API key first (https://maq-observations.nl/api/) and put it in the Python Notebook.
