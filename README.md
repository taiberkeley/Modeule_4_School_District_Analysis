# Module_4_School_District_Analysis
# 1. Overview of the school district analysis: 
The objective of this analysis is to perform a comprehensive analysis of the scholl district grades. After making sure the data is cleaned, transformed, manipulated, analyzed,    and visualized, we will present the results to the School Board
#  Here is the list of the deliverables ofthis analysis: 
    A high-level snapshot of the district's key metrics, presented in a table format
    An overview of the key metrics for each school, presented in a table format
    Tables presenting each of the following metrics:
    Top 5 and bottom 5 performing schools, based on the overall passing rate
    The average math score received by students in each grade level at each school
    The average reading score received by students in each grade level at each school
    School performance based on the budget per student
    School performance based on the school size 
    School performance based on the type of schoolA high-level snapshot of the district's key metrics, presented in a table formatAn overview of the key metrics for each school, presented in a table format
 # 2. Results: 
 # How is the district summary affected? 
    It is importnat to start the analysis considering that the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty - specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. For that reason, I had to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. For this reason, we have excluded 462 students that are from 9th grade at Thomas High School
#  Here is the command used to determine the number of students at the 9th grade at Thomas High School:        
    student_9th_count = school_data_complete_df.loc[(school_data_complete_df["school_name"]=="Thomas High School") & (school_data_complete_df["grade"]=="9th"),"Student ID"].count()
   student_9th_count
