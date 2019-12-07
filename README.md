# (Dataset Exploration Title)
## by (your name here)


## Dataset


The dataset named 'HMXPC13_DI_v2_5-14-14.csv' is de-identified data from the first year (Academic Year 2013: Fall 2012, Spring 2013, and Summer 2013) of MITx and HarvardX courses on the edX platform along with related documentation.

These data are aggregate records, and each record represents one individual's activity in one edX course.  

The data description can be found in file 'Person+Course+Documentation.pdf', for better understanding of each variable, I also put the description of each variable into a spreadsheet(named 'HMX Data description.xlsx') with some comments.

The dataset and documents are available on link below:

[dataverse.harvard.edu](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/26147)

Since the dataset is pretty dirty, we have to do a lot data wrangling before exploring it, this process including:

- Filter out unreliable records
- Handling missing data
- Convert data type

For better exploration,we also did some feature engineering work, like  created 'start year', 'age' variable and so on.

## Summary of Findings
- Most of the students are not certified at the end of the course, hte proportion os certified is only about 3%.
- Most students get a grade of 0, which makes the histogram a long tail.Although we tried square root and cube root tranformation, it did not make too much difference.
- For countries of the students, we noticed that there are about 30% percent students from US, after that is about 15% from India.Following by UK and Brazil, each has 3%.
- As much as 40% students hold a Bachelor's Degree, while around 20% hold a Master's, 3% hold a Doctorate Degree. That is to say, the mojority of the students have a education level of Bachelor's or higher. We are educating the well educated.
- Regarding the age of students, the peak appears at age 22-24. And there is a long tail at the age > 50.
- For gender, 75% of the students are male, which is about 3 times of female
- activity variables: based on the exploration above, especially for certified and grade, it is not surprising that all the activity variables are right scewed, most of the values are 0.


## Key Insights for Presentation

One of the plot I polished for further exploration is the bar chart of certified, which is one of our two variables of interest, sicne the distribution of the other variable grade is seriously skewed. 
What I did to polish this plot including:

- Set the font size
- Set the figure size
- Change labels of xticks
- Add title
- Add x label
- Add y label

## Reference
- [Education in the United States](https://en.wikipedia.org/wiki/Education_in_the_United_States)
- [How to change the font size on a matplotlib plot](https://stackoverflow.com/questions/3899980/how-to-change-the-font-size-on-a-matplotlib-plot)
- [matplotlib.pyplot.xticks](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.xticks.html)
- [HarvardX and MITx: The First Year of Open Online Courses, Fall 2012-Summer 2013](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2381263)

