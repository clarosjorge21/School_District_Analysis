# School_District_Analysis

## Overview of Project

### Purpose
The purpose of this project is to use Jupyter notebook to help Maria and her supervisor in sorting and comparing the math & reading grades between different schools. 
### Summary
Maria and her supervisor have been shown evidence of academic dishonesty for the Thomas High School ninth graders. We are here to help Maria replacing the math and reading scores for Thomas High School to NaNs while keeping the rest of the information intact.   

### School District Analysis Results

* #### How is the district summary affect?
  * By omitting the grades of the 9th grade class from Thomas High School, we could see a couple of changes. One of the changes is that the overall passing percentage for the entire district fell from 65.17% to 64.9%. Along with the overall passing percentage, the math and reading passing % decreased as well. The math passing % went from 74.98% to 74.8% and the reading passing % went from 85.81% to 85.7%.  
  * ![This is an image](https://github.com/clarosjorge21/School_District_Analysis/blob/1c1029cb71d667ff79f086c4b4c68fd582d84124/Resources/district_summary.PNG)

* #### How is the school summary affected?
  * The school summary is affected in every category after the "Per School Budget" column. Average math score went from 83.42 to 83.35 and average reading score went from 83.85 to 83.90. As you can see, it increased the average math score while it increased the average reading score. The % passing math went from 93.27 to 66.91 and the % passing math went from 93.30 to 69.66. Giving a big difference between both % of passing. The overall passing % went from 90.95 to 65.08, which is also a significant drop. 
 
* #### How does replacing the ninth grader's math and reading scores affect Thomas High School's Performance relative to the other schools>
  * By ommitting the 9th grader's and replacing it with NaaN you can see a significant difference in some parts. For example, Thomas High School goes from not being in the top 5 to being in the top 3. The overall passing percentage increases to 90.63%. While the passing math and reading % go from mid 60s to low 90s. 

* #### How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade 
    *  ![This is an image](https://github.com/clarosjorge21/School_District_Analysis/blob/1c1029cb71d667ff79f086c4b4c68fd582d84124/Resources/reading_scores_grade.PNG)
    *  ![This is an image](https://github.com/clarosjorge21/School_District_Analysis/blob/1c1029cb71d667ff79f086c4b4c68fd582d84124/Resources/math_scores_grade.PNG)
    *  Replacing the 9th grade scores doesn't affect the other grades at all. You can see the difference between the schools and not between the grades in Thomas High School. 

  * Scores by school spending
    * ![This is an image](https://github.com/clarosjorge21/School_District_Analysis/blob/1c1029cb71d667ff79f086c4b4c68fd582d84124/Resources/school_spending.PNG)
    * The picture above shows that even though more was spent per student it did not mean that the grades increased. In fact, it meant the opposite, the more a school spent per student the lower the grade was. This showing that there might be an issue in another category. The overall passing % decreased by almost 9% from a school that spent $584 per student compared to one that spent a range of $585 to $629. 


  * Scores by school size
    * ![This is an image](https://github.com/clarosjorge21/School_District_Analysis/blob/1c1029cb71d667ff79f086c4b4c68fd582d84124/Resources/school_size.PNG)
    * The picture above shows that school size does make a difference when it comes to scores. Small and Medium sized schools tend to do better compared to the large sized schools. While The difference between small and medium sized schools are within .03% to .1%, the difference between medium and large sized schools are roughly between 1.5% up to almost 24%.
    
  * Scores by school type 
    * ![This is an image](https://github.com/clarosjorge21/School_District_Analysis/blob/1c1029cb71d667ff79f086c4b4c68fd582d84124/Resources/charter_vs_district.PNG)
    * Charter and District could be seen with a similar type of difference compared to the school size. The differences range from 2.9% up to 36%, charter schools consistently being better than district schools.  
 
### School District Analysis Summary

To summarize there are a few things we can take away from our analysis: 
 * While running the analysis we want to make sure that we completely omit the grades of the 9th grade instead of leaving them as 0. By omitting and replacing, we can make sure that our analysis is more concrete and isn't lowered by the 9th grade. To add, by removing the 9th grade and not replacing it affects not only the school but the district overall. 
 * Increased spending does not equal to better grades.
 * The smaller the school, the better the grades. Due to the school being smaller, it means more focus on students.
 * Even if we remove one grade, it will not affect the other grades.
 * Charter schools tend to do better than district schools. 
 * Even though there was academic dishonesty, it is not safe to assume that it was the whole 9th grade class. Every other grade maintained good grades compared to other schools. 

