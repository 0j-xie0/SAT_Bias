# SAT Bias in NYC schools
### •To examine potential biases inherent in the SAT across high schools in New York City.

# Installation
•Clone this repo to your computer.  
•Install the requirements using pip install -r requirements.txt.  
•Make sure you use Python 3.  
•You may want to install [Jupyter](http://jupyter.org/install) to run the ipynb.

# Usage
•Run the Jupyter Notebook "SAT.Bias.ipynb" either in Jupyter or the IDE of your choice.

# Tasks Performed
### •Combined the following data sets into a single, clean pandas dataframe:
••SAT scores by school - SAT scores for each high school in New York City.  
••School attendance - Attendance information for each school in New York City.  
••Class size - Information on class size for each school.  
••AP test results - Advanced Placement (AP) exam results for each high school.  
••Graduation outcomes - The percentage of students who graduated, and other outcome information.  
••Demographics - Demographic information for each school.  
••School survey - Surveys of parents, teachers, and students at each school.  
### Examined Links between Survey Data & SAT Scores
••Visualized correlations between parent, teacher and student survey data with SAT scores using bar plots.
### Investigated Relationships between Perceived Safety & SAT Scores
••Visualized correlations between perceived safety of parents, teachers and students with SAT scores using scatter plots.
### Investigated Racial Differences in SAT Scores:
••Visualized correlations across races (white, asian, black, hispanic) with SAT scores using bar and scatter plots.
### Investigated Gender Differences in SAT Scores:
••Visualized correlations between gender and SAT scores using bar and scatter plots.
### Examined Links between AP Exam Taking and SAT Scores:
••Calculated percentage of students in each school that took AP exam.  
••Visualized correlations between the percentage of AP test takers in each school with SAT scores using scatter plots.

# Observations
### •From the correlation bar plots, the number of student and parent survey respondents have a high correlation with SAT scores. It is prudent to infer that parent, as well as student involvement, equates to higher academic achievement.
### •From the correlation bar plots, safety and respect scores based on how safe the learning environment is perceived by student and teachers seems to be a highly correlated factor in doing well academically. However, scatter plots reveal that there is a weak or perhaps no relationship bewteen perceived safety and SAT scores.   
### •From Basemap plots, Brooklyn has higher safety scores. Queens, Bronx and Upper Manhattan have lower scores.
### •From the correlation bar plots, there are positive correlations between percentage of whites and asians and SAT scores.
••The high positive correlation of percentage asian challenges the assumption that the SAT is racially biased against minorities.
### •Race and SAT scores might be a spurious correlation. A likely confounding variable might be socio-economics.
••On further examination the list of schools with high ESL enrollment have low SAT scores. This reveals that low language comprehension might also be a confounding variable.  
••On further examination the list of schools that are well-funded, provide extra help for students, hence well-funded schools tend to have high SAT scores. This reveals that socio-economics is a crucial factor for high SAT scores.
### No discernable relationship between gender & SAT scores.
### No discernable relationship between AP test taking & SAT scores.


# Potential Next Steps
•Determine whether there's a correlation between class size and SAT scores.  
•Explore neighborhoods with the best schools:  
•Investigate differences between parent, teacher, and student responses to surveys.  
•Assign scores to schools based on SAT score and other attributes.
