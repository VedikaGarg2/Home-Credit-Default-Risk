# Home-Credit-Default-Risk Analysis
This repository contains the Python notebook for home credit default risk analysis.

## Table of Contents
- [Introduction](#introduction)
- - [Business Problem](#business)
- - [Project Objective](#objective)
- [Contribution to the project](#contribution)
- [Group's Solution](#solution)
- [Business Value of the Solution](#businessvalue)
- [Difficulties Encountered](#difficulties)
- [Learning Received](#learning)

## Introduction <a id = "introduction"></a>
For many people with little or no credit history, obtaining credit continues to be a significant obstacle at a time when financial inclusion is essential. Established financial institutions often ignore this unbanked population, which makes them vulnerable to loan sharks. Nonetheless, there is a chance to reduce this and give marginalized communities more power.

### Business Problem <a id = "business"></a>
One of the challenges faced by Home Credit, a worldwide financial company committed to increasing financial inclusion, is reaching out to the unbanked population with its services. Those without a typical credit history are frequently turned down despite being capable of repayment. By utilizing other data sources like telco and transactional data, Home Credit wants to close this gap. However, Home Credit believes there is untapped potential within its existing system, discovering which might simplify the identification of this underserved yet creditworthy group.

### Project Objective <a id = "objective"></a>
The project aims to increase Home Credit's ability to evaluate credit using machine learning and statistical models. We must build a prediction model that identifies potential borrowers who can repay to reduce default risks and maximize acceptance rates. This initiative will ensure that loans are only given to qualified unbanked applicants to advance Home Credit's financial inclusion.

## Contribution to the project <a id = "contribution"></a>
Before EDA, we performed feature engineering by combining historical and current application data to enrich the dataset. This involved integrating variables like the count of previous applications and past credits into the training and testing datasets to enhance the model's predictive accuracy for loan repayment probabilities. Post feature engineering, we transitioned to EDA to extract insights from the data. Following this, we cleaned the data to address missing values and encoded categorical variables.<br>
After data preprocessing, we built models to determine the most effective predictive approach. We developed logistic regression, random forest, and XGBoost models, with the latter demonstrating superior performance, particularly when downsampling was applied.<br><br>
**My contributions to the project**: I carried out feature engineering and was tasked with building the XGBoost model. I tested strategies like downsampling and upsampling to maximize performance. In addition, I also performed cross-validation and did feature importance analysis to identify the primary factors influencing the outcome.

## Group's Solution <a id = "solution"></a>
XGBoost's remarkable performance is crucial to our predictive modeling approach. It is perfect for estimating loan payback probability because of its capacity to handle significant, high-dimensional information and capture nonlinear interactions. In addition, XGBoost's ability to produce interpretable results and resistance to overfitting were essential considerations in our choice. Thus, XGBoost was the best option for improving Home Credit's capacity to evaluate creditworthiness.

## Business Value of the Solution <a id = "businessvalue"></a>
The XGBoost model's accurate creditworthiness assessment provides Home Credit with several benefits. Loan evaluations built by conducting thorough data analysis increase client **loyalty**. It also contributes to Home Credit's reputation by highlighting its **ethical lending practices**. <br>To get the most out of the XGBoost model, Home Credit should incorporate it into its framework for evaluating credit and make significant investments in reliable data infrastructure. Crucial actions like imputation methods for missing values, hyperparameter adjustment, and outlier management should be undertaken by Home Credit to maximize the model's stability. Its effectiveness can be further increased by looking at areas for improvement and adapting to the changing market conditions; this will help promote **long-term growth and customer happiness**.

## Difficulties Encountered <a id = "difficulties"></a>
While experimenting with hyperparameter tuning, our machine overheated and slowed down significantly, making it difficult for us to complete the assignment. We tried to fine-tune the hyperparameters, but the system's computational limitation prevented us from doing so. As a result, we had to give up on this strategy altogether. We learned from this experience how crucial it is to have reliable computer resources to assist in demanding modeling tasks. 

## Learning Received <a id = "learning"></a>
During the project, we learned a few essential things. To begin with, having a powerful computer or using cloud computing is crucial for tasks like hyperparameter tuning. It helps avoid slowdowns and keeps things running smoothly. Additionally, we understood the importance of having the data ready before creating the models. Model performance significantly increases by filling in missing values, organizing data, and selecting the appropriate features. It's also essential to be willing to test various strategies and adjust settings. It makes better outcomes possible and aids in determining what functions best. To conclude, communication and teamwork are essential. All team members' cooperation and input are crucial to accomplish the project's objective.
