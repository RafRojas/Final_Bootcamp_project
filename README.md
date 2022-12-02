# Final Bootcamp Project:

A school in the United States is interested on knowing in advance which of their students may or may not end in summer school at the end of the year. The head of the school has been gathering data of the student's performances and also some characteristics they consider relevant. 

The principal has hired us to make a machine learning model to predict the flow of students to the school in the summer break, they want an estimate of how many students will attend their summer school to catch up on their failed classes.

In order to do this we will do a full analysis of the student's performance given the characteristics the school has considered important, which will help us to predict the students that are going to attend the summer school before the next school year.

We will ask ourselves some burning questions such as:

- Who has the best GPA between males and females?
- Which ethnicity is the most representive in the school? What are their GPAs? How about the others?
- How does the parental education of the alumny affects their performance?
- Does the lunch plan affect how the students perform on their tests?
- Are the test prepration courses helpful for the students? How many students have completed it before taking their exams?

# Dataframe: 
- Gender: male or female.
- Ethnicity: divided into groups going from A to E.
- Parental education: goes from some high school to some college, incluiding the completed degrees in between such as associates.
- Lunch plan: the students have to pick between the paid standard lunch plan and the free reduced lunch plan.
- Test preparation Course: the school has available an optional course to help the alumny study for their exams.
- Math score: the results of the math exam.
- Reading score: the results of the reading exam.
- Writing score: the results of the writing exam.

The original version of the data can be found [here](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?sort=votes):

# Modeling of the data:

There are 6 available models to predict our data. The best results were given by the regression models, specifically linear regression and KNN regressor. Meaning that our data is best described by regressors instead of classifiers.

# Conclusions:

- The linear models all managed to predict succesfully the number of failed students based on the data, unfortunately in most cases it wasn't able to predict their GPA correctly.
- The parental education seemed to be the most relevant value when it comes to predicting the students GPA.
- The models did not seem to take into account that the students without the standard lunch plan had a lower GPA.
- The test preparation course did not seem to be that important for the students results.
- The students with the most extra curricular activities seemed to get better results on their exams.
