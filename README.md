# LLM - Detect AI Generated Text
[Kaggle Competition](https://www.kaggle.com/competitions/llm-detect-ai-generated-text/overview)

AI가 생성한 글인지 사람이 작성한 글인지 판별하는 대회
- Private Score : 0.8637
- Public Score : 0.9315

---
Word Cloud, Box Plot, Scatter Plot 등을 통해 EDA 분석 및 특징 추출  
TF-IDF vectorize  
GridSearchCV를 통해 최적의 hyperparameter를 탐색  
XGBClassifier + SGDClassifier + LogisticRegression + MultinomialNB 앙상블 모델 사용