# 🏃‍♀️ Kaggle Competition : Jigsaw Rate Severity of Toxic Comments
comments의 독성 순위를 매겨 pairs of comments 중 more toxic한 것을 선택하는 문제      
[competition rink](https://www.kaggle.com/competitions/jigsaw-toxic-severity-rating/overview)    

Kaggle code의 [Jigsaw Stater](https://www.kaggle.com/code/debarshichanda/pytorch-w-b-jigsaw-starter) 코드를 베이스라인으로 선정하였다.

## Preprocesisng
```Ruddit dataset``` 추가 데이터셋으로 이용.

## Model
2개의 roberta-base 모델이 각각 less/more toxic comments의 toxic score를 예측.

## Result
- public score : 0.90312

여러 데이터셋 조합을 고려하여 실험을 진행하였다.       
best CV, best LB를 submission으로 택하는 것이 무난한 것 같다.
Trust your CV,,
