# School_District_Analysis.

## Overview of Project

This project entails asssiting Maria, the chief data scientist for a city school district in analyzing data on student funding and student's standardized test scores.

I assisted Maria in analysing maths and reading scores for 39,170 students accross 15 schools. I aggregated data and provided trends to assist the school board and superinterndent in budget planning.

I had to do an extensive data cleaning by finding missing values, removing and replacing strings and fixing the students name.

The data analysed for Maria includes the count of students and schools, the total budget amount, average math and reading scores, perentage of students who passed math and reading, overall passing percentage,
scores by school type, scores by school size, scores by grade , high and low performing schools.

In addition, I also provided district and school summary for the report.

However, the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders
appear to have been altered.

Maria has asked me to replace the math and reading scores for Thomas High School for 9th graders with NaNs while keeping the rest of the data intact.

I will then repeat the school district analysis to see how the outcome will affect the analysis and report I presented earlier.

### Resources

* Data Source: schools_complete.csv, students_complete.csv, PyCitySchools_Challenge_starter_code.ipyn

* Software: Python 3.9, Visual Studio Code 1.56.0, Anaconda 4.9.2, Jupyter Notebook 6.1.4

## School District Analysis Results

In this section, we will see how the changes we made to the analysis affects the final results.
 
The below analysis and screenshots will provide insights to the following key areas;

### District Summary

Here we see a change to the Average match score, the average reading score, percentage of students passing math and reading, and a change to the overall passing percentage.

* The below image shows the result of the original analysis;

