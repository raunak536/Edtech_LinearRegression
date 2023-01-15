# Problem Statement
Provide actionable insights to an Inditan edtech company by leveraging the power of machine learning to help their student base know in advance their chances of getting into a particular university based on metrics like GRE, GMAT, Toefl etc 

# Insights
- CGPA is the strongest predictor (weight ~ 0.069) for getting into a university of choice
- SOP and University Rating have a p-value > 5%, showing that these 2 don't have predictive power when it comes to chance of admission
- We built a robust Linear Regression model with following characteristics : 
    - R2 : 0.78
    - Adjusted R2 : 0.77
    - RMSE : 0.06
    - MAE : 0.05
    - Our model meets all underlying assumptions of a linear model

# Recommendations
- A student applying for a particular university should prioritize his application in the following order : CGPA >  GRE > TOEFL > LOR > Research > University Rating > SOP
- To boost performance of its models the edtech should collect additional data such as : 
    - Basic information : Age, Gender, Birth City
    - Education Background : Tier of Undergraduate College, Department
    - Work Background : Number of years of work/internships experience, Previous employees
    - Program information : Early/Late Stage applicant, Batch size, Applied Department, Course vintage 
- If the company deploys an accurate model on their website, this could lead in increase in traffic of students which could be used to generate revenues via: 
    - renting out ad space on the website
    - a subscription model (Rs X per prediction)
    - Provide counselling service to boost chances