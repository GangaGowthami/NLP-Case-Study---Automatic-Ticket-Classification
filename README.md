# NLP-Case-Study---Automatic-Ticket-Classification
For a financial company, customer complaints are crucial as they provide insights into the shortcomings of their products and services. Resolving complaints efficiently and on time can reduce customer dissatisfaction and strengthen their loyalty. Additionally, it allows companies to continuously improve their services to attract more customers.

However, evaluating and assigning each customer support ticket to the relevant department can become a tedious task, especially as the company grows and has a large customer base. This is where natural language processing (NLP) and machine learning (ML) can come to the rescue.

This project aims to automate the customer support ticket system of a financial company using NLP and ML techniques. The goal is to accurately identify and categorize support tickets based on their content and assign them to the relevant team for swift resolution.

# Problem Statement
You need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and therefore, help in the quick resolution of the issue.

You will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.

# Solution
To automate the customer support ticket system, we will use NLP techniques to process and analyze the text data. We will apply ML algorithms to classify support tickets based on their content and assign them to the relevant team. The ML component of this project utilizes a powerful algorithm that predicts the ticket's category based on the content of the ticket, achieving high accuracy rates.

# Features
- Automatic ticket classification using NLP and ML algorithms
- Accurate identification and categorization of support tickets
- Efficient assignment of support tickets to the relevant team for swift resolution
- Comprehensive documentation and step-by-step guide for using and integrating the system with existing support workflows
- Open-source codebase for customization and enhancement of the system to fit specific needs.

# Model Evaluation Metrics
       Models           Training Accuracy	  Test Accuracy
- Logistic Regression	    0.964503	    0.940964
- Decision Tree Classifier	    0.858960	    0.790243
- Random Forest Classifier	    0.866679	    0.846811

- We can infer that a standard logistic regression model is able to perform the best for our use case. There is also no major overfitting that we should be concerned about.
- We can test the results using custom texts next to check the performance of the model.

# Conclusion
- This concludes this exercise of trying to automatically classify tickets(complaints) in the banking sector.
- A reasonably good model has been obtained which is able to predict the appropriate category of the ticket as required.

# Contact
Created by [@GowthamiGanga] - feel free to contact me!
