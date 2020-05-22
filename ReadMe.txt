Author: Matthieu Nadini. 05/21/2020
For questions, please contact me: matthieu.nadini@gmail.com

###########################################################

Code to analyze our data collected to assess viable ways to increase the awareness in flu prevention
- All codes use Python 3 with the jupyter notebook. 
- In order to use it, install Anaconda 3. Other packages may have to be installed as well from the Linux terminal
  
  
##############################################################
In order to open the jupyter notebook, go into your the linux terminal and type
- jupyter notebook

##########################################################################################
Jupyter notebooks and their main function 
- CleanData.ipynb: it cleans and anonymize the original data (Not available for public use to protect anonymity)
- FromCategoricalToNumerical.ipynb: it transform categorical data in numerical ones, according to the definitions given in the manuscript
- AnalyzeCategoricalData.ipynb: it analyzes the catergorical data, producing part of the results used in the manuscript
- AnalyzeNumericalData.ipynb: it analyzes the numerical data, producing part of the results used in the manuscript


###########################################################
Input Folder
- it contains all data collected from our online study (Not available for public use to protect anonymity)

#################################################
Output Folder
- CleanedCategoricalData.csv: it contains the cleaned, anonymized data with original entries
- CleanedNumericalData.csv: it contains the cleaned, anonymized data with numerical entries
- Plot Subfolder: it contains part of the results used in the manuscript; the remaining part can are only printer in the selected jupyter notebook

