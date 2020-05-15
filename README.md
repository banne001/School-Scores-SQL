# School-Scores-SQL
Project for Database fundamentals. 
Object: re-organize a real life data. Create questions that is able to be answered by writing an sql command

Analysis

The school score database shows the amount of test takers and average math and verbal scores for the SAT test. The database consists of scores from all states in the USA for each year from 2005 to 2015. There are 7 look-up table containing a name or description and a corresponding id. The look-up tables are family-income-range, gpas, score_range, types, subjects, state, and year. There are also 6 linking tables that consists of foreign keys from the look-up tables and contains the results (i.e. verbal and math score, and test takers). The linking tables are Fam_income_scores, gpa_scores, score_range_students, gender_scores, subject_averages, and score. The gpa_scores table is the only table that does not have average math and verbal scores and test takers, but it does have average gpa and average year.

As a student, it is interesting to see how other students have done on the same test. Also, this dataset includes other factors other than GPAs, it includes family income, gender, and all of the states spanning 10 years.

Questions

1. Display the scores of states that contain the word “New” and has an Average Math score between 550-600

2. Display the top 5 Average Verbal scores and years of Texas with a GPA of “A+”, “A-”, or “A.”

3. Show the States and average female math scores that are more than the average score of males in 2015.

4. What Family income range has the most test takers in California on 2010.

5. Show the state, average gpa, average verbal score for the highest average GPA in the subject of “Arts/Music” for each year.

6. Show the Total number of male students in each score range on 2013 that is greater than 5000.
