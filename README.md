<br>
<br>

# Titanic Survivor Prediction
<br>

![](titanicLogo.jpg)<br><br>
kaggle 의 Signature classfication인 타이타닉 데이터 셋입니다.

# Data analysis process

## Data <br><br> [kaggle - titanic data](https://www.kaggle.com/c/titanic/data)

## Data preprocessing <br>
  Log, SVC model 에 알맞게 전처리를 진행했습니다. 
  
  - Missing value handling
  
    1. Replace with average / Replace with group average
    2. Replace with mode
    3. Leave it alone (because Feature has too many missing values) 

  - Outlier handling 
  
    1. Using quartile 
   
  - Scaling with Standardscaler 
    
  - One-Hot-encoding with Dummies 
 
## Modeling - Logistic Regression, SVC

 - Avoid Overfitting
  
     - Combining features
        1. Famliy size
        2. Ticket Code
        3. Cabin isin
        
     - Feature drop (경험에 기반해 feature 드랍, Mushroom Classfication 에서 Features Selection 학습 예정)
     
     - Cross validation

 - Modeling
