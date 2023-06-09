## 실습 내용

||Day1|Day2|Day3|
|---|----|----|----|
|주제|스프링 내구력 테스트 통과/실패 예측|최대수요전력 예측|세탁 지수 예측|
|출제<br/>영역|**결측치 처리**<br/>> 반복적 결측치 처리<br/>**비율 검정**<br/>> 베르눌리 분포,  정규 분포<br/>**속성 선택**<br/>> 필터법, 전진선택법<br/>**가설 검정**<br/>> Jarque-bera, Bartlett, 일원산 분산분석<br/>**지도학습**<br/>> 로지스틱 회귀, 랜덤 포레스트, LDA<br/>**비지도학습**<br/>> PCA<br/>**하이퍼 파라미터 최적화**<br/>> 그리드 서치|**데이터 전처리**<br/>> Join, 표준화, 일자(date) 형식 처리, shifting<br/>**데이터 추출**<br/>> GroupBy, …<br/>**가설 검정**<br/>> Shapiro-Wilks, Bartlett, T,<br/>일원산 분산분석, Mann-Whiteny U<br/>Chi2 독립성 검정, 이원산 분산분석<br/>**지도학습**<br/>> 결정트리, SVM, MLP<br/>**비지도학습**<br/>> PCA, DBSCAN <br/>**이상치 탐색**<br/>> Isolation Forest, Local Outlier Factor|**데이터 전처리**<br/>> 치환, 문자열 결합, 표준화, 구간범주화, 가변수화<br/>**가설 검정**<br/>> Komogolov-Smironov, Bartlett, 일원산 분산분석<br/>**확률 통계**<br/>> 정규분포<br/>**지도학습**<br/>> Linear Regression, xgboost<br/>**비지도학습**<br/>> Agglomerative Clustering, PCA<br/>**하이퍼 파라미터 최적화**<br/>**Oversampling**|

## 강의 시간표

|구분|강의 내용|시작|끝|
|----|---------|----|--|
|0|전처리|8시 30분| 9시 30분|
|1|문제 1|9시 40분| 10시 40분|
|2|문제 2|10시 50분| 11시 50분|
|3-1|문제 3|12시 00분| 12시 20분|
|3-2|문제 3|13시 30분| 14시 10분|
|4|문제4|14시 20분| 15시 20분|
|5|문제5|15시 30분| 16시 30분|
|6|문제6|16시 40분| 17시 30분|

## 사전 배포 문항 수정 사항

```
Day2 문항
2번 ) 
단계 2-6 문제 수정: 
        오전/오후에 따라 Avg를 구분하여 Mann-Whiteny U 검정을 하라. 검정 결과 검정통계량을 E값으로 한다.
3번 ) 
단계 3-3: prob4_test -> prob3_test
단계 3-4: prob4_train -> prob3_train, prob4_test -> prob3_test
문제 정답: 76.139

4번)
단계 4-5: learing_rate_init->learning_rate_init

5번)
단계 5-4: 비복원 추출 -> bootstrapping

```
