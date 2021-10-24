# School_District_Analysis
## Overview of Analysis  
We are tasked with evaluating several metrics of school performance based on reading and math testing scores for a certain set of schools. In particular, we are interested in the effects of school, school size, budget, per-student budget, and school type on reading and math scores including number of "passing score". Given two files with the appropriate data we performed a detailed analysis of the data to answer these questions. However, given these results, there is concern that the ninth grade scores from one particular high school, Thomas High School may have been altered to affect the overall performance of that high school.  We therefore were tasked with re-performing the analysis with the Thomas High School ninth grade scores excluded to see how this affects the results.  Data is stored in the resources folder. Code for analyzing data include PyCitySchools.ipynb which analyzes the data leaving everything intact while PyCitySchools_Challenge.ipynb analyzes the data after removing the scores of interest (Thomas High School ninth grade math and reading scores).
## Results  
*  Removing the Thomas High School ninth grade data had a minimal effect on the overall district results with only a slight decrease in average scores and percentages of students with passing scores in both reading and math.  
  
    District Results with ninth grade data from Thomas High School:    
    ![district_summary_old](https://user-images.githubusercontent.com/60231630/138578338-321bf0a5-1d7d-4d67-8658-1a7d3232120d.png)  
    District Results with ninth grade data removed/replaced with NaNs:  
    ![district_summary_new](https://user-images.githubusercontent.com/60231630/138578353-7ee6f36a-6013-42bd-ac4f-ca68406a10fa.png)


*  No significant effect is observed in school summary data except for a non-significant decrease in the percentage of passing students by no more than a few tenths of a percent. In other words, the metrics are largely not effected.
*  Likewise, removal of ninth grade scores has no effect on school rankings as Thomas High School still remains in the top five schools in terms of students who earned passing reading and math scores with a second place rank.  
    Top five performing schools with ninth grade data from Thomas High School:  
    ![top_rank_old](https://user-images.githubusercontent.com/60231630/138578453-5943b94f-addd-4139-af19-3cca2356ffcb.png)  
    
    Top five performing schools with ninth grade data from Thomas High School removed/replaced with NaNs:  
    ![top_rank_new](https://user-images.githubusercontent.com/60231630/138578503-90569420-2fe8-41f9-af89-d241e67f3f97.png)


* Reading and math results based on grade were unchanged by the removal of Thomas High School ninth grade results with the exception that this results in missing data for Thomas High School at the ninth grade level.  
    Math by grade results with Thomas High School ninth grade data intact:  
    ![math_by_grade_old](https://user-images.githubusercontent.com/60231630/138578536-4bb6ab5d-5f0d-4acf-b342-a33c50846702.png)  
    
    Math by grade results with Thomas High School ninth grade data removed/replaced by NaNs:
    ![math_by_grade_new](https://user-images.githubusercontent.com/60231630/138578550-c4661807-2275-442d-ba3f-5d251e8052c7.png)



* Likewise there is zero effect on scores as they relate to school spending by removal of the ninth grade scores from Thomas High School. 
    Original spending summary results:   
    ![spending_summary_old](https://user-images.githubusercontent.com/60231630/138578583-84536a39-f7fc-43b3-befc-b859e7a80ee2.png)
    
    Spending summary results after removal of Thomas High School ninth grade data:  
    ![spending_summary_new](https://user-images.githubusercontent.com/60231630/138578586-97b77840-adc6-49b9-abb9-2bb834fe22b1.png)


* With regard to the effects of school size on reading and math scores, there is also no observed effect of removing the ninth grade scores from Thomas High School.  
      Original size summary results:  
      ![school_size_old](https://user-images.githubusercontent.com/60231630/138578611-43164c0e-4c5f-481f-9717-894447591522.png)  
      Size summary results after removal of Thomas High School ninth grade data: 
      ![school_type_new](https://user-images.githubusercontent.com/60231630/138578615-25fb0494-a280-474a-8c70-31db45ed35ce.png)


* Finally, with regard to school type (District or Charter), removal of the ninth grade data has no effect on the final results in terms of overall average reading and math scores and the passing percentages in both of these metrics.  
     Original school type results:    
     ![school_type_old](https://user-images.githubusercontent.com/60231630/138578597-8deafdcc-6a6f-42dd-bdf1-710ff0b2109e.png)  
     School type results after removal of Thomas High School ninth grade data:  
     ![school_type_new](https://user-images.githubusercontent.com/60231630/138578601-23c16505-0d8b-4ac2-bbc1-65682b371cd0.png)



## Summary of changes to results
In terms of the district summary, the most notables changes when ninth grade scores are replaced include a decrease in average reading scores by two-tenths of a percent, a decrease in the percentage of passing math scores by three-tenths of a percent and a tenth of a percent decrease in the percentages of students that earned passing scores in both categories. The other notable change is observed in the school summary results, where removal of the ninth grade data resulted in a decrease in average reading and math scores and the percentage of passing math, passing reading, and passing of both reading and math scores by a couple of tenths of a percent in most cases. In summary however, the overall data is largely not effected.
