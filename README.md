# Titanic

**Introduction:**
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.  One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

**Objective:**<br/>
Challenge is to apply the tools of machine learning to predict which passengers survived the tragedy.

**Business objectives and Constraints:**<br/>
1. Latency : Not required <br/>
2. Interpretability :  It is good to have an uderstanding behind the passengers survival<br/>

**Data:**<br/>
Taken data from : https://www.kaggle.com/c/titanic/data  

**Summary:**


|        Model        | Hyper_parameter |    Train score     |     Test score     |
|---|---|---|---|
|         KNN         |        17       | 0.7399678972712681 | 0.7052238805970149 |
|     Naive bayes     |       100       | 0.680577849117175  | 0.7052238805970149 |
| Logistic Regression |        10       | 0.7961476725521669 | 0.8059701492537313 |
|         SVM         |       0.01      | 0.7752808988764045 | 0.8022388059701493 |
|    Decision Tree    |        5        |  0.85553772070626  | 0.7947761194029851 |
|    Random Forest    |     [100, 5]    | 0.869983948635634  | 0.8134328358208955 |
|         XGB         |     [50, 5]     | 0.8972712680577849 | 0.7910447761194029 |
|         MLP         |                 | 0.6175802928298267 | 0.7126865662745575 |
