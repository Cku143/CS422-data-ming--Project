### CS422 Data mining Project   
**Depression Integrative Analysis and Prediction for Students**  

**Chengxuan Ku**  


#### Abstract  
Depression among university students is a growing public health concern, with significant impacts on academic performance and physical and mental health.And many students face stress from studies, social life, and daily habits. This project predicts if a student might be depressed using their personal, academic, and lifestyle data.Through developping the machine learning model  on the dataset,our prediction of depression in students has made effective progress.I think in the future, machine learning models can be used to analyze and improve the overall student depression trends in society.With the end of the project,I think in the future, machine learning models can be used to analyze and improve the overall student depression trends in society.  

#### Rationale
Depression among Students at all stages is a growing public health concern, with significant impacts on academic performance and physical and mental health.Early detection will be crucial for effective intervention and can help schools find and support students who may need help.Depression analysis is taken  for research purposes in psychology, education, and data science, with the goal of enabling reliable insights into the predictors of student depression and supporting the development of early intervention strategies.

#### Research Question  
Is it possible to build a machine learning model to accurately predict and judge whether students have depression?And Which behaviors and characteristics of students are closely related to depression?  

#### Data Sources
Data sources from https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset. This dataset compiles a wide range of information aimed at understanding, analyzing, and predicting depression levels among students. It is designed for research in psychology, data science, and education, providing insights into factors that contribute to student mental health challenges.This dataset collects a large amount of data from currently highly concerned populations with depression tendencies.A total of 27901 rows of data, each representing a student, bear information for 18 columns.
- Numerical Feathers: id, Gender, Age, Academic Pressure, Work Pressure, CGPA, Study Satisfaction, Job Satisfaction, Work/Study Hours, Financial Stress.
- Categorical Feathers: City, Profession, Sleep Duration, Dietary Habits, Degree, Have you ever had suicidal thoughts ?, Family History of Mental Illness.  
- **Target Variable**: Depression: Binary (1:Yes,0:No)- Class label.

#### Methodology
**Data Processing** :   
   - Comprehensive Data Cleaning:Remove noise, inconsistencies, duplicates and missing values.  
   - Created Data visulizations:Intuitively analyze data.   
   - Data Transformation and Feature Engineering:Simplify data and convert the categorical data into numerical labels,Create meaningful features,Scale and balance the data.     

**Develop Model**:
   - Model Implementation:Created three models:Logistic Regression,Random Forest and Gradient Boosting.Finally choose the best model--Gradient Boosting.   
   - Hyperparameter Tuning:Use the Sequential Grid Search method for parameter optimization.   
   - Model Evaluation:Use confusion matrix,ROC curve and PR curve.   

#### Results
The hyperparameter tuned Gradient Boosting model achieves an accuracy of 87%, with strong recall of 88% for class depression.It indicates effective identification of depression cases.Therefore, this model has obvious significance for predicting students' depression.What's more,the feather of Suicidal Thoughts is closely related to target variable depression.Financial Stress can also be considered as a main feature.Secondary features include Relative stress..In conclusion,the model we created has excellent performance and can provide effective help in predicting students' depression.

#### Next steps
- Collaborate to refine input features based on clinical relevance and ensure diagnostic labels (ground truth) are accurate and consistent. Discuss the limitations of the labels used.
- Define Clinical Utility: Make actively discuss such as How could this model realistically be used? (e.g., screening tool, risk stratification, monitoring symptom change, informing treatment selection). Define clear target use cases.  
- Aims for a tool (e.g., screening app, clinician decision support), design a small-scale pilot study in a realistic setting. Observe how clinicians or patients interact with it, assess usability, workflow integration, and gather qualitative feedback.   

#### Conclusion
The Gradient Boosting model can accurately identify samples of the target class with minimal misclassification of other classes as the target class.Overall,the model efficiently and accurately classifies the class of Depression.And the model we created has excellent performance and can provide effective help in predicting students' depression.Our model has effective identification of depression cases.Therefore, this model has obvious significance for predicting students' depression.

### Bibliography 
- [1] P. -N. Tan, M. Steinbach, A. Karpatne, and V. Kumar. Introduction to Data Mining, 2nd edition. Pearson, 2019.
- [2] C. C. Aggarwal. Outlier Analysis, 2nd edition. Springer, 2017
- [3] Lundberg, S. M., & Lee, S. I. (2017). A unified approach to interpreting model predictions. *Advances in neural information processing systems*, 30.  
- [4] F. Pedregosa et al., "Scikit-learn: Machine learning in Python," *J. Mach. Learn. Res.*, vol. 12, pp. 2825-2830, 2011.
- [5] I. H. Witten, E. Frank, M. A. Hall, and C. J. Pal. Data Mining: Practical Machine Learning Tools and Techniques, 4th edition. Morgan Kaufmann Publishers, 2017.
- [6] J. Grus. Data Science from Scratch: First Principles with Python, 2nd edition. O'Reilly Media, 2019.
- [7] L. Breiman, "Random forests," *Mach. Learn.*, vol. 45, no. 1, pp. 5-32, Oct. 2001.
- [8] J. Han, M. Kamber, and J. Pei. Data Mining: Concepts and Techniques, 3rd edition. Morgan Kaufmann Publishers, 2012.


##### Contact and Further Information
For questions , please contact: kuchengxuan0606@hotmail.com
