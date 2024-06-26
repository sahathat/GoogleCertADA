# Case scenario: Working for Salifort Motors - Created by 29/12/66​

## Overview 
- Plan to keep dataset
- Plan to use dataset for clean, group and transform to feature 
- EDA and Classification with model assumption and result report
- Hypothesis testing
- Feature engineering

## Classification Method
- Using grid search to find most optmized ways to make accurate predict data
- Logistic Regression
- Decision Tree (XGBoost)
- Random Forest Tree (XGBoost)
- Neural network (Tensorflow)

## Feature selection
- Before Engineering: ['satisfaction_level', 'last_evaluation', 'number_project','average_monthly_hours', 'time_spend_company', 'promotion_last_5_years']
- After Engineering: ['last_evaluation', 'number_project','overworked', 'time_spend_company', 'promotion_last_5_years']

## Summary
- Cause of employee left had number of project has the most following last evaluation time, time spending company and overwork respectively.
- The most of employee has working more than 8 hours per day or 166.67 hours per month that mean they have more overworked specially their number projects. Make it caused for exiting on company.
- HR need to controlled number project for employee working must on cap like no more than 6 projects per employees.
- HR need to recruit new employee, train with upskill and development for support their recent work so reduce their time and cost to use and evaluation with fair score point not bias with lower projects number with lower score and high projects number with high score included protect satisfaction of each employees and reduce their overwork.

Tableau dashboard:
Dashboard: [Why employee left at the most in Salifort company?](https://public.tableau.com/views/Whysalifortemployeeleavefromcompany/WhyemployeeleftinSalifortCompany?:language=th-TH&:display_count=n&:origin=viz_share_link)

Presentation: 
[canva slide](https://www.canva.com/design/DAF4Vr3sDSE/2yT3GEzLJEBsekQepAm6jw/edit?utm_content=DAF4Vr3sDSE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
[Tableau Presentation-20231217_190656-Meeting Recording.mp4 (sharepoint.com)](https://mailkmuttacth.sharepoint.com/sites/Test113721/_layouts/15/stream.aspx?id=%2Fsites%2FTest113721%2FShared%20Documents%2FGeneral%2FRecordings%2FTableau%20Presentation%2D20231217%5F190656%2DMeeting%20Recording%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)
