# Digital Humanities and Social Analytics in Practice Project Smell Stories

This is part of the project for the course Digital Humanities and Social Analytics in Practice at Vrije Universiteit 2024.

Information on the content:

human.xlsx , rich.xlsx and poor.xlsx are all the original datasets resulting from the Odeuropa Smell Extractor Tool. They were made by taking the texts from Das Parfum Social Classes and Scents pdf document.

Link to Odeuropa Smell Extractor Tool Demo: https://smell-extractor.tools.eurecom.fr/ 

The complete dataset of the three datasets put together is also included as xlsx file under the name 'Full Data'

The R markdown file 'Dataset_Preprocessing_Cloud.rmd' is where the original preprocessing of the datasets is done, and the word cloud visualisations are generated. Also, the datasets are saved after preprocessing and frequency calculation. Lastly, columns for class differentiation based on frequency in each social class division and labelling for the sentiment behind the smell quality were also added. 
This allowed for a contingency table, the values of which were used in Rstudio to conduct a chi-squared test.
The resulting dataset is saved into a CSV file with the name 'merged_data_freq.csv'

The files 'poor_freq.csv' , 'rich_freq.csv' and 'human_freq.csv' are made in R which include the preprocessed data plus frequencies.

The Jupyter notebook file 'R_Dataset_Visualisation.ipynb' is where the preprocessed files are then made into a Venn Diagram, a merged list of the data is made with a total frequency column is added, and a histogram of the resulting frequency merged dataset is created.
