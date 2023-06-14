# Dacon_contest1
## 데이콘 Basic 자동차 가격 예측 AI 경진대회

Dataset Info.

train.csv [파일]
57920개의 데이터
ID : 샘플 별 고유 id
생산년도 : 차량이 생산된 연도
모델출시년도 : 차량의 모델이 처음으로 출시된 연도
브랜드
차량모델명
판매도시 : 3글자로 인코딩된 도시 이름
판매구역 : 3글자로 인코딩된 구역 이름
주행거리 : 총 주행 거리(km)
배기량 : 내연기관에서 피스톤이 최대로 밀어내거나 빨아들이는 부피 (cc)
압축천연가스(CNG) : 압축천연가스(CNG) 자동차 여부
경유 : 경유 자동차 여부
가솔린 : 가솔린 자동차 여부
하이브리드 : 하이브리드 자동차 여부
액화석유가스(LPG) : 액화석유가스(LPG) 자동차 여부
가격 : 자동차 가격(백만원)
 

test.csv [파일]
14480개의 데이터
ID : 샘플 별 고유 id
생산년도 : 차량이 생산된 연도
모델출시년도 : 차량의 모델이 처음으로 출시된 연도
브랜드
차량모델명
판매도시 : 3글자로 인코딩된 도시 이름
판매구역 : 3글자로 인코딩된 구역 이름
주행거리 : 총 주행 거리(km)
배기량 : 내연기관에서 피스톤이 최대로 밀어내거나 빨아들이는 부피 (cc)
압축천연가스(CNG) : 압축천연가스(CNG) 자동차 여부
경유 : 경유 자동차 여부
가솔린 : 가솔린 자동차 여부
하이브리드 : 하이브리드 자동차 여부
액화석유가스(LPG) : 액화석유가스(LPG) 자동차 여부


sample_submission.csv [제출양식]
ID : 샘플 별 고유 id
가격 : 자동차 가격(백만원)
