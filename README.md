# DHSAIP
Digital Humanities and Social Analytics in Practice

Information on the content:

human.xlsx , rich.xlsx and poor.xlsx are all the original datasets resulting from the Odeuropa Smell Extractor Tool. They were made by taking the texts from Das Parfum Social Classes and Scents pdf document.

Odeuropa Smell Extractor Tool Demo: https://smell-extractor.tools.eurecom.fr/ 

The complete dataset of the three datasets put together is also included as xlsx file under the name 'Full Data'

The R markdown file Dataset_Preprocessing_Cloud.rmd is where the original preprocessing of the datasets is done and the word cloud is generated. Also, the datasets are saved after preprocessing and frequency calculation.

The files poor_freq.csv , rich_freq.csv and human_freq.csv are made in R which include the preprocessed data plus frequencies.

The Jupyter notebook file R_Dataset_Visualisation.ipynb is where the preprocessed files are then made into a Venn Diagram, a merged list of the data is made with a total frequency column is added, and a histogram of the resulting frequency merged dataset is created.
