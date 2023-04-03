# 전체 참가 팀 : 728 팀
# Leaderboard: 22 등
# 2차 평가: 8 등

발표 영상 :https://youtu.be/v02lxHB0BEo

비고

- 독립변수에 범주형 변수만 존재할 때, 분류 모형은 catboost의 성능이 뛰어남
- optuna를 통해 하이퍼 파라미터 최적화 가능, GridSearch에 비해 시간적으로 여유로우나 최적값이 아닌 그에 근사한 수치를 제공
- 앙상블 기법을 활용해 여러 모델을 결합하여 유의미한 성능 향상을 기대할 수 있음
- 교차 검증 시 기존 KFold에 비해 train data 분포에 맞게 StratifiedKFold을 활용하면 분류 모형의 성능 향상을 어느정도 기대 가능
- binary classification 시 predictproba를 통해 기존 threshold=0.5 가 아닌 다른 최적 threshold를 적용하며 성능 향상 가능
