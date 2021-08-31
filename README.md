# Titanic Survivor Prediction
세계에서 가장 큰 규모의 데이터 분석 커뮤니티인 kaggle 의 대표 분류 예측 문제인 타이타닉 생존자 예측에 관한 코드입니다.

## Data analysis process

### Data collection <br><br> [kaggle - titanic data](https://www.kaggle.com/c/titanic/data)

### Data preprocessing <br>
  Log, SVC model 에 알맞게 전처리를 진행했습니다. 
  
  - Missing value handling
  - Outlier handling 
  - Scaling with Standardscaler
  - One-Hot-encoding with Dummies
 
### Modeling - Logistic Regression, SVC

 - Avoid Overfitting
  * Combining features
  * Feature drop (경험에 기반해 feature 드랍, Mushroom Classfication 에서 Features Selection 학습 예정)
  * Cross validation

