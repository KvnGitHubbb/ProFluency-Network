# ProFluency-Network (Processing Fluency Neural Network)

Below I give a short summary of the contents and the most important files 

# 📁 Codes

### 📁 controls
The variables for the panel regressions are stored here.  
These include the **control variables** from Compustat.

### 📁 data
Raw data that are either directly from the source or used to give extra insights. 

`data_nyse_screener.xlsx` contains the (cleaned) **company names** from the NASDAQ Screener.   
`data_lemma_internet.txt` is the **frequency list**, note that you to multiply the 'frequency' with 181,376 to get the real total amount of occurences.  
`data_lexicon.xlsx` is the **lexicon**, the list that contains many English words. 

### 📁 neural network
This file contains the architecture of the neural network.

### 📁 output neural network
`z_predictions_100x.xlsx` is the file that contains the **fluency predictions** for each company name.

### 📁 panel regressions
Contains the 3 **panel regressions** in Eviews.

### 📁 python
Contains Jupyter Notebook files written in python.

# LaTeX

### 📁 figures
Contains the figures that are used in this project.

### 🗒️ library.bib
Bibtex style references to other studies.

### 🗒️ main.tex
This file contains the thesis written in LaTeX.

# Prefixes
If you were curious why... 💭

* `data_`             &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    Raw data obtained from scources

* `data_filtered_`    &nbsp;         Processed raw data

* `data_reg_`         &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Regression data for testing the effect of fluency on the characteristics  

* `z_`  		          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Input and output data that are from the deep learning model  

* `py_`               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                Jupyter Notebook files with python code
