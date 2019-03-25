### Project Description

This project is aimed to build a model which approximately predicts how much people can borrow. It could be a simple application that one will be asked some questions, such as annual income, house ownership, purpose of the loan,  and then he will know an estimate amount of the loan that he can get. The idea is that anyone can have an idea about how much they can borrow just by answering some questions online instead of going to the bank and talking to some specialists. 

The data set is downloaded from Lending Club, which is a peer to peer lending company. The file contains the complete information of loans, including the current status , and information about borrowers, such as annual income, employment length, and so on. The loan data I downloaded contains all loans issued in Lending Club through 2007 to 2011. There are total 42,542 loans and each one has 145 features. 115 out of those are numeric values and 30 are categorical. I have some data cleaning and exploration done firstly. When training the model, I choose to use the Random Forest Regression algorithm. I also apply quadratic feature transformation, cross validation, and hyperparameter tuning to improve the model in this project.

### Approaches:

Features Transformation --- Quadratic Features Transform
Regression Algorithm -- Random Forest Regression
Cross Validation
Hyperparameter Tuning
