# Project

## Objective
To explore the significance of "self-reported health" as a health indicator. 

## Source of Data
- **Survey Data:**
Import the survey data from the 1999-2000 National Health and Nutrition Examination Survey (NHANES)
```
import sasxport5 "https://wwwn.cdc.gov/Nchs/Nhanes/1999-2000/DEMO.XPT", clear
```
- **Mortality Follow-up Data:**
Obtain follow-up mortality data to analyze over a 20-year period from the National Center for Health Statistics (NCHS). Detailed linkage instructions are available on the Linked Mortality page:
  - Health Statistics
      - NCHS
          - Datalinkage
              - Linked Mortality
                  - &nbsp; <kbd>NHANES_1999_2000_MORT_2019_PUBLIC.dat</kbd> &nbsp;
                  - &nbsp; <kbd>Stata_ReadInProgramAllSurveys.do</kbd> &nbsp;
               
                                  

  ```           
  //data
   global mort_1999_2000 https://ftp.cdc.gov/pub/HEALTH_STATISTICS/NCHS/datalinkage/linked_mortality/NHANES_1999_2000_MORT_2019_PUBLIC.dat

  //code
  cat https://ftp.cdc.gov/pub/HEALTH_STATISTICS/NCHS/datalinkage/linked_mortality/Stata_ReadInProgramAllSurveys.do
  ```
