# Titanic-Survivors
## Survival on the Titanic: Who lived and Why?
## Table of Contents
- [Project Overview](project-overview)
- [Data Sources](data-sources)
- [Data Tools](data-tools)
- [Data Cleaning and Preparation](data-cleaning-and-preparation)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis and Findings](data-analysis-and-findings)
- [Key Insights](key-insights)
- [Interpretation](interpretation)
- [Recommendations](recommendation)

## Poject Overview
The sinking of the Titanic, on the April 15th, 1912 remains one of the deadliest maritime disasters in the world history. During her maiden voyage, the “unsinkable” RMS Titanic sank after striking an iceberg, resulting in over 1,500 deaths of passengers and crew on board. While survival depended partly on luck, patterns of investigation suggested that factors, such as gender, age and social class played a vital role in the survival outcomes. This repository provided a detailed analysis about "the sorts of people that survived the Titanic disaster and why”, as well as a better understanding of how social structure dynamics influenced the survival outcome during the shipwreck.

## Data Sources
The dataset used for this project is a Titanic dataset sourced from Kaggle. It contained key attributes, such as passenger class, survival status, gender, and age, that are directly relevant to survival outcome.
### Data Summary
  - Source: Kaggle (The Complete Titanic Dataset)
  - Records: 1,309 passengers
  - Features: 14 variables [Download Here](https://www.kaggle.com/datasets/vinicius150987/titanic3)

## Data Tools
  - Microsoft Excel - Data cleaning and transformation
  - Microsoft Excel - Pivot table, Visualization, and Dashboarding.
  
## Data Cleaning and Preparation: 
- Missing Values: Dataset was checked for blanks, using “COUNTBLANK” function. The age, cabin, boat, body and home.dest columns have 263, 1014, 823, 1188, and 564 missing values respectively. %missing value was then calculated by dividing the missing values by the total number of rows (total number of rows was obtained using “COUNTROW” function. Columns with more than 30% missing values were thereafter dropped to avoid inconsistency.
- Replaced Missing values: Missing age values were replaced with the median age to avoid skewing the data. 
- Text Consistency: Standardized entries in the columns were done using the “TRIM” and “FILTER” functions.
### Data Transformation and Formatting
- Power Query: New fields/columns were created to segment passengers for clearer analysis i.e. 
a. pclass 1, 2, 3 codes into First class, Middle class and Low class respectively
b.	age into 0-9, 10-19, 20-29, 30-39, 40-49, 50-59 etc 
c.	and survived codes 1 and 2, into survived and did not survive respectively. 
- Unwanted Columns:  Columns not needed for the analysis were removed and data for ready for analysis.

  ## Exploratory Data Analysis [EDA]
  
The dataset was explored to provide insights into:
  - The sort of people that survived?
  - How social status and demographics influenced the survival outcome.

## Analysis and Findings

### Survival Status
- Of the 1,309 passengers reported in the dataset, only 500 (representing 38% of the total population on board) survived the shipwreck.
  
### Survival by Gender
- Female passengers had the highest survival rate of 73% (from the 466 population) compared to 19% (from the 843 population) recorded for males.

### Survival by Passenger Class
- 62% (of the 323) passengers in the First-class cabin, followed by 43% (of the 277 passengers) in the middle-class cabin survived. the low-class cabin recorded the  least survival chance of 26% (of the 709 passengers).

  ### Survival by Age-group
- Of the 3 different age groups (193 children, 1083 adults and 33 seniors respectively) on board,children (49%) had the highest survival rate, followed by adults (37%), while the seniors recorded the least survival rate (24%).

  ### Survival Rate by Gender and Class
- Women had the highest survival chance (97%, 89%, and 49%) in the first, middle, and low-class cabin respectively, while 34%, 15% and 15% was respcetively recorded for the men.

  ### Survival Rate by Age Group and Class
- Children had the highest survival rate (86%, 74%, and 35%) across the passengers’ cabins, while the seniors (29%, 17%, and 17% respectively) had the least survival rate.

## Key Insights
- Gender was the strongest predictor of survival: From the analysis, 74% of female passengers survived, compared to just 19% of males. This reflects the “women and children first” policy during evacuation.
- Passengers’ class significantly influenced survival: The first-class passengers had a survival rate of over 60%, while the low (or third-class) passengers had only 24%. Additionally, access to lifeboats and proximity to escape routes accorded passengers in the first-class cabin significant advantage.
- Children had the highest survival rate among the age-groups: This was especially true in the first and middle -class cabins. Prioritization of children during evacuation process/lifeboat boarding likely explains these trends.
- Being male and in lower class cabins significantly reduced survival chances: The findings revealed that male passengers in these sections of the ship had the lowest survival rate of around 15%. 
- Combinations of factors impacted the outcomes. As revealed in the findings, the female passengers in the first-class cabin had a 97% survival rate, whereas male passengers in the third class had less than a 1 in 8 chance of survival. Additionally, younger passengers in the higher classes (first and middle classes) had the best survival outcomes, while senior passengers recorded low survival rates regardless of class.

## Interpretation
- From the insights, it was confirmed that survival on the maiden voyage of the “unsinkable” RMS Titanic ship was not random, rather it significantly depended on gender, age, and passengers’ class. This highlighted the real-world consequences of social structure and human decision-making in life-or-death situations. The findings did not only provide answers to "the sorts of people that survived the Titanic disaster and why” but also offered a clear insight into the factors that influenced the survival outcomes.

## Recommendation
Based on the findings of this analysis, it is recommended that:
- Emergency planning should prioritize fairness and equity for all passenger classes: The analysis showed that the low (or third) class passengers had the lowest survival rate owing to limited access to evacuation route and lifeboats. In real-world cruise settings, equal access to evacuation routes and safety equipment for all passenger classes must be ensured. Future ship structural layout should support efficient evacuation for all passengers, and she be tested for evacuation fairness in crisis simulations.
- Structured evacuation protocols based on vulnerability, and not social class should be implemented: The high survival rates recorded for women and children was based on informal social norms, and not structured policy. Future emergency response plans should be policy-driven, prioritizing the most vulnerable groups, including children, elderly, and the disabled across all the ship compartments. 
- Clear signage and communication should be ensured for all passenger groups: The insight from the analysis suggested that passengers in the third-class were at the disadvantage due to unfamiliarity and poor access to the ship layout. Safety protocols, including multi-lingual signage, accessible maps, and clear public announcements should be provided during emergencies.

  ## Conclusion
This project set out to answer a key question: “What sorts of people survived the Titanic disaster and why” using a complete Titanic dataset downloaded from Kaggle and analysed in Microsoft Excel. The survival outcome from the shipwreck was examined based on gender, age, and passenger class. 
Through data cleaning, exploratory analysis, and visualization, clear patterns were identified as follows: 
- Women and children had significantly higher survival rates.
- Passengers in the first-class survived more than those in lower classes.
- Men in lower-class decks had the lowest survival rate.
The findings confirmed that the survival on the Titanic was influenced by a combination of social status and demographic factors, and not a random chance. The project objective was fully met, and the analysis provided evidence-backed insights into how survival on the Titanic was shaped by social structures and human decision-making. It highlighted the real-world value of data analysis in understanding human behaviour during crises, and the need for equity in safety planning. 

  





    
  


  












