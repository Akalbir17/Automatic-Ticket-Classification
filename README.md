# Automatic-Ticket-Classification

## Problem Statement 
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 

 

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

 

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. <br>
<br>
<br>
You need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.The different products/services are: -
- Credit card / Prepaid card

- Bank account services

- Theft/Dispute reporting

- Mortgages/loans

- Others 
<br>

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.


## Tasks Performed in the Project:
1. Data loading

2. Text preprocessing

3. Exploratory data analysis (EDA)

4. Feature extraction

5. Topic modelling 

6. Model building using supervised learning

7. Model training and evaluation

8. Model inference


## Supervised Models Tested and Results
<table><tr><td class="border_l border_t border_r border_b selected" colspan="1" rowspan="1" style="display: table-cell; text-align: left; font-weight: bold;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="KKsqoLFxeezLIfbGeVuNn"><p><span>Model Name </span></p></div></div></td><td class="border_l border_t border_r border_b selected" colspan="1" rowspan="1" style="display: table-cell; text-align: right; font-weight: bold;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="3nuJ39wsFanJvXUWDuc6K"><p><span>F1 Score in %</span></p></div></div></td><td class="border_l border_t border_r border_b selected" colspan="1" rowspan="1" style="display: table-cell; text-align: right; font-weight: bold;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="AcYigt3_z-mvWySgIgpRC"><p><span>Hyper Parameter Tuned F1 Score in %</span></p></div></div></td></tr><tr><td colspan="1" rowspan="1" style="display: table-cell; text-align: left;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;"><p><span>Logistic Regression </span></p></div></div></td><td colspan="1" rowspan="1" style="display: table-cell; text-align: right;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;"><p><span>91.96</span></p></div></div></td><td colspan="1" rowspan="1" style="display: table-cell; text-align: right;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;"><p><span>94.46</span></p></div></div></td></tr><tr><td colspan="1" rowspan="1" style="display: table-cell; text-align: left;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="BVgpHY-ODQET7iddWozJc"><p><span>Decision Tree Classifier</span></p></div></div></td><td colspan="1" rowspan="1" style="display: table-cell; text-align: right;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;"><p><span>78.50</span></p></div></div></td><td colspan="1" rowspan="1" style="display: table-cell; text-align: right;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;"><p><span>80.43</span></p></div></div></td></tr><tr><td colspan="1" rowspan="1" style="display: table-cell; text-align: left;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;"><p><span>Random Forest</span></p></div></div></td><td colspan="1" rowspan="1" style="display: table-cell; text-align: right;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;"><p><span>81.70</span></p></div></div></td><td colspan="1" rowspan="1" style="display: table-cell; text-align: right;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="rStMrgeEC3-V_fDk_gH0C"><p><span>81.60</span></p></div></div></td></tr><tr><td colspan="1" rowspan="1" style="display: table-cell; text-align: left;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="u2y13RqWb8P83dCkROcuB"><p><span>Naive Bayes</span></p></div></div></td><td colspan="1" rowspan="1" style="display: table-cell; text-align: right;" class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="kL22ZRP2InB1O02_mr5Gs"><p><span>67.75</span></p></div></div></td><td colspan="1" rowspan="1" class="border_l border_t border_r border_b selected" style="display: table-cell; text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="yN9CZZ_D2-Iy4vW56TTeO"><p><span>78.17</span></p></div></div></td></tr><tr><td class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="AkT0rkuKResi35KSxgCoc"><p><span>Support Vector Machine</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="LvwS_iuH77M4xMZ8yWggw"><p><span>91.59</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="DJz6R6gKlvkM8HZvpcL2E"><p><span>91.78</span></p></div></div></td></tr><tr><td class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="GHEXxswXrr4MVwnkVm53t"><p><span>XGBoost</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="E-OxWo28qk5mb5tJQ8U7w"><p><span>89.74</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="09wqyFKIlrWp0yHZ511O0"><p><span>92.16</span></p></div></div></td></tr><tr><td class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="zMrHFJXkdPr_lDisri4uH"><p><span>CatBoost</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="RGO1msGRT42vBknvXqszQ"><p><span>90.81</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="HQ-7mP67tGlNjQxZlOSIw"><p><span>79.34</span></p></div></div></td></tr><tr><td class="border_l border_t border_r border_b selected"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="yGlzesahUKyg6XhAQVrFJ"><p><span>AdaBoost</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="y9tcncKIALYJrrr-o5Y9Y"><p><span>84.52</span></p></div></div></td><td class="border_l border_t border_r border_b selected" style="text-align: right;"><div class="wrap"><div style="margin: 10px 5px;" class="" contenteditable="false" data-gramm="false" wt-ignore-input="true" data-quillbot-element="H2VV0CPXMQECq5W1SryGT"><p><span>78.67</span></p></div></div></td></tr></table>
 
 
 ## Best Model Confusion Matrix
 ![2023-01-19](https://user-images.githubusercontent.com/69676151/213446306-7628dbb9-ad53-4b4d-be1d-7b7686d48085.png)

 
 ## Conclusion
 In this project we were successfully able to predict the different classes based on the complaints recieved from the customers. We performed Text preprocessing,Exploratory data analysis (EDA), Feature extraction and Topic modelling on the data. Later on we applied 8 different types of supervised machine learning models on the data and used F1 score as the evaluation metrics for the models as the class distribution was imbalanced. After model building we understood that `Logistic Regression Model` performed the best with an `F1 score 0.94` with `hyper paramter tuning`. Lastly, we completed the project by using Logistic Regression Model for Model Inference and testing the model on dummy data.

 

