# LLM - Detect AI Generated Text
[Kaggle Competition](https://www.kaggle.com/competitions/llm-detect-ai-generated-text/overview)

AI가 생성한 글인지 사람이 작성한 글인지 판별하는 대회
- Private Score : 0.8637
- Public Score : 0.9315

---
[Baseline Code](https://www.kaggle.com/code/datafan07/train-your-own-tokenizer?scriptVersionId=153008703)  
Word Cloud, Box Plot, Scatter Plot 등을 통해 EDA 분석 및 특징 추출  
TF-IDF vectorize  
GridSearchCV를 통해 최적의 hyperparameter를 탐색  
XGBClassifier + SGDClassifier + LogisticRegression + MultinomialNB 앙상블 모델 사용
- XGBClassifier : eXtreme Gradient Boosting, 결정 트리를 기반으로 하는 Boosting 기법
- SGDClassifier : Stochastic Gradient Decent, 손실 함수의 기울기가 최소가 되는 지점을 찾아냄
- LogisticRegression : 데이터를 선형적으로 구분, 클래스에 속할 확률 예측
- MultinomialNB : Multinomial Naive Bayes, 단어의 빈도수를 기반으로 확률 계산
