# week4_pandas_jupyternotebook_homework
Week 4 Pandas and Jupyter notebook homework submission

# Overview of the school district analysis:
There were evidence of academic dishonesty for ninth graders at Thomas HighSchool. The request is to update the data for these studdents and update the analysis of how school spending per student affect the school's average scores and passing percentages. This information will help the school board make decisions about the budget for the upcoming school year.

# Results
-How is the district summary affected?
    The district summary was minimally affected. The ninth graders at Thomas HighSchool were a small population of 461 students out of a total of 39170.   


-How is the school summary affected?
    The school summary was slightly changed just by the Thomas Highschool's data.


-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s   performance relative to the other schools?

The school summary was  affected. As seen below, the before the 9th graders were updated to NaN, the percentages for passing math and reading were lower compared to after the corrections. 

!school_summary_before_changes


!school_summary_after_changes

-How does replacing the ninth-grade scores affect the following:
    -Math and reading scores by grade
        The scored by grade was not impacted. 

    -Scores by school spending 
        The school spending was minimally impacted by replacing the ninth graders. As shown below the data is similar to before the changes.
       
        Before:
            !spending_summary_before_changes


        After:
            !spending_summary_after_changes


    -Scores by school size
        The scores by school size also was not impacted. 

         Before:

            !scores_by_school_size_before_changes

        After: 

            !scores_by_school_size_after_changes


    -Scores by school type
        The scores by school type was not impacted either.

# Summary:
    The summaries were slightly changed. However, the total students changed from a total of 39170 to 38709. The passing percentages for Thomas highschool changed as well. The initial  % Passing Math	=66.91, % Passing Reading =69.66 , % Overall Passing= 65.07 to % Passing Math = 93.18, % Passing Reading =97.01 , % Overall Passing= 90.63. 
    With the small population of ninth graders the spendings did not significantly change. 