![District summary original](https://user-images.githubusercontent.com/81701640/118380365-2fc0c980-b5af-11eb-94ea-bdb90b575059.png)

* The below image shows the result after the requested modification to the analysis;

![District summary modified](https://user-images.githubusercontent.com/81701640/118380376-3f401280-b5af-11eb-81e7-6c26cb26c7d4.png)

### School Summary

The school summary shows that the data for Thomas high school changed.

The average math score, percentage of student passing math, percentage of student passing reading, the overall passing percentage were all impacted.

* The below image shows the result of the original analysis;

![School summary Original](https://user-images.githubusercontent.com/81701640/118376732-d305e480-b597-11eb-9a39-7f3844ce2aa9.png)

* The below image shows the result after the requested modification to the analysis;

![School summary Modified](https://user-images.githubusercontent.com/81701640/118376745-df8a3d00-b597-11eb-98ec-a63ae323a4aa.png)

* The below image shows the result when we compute using 10th to 12th grade of Thomas highschool for the analysis;

![School summary Modified](https://user-images.githubusercontent.com/81701640/118381158-08b9c600-b5b6-11eb-8bb8-d79e8e3c7984.png)

### Thomas High School performance relative to other schools

Replacing the ninth grade scores of Thomas High School with NaN resulted in a decline in Thomas high school overall performance from 2nd to 8th position.

* The overall passing percentage declined by 25.9% from 90.9% to 65.0%

* The below image shows the result of the original analysis;

![Overall Performance Original](https://user-images.githubusercontent.com/81701640/118377690-c9cb4680-b59c-11eb-9129-baca5092c315.png)

* The below image shows the result after the requested modification to the analysis;

![Overall Performance Modified](https://user-images.githubusercontent.com/81701640/118377693-d0f25480-b59c-11eb-80c9-3acb93702583.png)

From the above screen shot, we can clearly see the decline in the ranking of Thomas High school.

The image below shows the ranking when we use only information for the 10th to 12th graders for Thomas High School ;

![Overall Performance Modified 1012](https://user-images.githubusercontent.com/81701640/118381312-b8436800-b5b7-11eb-862d-7c24e5c79c9f.png)

Thomas High shcool retains its 2nd position ranking using this approach.

### Top 5 performing schools based on Overall Passing Rate;

We performed an analysis to see the performance of the schools using only score information of 10th to 12th graders.

Thomas high school emerged second following the recomputation of the overall passing percentage;

* The below image shows the top 5 performing schools by passing percentage;

![Top 5 Schools](https://user-images.githubusercontent.com/81701640/118377897-1f542300-b59e-11eb-9170-26ff7dca00fc.png)

### Bottom 5 performing schools based on Overall Passing Rate;

Thomas High School is not in the bottom 5 schools.

* The below image shows the bottom 5 performing schools by passing percentage;

![Bottom 5 Schools](https://user-images.githubusercontent.com/81701640/118377916-35fa7a00-b59e-11eb-8c54-8b4ae97d7489.png)

### Math and Reading Scores by Grade

There is no change to other grades (10th - 12th) within Thomas High school.

However, the 9th grade has been replaced. Hence, no 9th grade result for Thomas High School.

This significantly affected the overall 9th grade performance when viewed from the total school performance perspective.

* The below image shows the math result of the original analysis;

![Math Score Original](https://user-images.githubusercontent.com/81701640/118378279-aefad100-b5a0-11eb-9851-4dde4def5b34.png)

* The below image shows the math result after the requested modification to the analysis;

![Math Score Modified](https://user-images.githubusercontent.com/81701640/118378286-c1750a80-b5a0-11eb-8749-6c36435c788f.png)

* The below image shows the reading result of the original analysis;

![Reading Score Original](https://user-images.githubusercontent.com/81701640/118378326-07ca6980-b5a1-11eb-8e15-916e3369a007.png)

* The below image shows the reading result after the requested modification to the analysis;

![Reading Score Modified](https://user-images.githubusercontent.com/81701640/118378332-19ac0c80-b5a1-11eb-985d-7a90bf1c98cb.png)

### Scores by school spending

The average math score, percentage of student passing math, percentage of student passing reading, the overall passing percentage of school spending range $630 - $644 dropped 
as can be seen in the screenshots.

The average reading score increased slightly. 

This is as a result of the changes we made to the Thomas High School data.

It is imortant to note that when we present this information to the nearest tenths, the changes cannot be seen or can be classified as insignificant.


* The below image shows the result of the original analysis;

![Score by school spending range original](https://user-images.githubusercontent.com/81701640/118380646-5f70d100-b5b1-11eb-94b7-aea41e423294.png)

* The below image shows the result after the requested modification to the analysis;

![Score by school spending range modified](https://user-images.githubusercontent.com/81701640/118380660-74e5fb00-b5b1-11eb-8de9-817ce31fd093.png)

### Scores by school size

The average math score, percentage of student passing math, percentage of student passing reading, the overall passing percentage of school size medium (1000-2000) dropped 
as can be seen in the screenshots.

The average reading score increased slightly. 

This is as a result of the changes we made to the Thomas High School data.

It is imortant to note that when we present this information to the nearest tenths, the changes cannot be seen or can be classified as insignificant.

* The below image shows the result of the original analysis;

![Score by school size original](https://user-images.githubusercontent.com/81701640/118380732-11a89880-b5b2-11eb-8241-a5cce3e637ef.png)

* The below image shows the result after the requested modification to the analysis;

![Score by school size modified](https://user-images.githubusercontent.com/81701640/118380743-25ec9580-b5b2-11eb-9f8f-f03d07fcd820.png)

### Scores by school type

The average math score, percentage of student passing math, percentage of student passing reading, the overall passing percentage of school type "Charter" dropped 
as can be seen in the screenshots.

The average reading score increased slightly. 

This is as a result of the changes we made to the Thomas High School data.

It is imortant to note that when we present this information to the nearest tenths, the changes cannot be seen or can be classified as insignificant.

This is as a result of the changes we made to the Thomas High School data.

* The below image shows the result of the original analysis;

![School type original](https://user-images.githubusercontent.com/81701640/118379306-6f83b300-b5a7-11eb-9054-cbdb7e85e88f.png)

* The below image shows the result after the requested modification to the analysis;

![School type modified](https://user-images.githubusercontent.com/81701640/118379313-7ad6de80-b5a7-11eb-962d-274d6df12fcc.png)

## Code for the modified analysis

```python

# Install numpy using conda install numpy or pip install numpy. 
# Step 1. Import numpy as np.
import numpy as np

# Step 2. Use the loc method on the student_data_df to select all the reading scores from the 9th grade at Thomas High School and replace them with NaN.
student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") 
                    & (student_data_df["grade"] == "9th"), 'reading_score'] = np.nan
student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th")]

#  Step 3. Refactor the code in Step 2 to replace the math scores with NaN.
student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") 
                    & (student_data_df["grade"] == "9th"), 'reading_score'] = np.nan
student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") 
                    & (student_data_df["grade"] == "9th"), 'math_score'] = np.nan

student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th")]

# Step 1. Get the number of students that are in ninth grade at Thomas High School.
# These students have no grades. 
THS_9th_count = student_data_df.loc[(school_data_complete_df["school_name"] == "Thomas High School") & 
                                             (school_data_complete_df["grade"] == "9th")].count()["student_name"]

# Get the total student count 
student_count = school_data_complete_df["Student ID"].count()


# Step 2. Subtract the number of students that are in ninth grade at 
# Thomas High School from the total student count to get the new total student count.

student_count_new = student_count - THS_9th_count 
print(THS_9th_count)
print(student_count)
print(student_count_new)

# Calculate the passing rates using the "clean_student_data".
passing_math_count = school_data_complete_df[(school_data_complete_df["math_score"] >= 70)].count()["student_name"]
passing_reading_count = school_data_complete_df[(school_data_complete_df["reading_score"] >= 70)].count()["student_name"]
print(passing_math_count)
print(passing_reading_count)

# Step 3. Calculate the passing percentages with the new total student count.
passing_math_percentage = passing_math_count/student_count_new * 100
passing_reading_percentage = passing_reading_count/student_count_new * 100
print(passing_math_percentage)
print(passing_reading_percentage)

# Calculate the students who passed both reading and math.
passing_math_reading = school_data_complete_df[(school_data_complete_df["math_score"] >= 70)
                                               & (school_data_complete_df["reading_score"] >= 70)]

# Calculate the number of students that passed both reading and math.
overall_passing_math_reading_count = passing_math_reading["student_name"].count()


# Step 4.Calculate the overall passing percentage with new total student count.
overall_passing_percentage = overall_passing_math_reading_count/student_count_new * 100
print(passing_math_reading)
print(overall_passing_math_reading_count)
print(overall_passing_percentage)

# Step 5.  Get the number of 10th-12th graders from Thomas High School (THS).
THS_count = school_data_complete_df[(school_data_complete_df["school_name"] == "Thomas High School")
                                           & (school_data_complete_df["grade"] != "9th")].count()["student_name"]
print(THS_count)

# Step 6. Get all the students passing math from THS
THS_passing_math = school_data_complete_df.loc[(school_data_complete_df["school_name"] == "Thomas High School") & 
                                             (school_data_complete_df["math_score"] >= 70)]
THS_passing_math_count = school_data_complete_df.loc[(school_data_complete_df["school_name"] == "Thomas High School") & 
                                             (school_data_complete_df["math_score"] >= 70)].count()["student_name"]
print(THS_passing_math_count)                                             
print(THS_passing_math)

# Step 7. Get all the students passing reading from THS
THS_passing_reading = school_data_complete_df.loc[(school_data_complete_df["school_name"] == "Thomas High School") & 
                                             (school_data_complete_df["reading_score"] >= 70)]
THS_passing_reading_count = school_data_complete_df.loc[(school_data_complete_df["school_name"] == "Thomas High School") & 
                                             (school_data_complete_df["reading_score"] >= 70)].count()["student_name"]
print(THS_passing_reading_count)                                             
print(THS_passing_reading)

# Step 8. Get all the students passing math and reading from THS
THS_passing_math_reading = school_data_complete_df.loc[(school_data_complete_df["school_name"] == "Thomas High School") & 
                                                       (school_data_complete_df["math_score"] >= 70) & 
                                                       (school_data_complete_df["reading_score"] >= 70)]
THS_passing_math_reading_count = school_data_complete_df.loc[(school_data_complete_df["school_name"] == "Thomas High School") & 
                                                       (school_data_complete_df["math_score"] >= 70) & 
                                                       (school_data_complete_df["reading_score"] >= 70)].count()["student_name"]
print(THS_passing_math_reading_count)                                             
print(THS_passing_math_reading)

# Step 9. Calculate the percentage of 10th-12th grade students passing math from Thomas High School. 
THS_passing_math_percentage = THS_passing_math_count/THS_count * 100
THS_passing_math_percentage

# Step 10. Calculate the percentage of 10th-12th grade students passing reading from Thomas High School.
THS_passing_reading_percentage = THS_passing_reading_count/THS_count * 100
THS_passing_reading_percentage

# Step 11. Calculate the overall passing percentage of 10th-12th grade from Thomas High School. 
THS_overall_passing_percentage = THS_passing_math_reading_count/THS_count * 100
THS_overall_passing_percentage

# Step 12. Replace the passing math percent for Thomas High School in the per_school_summary_df.
per_school_summary_df.loc["Thomas High School", "% Passing Math"] = THS_passing_math_percentage

# Step 13. Replace the passing reading percentage for Thomas High School in the per_school_summary_df.
per_school_summary_df.loc["Thomas High School", "% Passing Reading"] = THS_passing_reading_percentage

# Step 14. Replace the overall passing percentage for Thomas High School in the per_school_summary_df.
per_school_summary_df.loc["Thomas High School", "% Overall Passing"] = THS_overall_passing_percentage

# Sort and show top five schools.
top_schools = per_school_summary_df.sort_values(["% Overall Passing"], ascending = False)
top_schools.head(5)

# Sort and show top five schools.
bottom_schools = per_school_summary_df.sort_values(["% Overall Passing"], ascending = True)
bottom_schools.head(5)

```

## Summary

Having analysed the school district results following the changes to Thomas High School math and reading score. We can come to the conclusion 
that the following changes to the school district analysis occured;

Firstly, the count of students in Thomas high school and the overall count of students for the analysis changed significantly after removing the number of 9th grade students (461)
from the analysis. This put the total number of students in Thomas High School at 1,174 and the overall number of students to 38,709.

Secondly, there was a change to the passing percentage in reading and math score for Thomas Highschool. This is as a result of the modification in the student count 
highlighted above.

Thirdly, the modification impacted on the ranking of the schools and also impacted the score averages for math and reading.
 
Finally, there were changes to results by school spending, school size and school type specifically in the buckets where Thomas High school falls under.

Though there were changes accross the parameters highlighted above, the impact on the summary results is not highly impacted by the changes to Thomas High School
when we look at averages and percentages to the nearest tenths .

**Nnaemeka Enukorah**

**15th May, 2021**

