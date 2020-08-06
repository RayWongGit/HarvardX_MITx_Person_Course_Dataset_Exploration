# HarvardX MITx Person Course Dataset Exploration

## About Project

This project is a part of the author's research on retention in MOOC.

In this project, we try to explore the patterns of retention in MOOC, identify the features affecting retention in MOOC.




## Dataset


The dataset named 'HMXPC13_DI_v2_5-14-14.csv' is de-identified data from the first year (Academic Year 2013: Fall 2012, Spring 2013, and Summer 2013) of MITx and HarvardX courses on the edX platform along with related documentation.

These data are aggregate records, and each record represents one individual's activity in one edX course.  

The data description can be found in file 'Person+Course+Documentation.pdf' and 'HMX Data description.xlsx'

The dataset and documents are available on link below:

[dataverse.harvard.edu](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/26147)

## Project Process

### Data Wrangling

The dataset is pretty dirty. We have to do data wrangling to clean the data. This work is done in the jupyter notebook file 'HarvardX\_MITx\_Person\_Course\_Dataset\_Data_Wrangling.ipynb'

### EDA of Registered

We do EDA(Exploratory Data Analysis) for the registered (those who registered in the course)on the cleaned dataset. Refer to 'HarvardX\_MITx\_Person\_Course\_Dataset\_EDA_Registered.ipynb'

### EDA of Intended

In the EDA of registered we figured that completion rate of registered is misleading, we defined intended. Intended refers to those who intended to complete the course. We then do EDA for intended. Refer to  'HarvardX\_MITx\_Person\_Course\_Dataset\_EDA_Intended.ipynb'

### Final Exploration

Based on the EDA of Registered and Intended, we do a more formal analysis in 'HarvardX\_MITx\_Person\_Course_Dataset\_Exploration.ipynb'
### Machine Learning 

After identifying features affecting retention in MOOC, we aplly machine learning models to see how well these features can predict retention. Refer to 'completion\_prediction.ipynb'

## Reference
- [Education in the United States](https://en.wikipedia.org/wiki/Education_in_the_United_States)
- [How to change the font size on a matplotlib plot](https://stackoverflow.com/questions/3899980/how-to-change-the-font-size-on-a-matplotlib-plot)
- [matplotlib.pyplot.xticks](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.xticks.html)
- [HarvardX and MITx: The First Year of Open Online Courses, Fall 2012-Summer 2013](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2381263)

