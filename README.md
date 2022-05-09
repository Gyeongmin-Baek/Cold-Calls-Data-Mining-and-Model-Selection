# Cold-Calls-Data-Mining-and-Model-Selection
- 데이터 셋은 캐글 https://www.kaggle.com/kondla/carinsurance 입니다.
- 백경민(bkmin0215@naver.com), 송민성(songmile512@gmail.com), 최민호(hont1027@gmail.com), 우영목(wyminerva96@gmail.com), 심우빈(dnqls224@gmail.com)이 함께 하였습니다.

## Project

- 모델은 XGBoost, LGBM을 사용하였습니다.

- 차원 축소(PCA), 정규화도 추가로 고려하였습니다.

- 개별 변수를 이해하여 이상치를 적절히 처리하였습니다.

- 결측치에 대해 단순히 최빈값으로 대체하거나 샘플을 제거하는 대신 변수간 관계를 통해서 결측치를 대체 (Education과 Job의 관계, Outcome 결측치의 이해) 하였습니다.

- 시간과 관련된 변수에 대해 적절한 가정(2016년 데이터)을 통하여 변수를 가공하였습니다.

- 모델 학습 시 필요 없는 변수를 제거 : Communication (유/무선 전화 응답 여부)
