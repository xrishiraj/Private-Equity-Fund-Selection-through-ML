# Private-Equity-Fund-Selection-through-ML
This is part of the thesis that I wrote for my Masters.

Abstract:

This paper aims to build a prediction model using machine learning (ML) algorithms to offer decision support for private equity 
investors - limited partners (LPs) in their fund selection process. Past literature has studied a range of factors that appear 
to drive the performance of private equity funds; some of these factors are known to LPs during fundraising such as targeted fund
size, management experience, fund specialization level, state of the industry, and the overall economy. We tap into the predictive
power of these factors by using them to train a range of supervised machine learning models in a binary classification setting that
predicts the probability of a fund exceeding a predetermined performance threshold. We use the Public Market Equivalent measure 
developed by Kaplan and Schoar (2005) to construct our target variable which takes the value 1, if the fund has a PME greater than 
one, and takes the value 0, otherwise. Our models are based on a sample of 1058 Buyout (BO) funds and 659 Venture Capital (VC) funds
sourced from Preqin. Our analysis shows some degree of performance predictability in both VC and BO funds with the top models reaching
an accuracy of 69% for BO funds and 61% for VC funds. We also test the predictions of two of the models, Logistic Regression and Linear
Discriminant Analysis (LDA) against a na¨ıve investment strategy which also showed favorable results. 
