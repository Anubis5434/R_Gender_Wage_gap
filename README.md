# R_Gender_Wage_gap
This is an empirical research report on gender wage gap on data from NLSY79 (National Longitudinal Survey of Youth, 1979 cohort).
Data set description:

This dataset contains lots of historical data, to be specific, we want to study on a cross sectional dataset of year 2012, so we are including some variables from 2012 survey mainly, and basic information of subjects such as race, gender in historical survey (which remain stable for each subjects). We will name our subdataset as `gwgap`(stands for "gender wage gap").  

Below are the selected variables and brief description:  

`income`: total income from wage and salary in 2012  
`gender`: gender, Male/Female  
`race`: racial group, Hispanic/Black/Non-black  
`educ_year`: education years, continus variable of highest grade completed  
`region`: rigion of residence  
`num_job`: Number of jobs ever reported at interview date  
`urban`: urban or rural residence  
`industry`: recoded based on 


## Discussion

Overall, we can draw the conclusion that gender wage gap is almost universal (when comparing man and women in same condition), at least for the factors we included in the model. 

Another fact is there are many factors that can have interact or overlapping effect on gender wage gap, some of the mechanism we do know the reason, for some other, like the one we explored in the report "`industry`", the reasons of the significance of the interaction term needs further more research on.

I have like 70% confidence on my analysis, one most important deduction is that we didn't include possibily most powerful factor, which is job-realted experience or capacity level, that influences income. And the regression model itself can also be potentially improved by adding or replacing some varibles or interaction terms. What's more, as we mentioned before, non-linear pattern of the effect of education can be a potential weak point of the analysis. 


