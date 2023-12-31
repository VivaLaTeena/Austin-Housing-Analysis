# AUSTIN HOME VALUE FACTORS
<hr>
In this project we used historical home value prices from zillow and population zip code data to determine which population factors have the largest affect on home prices.

## [Presentation] ([./demographics_vs_housing_prices__1_ (3).pptx](https://github.com/VivaLaTeena/project/blob/main/demographics_vs_housing_prices__1_%20(3).pptx))

## [Jupyter Notebook] ([./valuations.ipynb](https://github.com/VivaLaTeena/project/blob/main/valuations.ipynb))

In this read me we will begin with a guide for the repository and then our analysis bewow: 

## To Clone Repo, Installing Dependencies & Run Jupyter

$ git clone https://github.com/VivaLaTeena/Austin-Housing-Analysis.git   

$ cd project   

$ conda install pandas   

$ jupyter lab

## Repository Contents

Our presentation and main code from our jupyter notebook are listed above.

#### [Outputs] (https://github.com/VivaLaTeena/project/tree/main/Outputs)
The Outputs folder contains captured images from each of the plots created within out notebook for easier veiwing.

#### [Resources] (https://github.com/VivaLaTeena/project/tree/main/Resources)
Next within the reasources folder we have 8 files. 5 of these are saved dataframes outputted as csv files from our api for each zip code in our project. The other 3 files are csv files from Zillow for the market values we required in different ways.

When running our code for testing purposes pleas note the api and api key are set up in the main code not on a secondary sheet. This code is linked to an account from a memeber of our group but it is their direct key so should provide no issues. All files paths are realitive and set up to read in or output directly from the reasources folder when cloned properly. Now please see below for our analaysis.

## Hypothesis: Our analysis will reveal that the variables of Education, Income, and Ethnicity have a significant impact on housing prices in the 5 selected zip codes within the Austin city limits.

## ANALYSIS

What Factors Most Impact Housing Value?

We explored the data for five zip codes in Austin, TX (78724 78729 78733 78741 78744), and analyzed how demographic factors, median household income, ethnicity distribution, and education level distribution impact the average housing value in these areas. Understanding these relationships assisted in identifying key drivers that influence housing prices in Austin, TX. 


Zip Code Key Findings

Zip Code 78748 has the highest population and median household income but offers relatively lower housing values compared to other areas.
Zip Code 78741 has the lowest median household income and relatively higher crime rates, making it a more affordable option for buyers on a budget.
 Zip Code 78733 has the highest median household income and housing values, making it an upscale neighborhood with fewer affordability options.
Zip Code 78729 provides a balanced combination of moderate population, income, housing values, and education levels, making it an attractive option for buyers seeking diversity and affordability.
 Zip Code 78724 offers more affordable housing options but has a higher crime rate, which buyers should consider in their decision making process.


## Conclusion:
 
Based on the analysis of the five selected zip codes within the Austin city limits, our findings support the hypothesis that the variables of Education, Income, and Ethnicity have a significant impact on housing prices in these areas.

Conclusions:

1. Education Level Impact: Zip codes with a higher percentage of residents holding Bachelor's or Master's degrees tend to have higher average housing values. This suggests that a higher level of education in a community may be associated with increased demand for higher-priced housing.

2. Income Impact: Zip codes with higher median household incomes generally exhibit higher average housing values. Higher income levels can enable residents to afford more expensive homes, contributing to the positive correlation between income and housing prices.

3. Ethnicity Distribution: Ethnicity distribution appears to influence housing prices, with zip codes having a higher percentage of White and Asian residents showing higher housing values. In contrast, areas with a higher percentage of Hispanic and Black residents tend to have relatively lower average housing values.

4. Zip Code Disparity: The analysis reveals significant disparities in average housing values among the five zip codes. Zip codes 78733 and 78748 stand out as areas with the highest average housing values, while 78724 and 78741 have comparatively lower average housing values.

5. Affordability: Zip code 78724 emerges as the most affordable option for homebuyers due to its lower average housing values. This area may be attractive for individuals or families seeking more affordable housing options.

6. Diversity and Housing Prices: Zip code 78748 exhibits the most diverse population in terms of ethnicity, with a mix of White, Hispanic, Black, and Asian residents. Interestingly, this area also has relatively high average housing values, indicating that diversity does not necessarily lead to lower housing prices.

7. Considerations: While our analysis indicates significant impacts of Education, Income, and Ethnicity on housing prices, it is essential to consider other factors such as location, amenities, and local economic conditions that can also influence housing values.

In summary, the analysis supports the hypothesis that Education, Income, and Ethnicity are important factors contributing to variations in housing prices among the selected zip codes in Austin, TX. The insights gained from this study can assist policymakers, investors, and homebuyers in making informed decisions about housing investments and understanding the dynamics of the real estate market in these areas.

>>>>>>> c2a80d5b55647cbcfd8e6ebc343e53f851ceda90
