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
    It is importnat to start the analysis considering that the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty - specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. For that reason, I had to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. For this reason, we have excluded 461 students that are from 9th grade at Thomas High School.

Comparing the results from the District Summary with and without 9th grade's scores from Thomas High School:
We can conclude that both % of Passing Math and Reading had a slight drop, for that reason, the Overall % of passing droped from 65.2% to 64.9%
![Screenshot](https://github.com/taiberkeley/Module_4_School_District_Analysis/blob/main/School%20District%20with%20vs%20whitout.png)

# How is the school summary affected?
    When we compare the Thomas High School summary data frame before and after excludimg 9th grade's scores, we conclude that % Passing Math and % Passing Reading were benefited. FOr that reason, the % Overall Passing went from 90.63% to 90.94% as per image below
 ![Screenshot](https://github.com/taiberkeley/Module_4_School_District_Analysis/blob/main/Thomas%20High%20School.png)   

# How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
Since we had to replace all 9th grade's scores by NaN, 461 student's grades were not considered and the overall passing percentage for Thomas High School was benefited from this once we removed from the calculation. Thomas High School ended up being on of the Top 5 best 

# How does replacing the ninth-grade scores affect the following:
    # Math and reading scores by grade: 
Scores by school spending
Scores by school size
Scores by school type
