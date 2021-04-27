# Sales-Performance-Prediction

* 대회: [2020 빅콘테스트](https://www.bigcontest.or.kr/index.php)
* 활동기간: 20/07/20 ~ 20/09/28
* 자세한 내용은 [보고서](https://github.com/SEUNGEUN-1025/Sales-Performance-Prediction/blob/8e24e9cad1fed775e9a8573b6a2af84467a9c6b0/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D_%EC%B1%94%ED%94%BC%EC%96%B8%EB%A6%AC%EA%B7%B8_%EA%B2%B0%EA%B3%BC%EB%B3%B4%EA%B3%A0%EC%84%9C_B526.pdf) 를 확인해주세요.

## ✔️ 분석 문제
- NS SHOP+ 판매실적 예측을 통한 편성 최적화 방안(모형) 도출
- NS Shop+편성데이터(NS홈쇼핑) 를 활용하여 방송편성표에 따른 판매실적을 예측하고, 최적 수익을 고려한 요일별/ 시간대별 / 카테고리별 편성 최적화 방안(모형) 제시

## ✔️ 분석 과정 및 결과
### 1. Data Preprocessing
- 기상 데이터 및 상품 관련 변수 사용
- 상품의 정확한 분류를 위해 대분류-중분류-소분류 따라 새로운 고유코드 부여
- 타겟 매출액: 상품이 한 시간 동안 판매되는 동안의 총 매출액의 누적합
### 2. Modeling
- Boosting Model 사용 (XGBoost, LightGBM)
- 단일모델 및 앙상블 사용
### 3. 최적화 편성 방안
- 요일별, 시간별로 매출액이 가장 높은 상품군 제시
