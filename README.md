# 산불 및 강우 데이터 분석
- 산불 및 강우 데이터 분석을 통해 사용자 편의 도모
- 예측을 통해 산불 위험 홍보 및 등산 준비물 안내

1. 산불 데이터 및 강우 데이터 크롤링 및 open API 호출 통해 데이터 수집
2. EDA 및 데이터 정제 등 데이터 전처리
3. 산불 예측 및 강우 예측을 위한 머신러닝 알고리즘 후보 선정 및 성능비교
4. 최종 모델 선정


### 1-1) 데이터 수집 1 - open api 호출
![image](https://user-images.githubusercontent.com/95295346/168986176-67edcf2d-51ce-44df-9f15-4db40c95f9c1.png "open api 호출함수")

### 1-2) 데이터 수집 2 - 크롤링 (BeautifulSoup)
![image](https://user-images.githubusercontent.com/95295346/168986851-d7171cf3-7d25-4606-aaaa-262b078b2e03.png "산악기상관측시스템 크롤링 후 저장")


### 2-1) 전처리 1 - pySpark  
![image](https://user-images.githubusercontent.com/95295346/168987299-9b93a3a7-642b-4e76-a389-c4f337cebc5d.png "rdd MapReduce")

### 2-2) 전처리 결과
![image](https://user-images.githubusercontent.com/95295346/168987619-86568942-bcba-4f4c-b0f8-763c1148808d.png "결과물")

### 3-1) EDA 1 - 수치형 변수 상관관계
![image](https://user-images.githubusercontent.com/95295346/168988153-1baad59c-779b-49a0-9fdf-8c840815edc8.png "수치형 변수")

### 3-2) EDA 2 - 범주형 변수 상관관계
![image](https://user-images.githubusercontent.com/95295346/168988269-6000d5f2-542d-4784-a3e3-22da2e246854.png "범주형 변수")

### 3-3) EDA 결과
![image](https://user-images.githubusercontent.com/95295346/168987771-4a0b31f9-e814-47af-b135-e068d8dae3c0.png "결과물")

### 4-1) 분류 알고리즘 후보 및 성능비교
![image](https://user-images.githubusercontent.com/95295346/168988533-61274587-378b-45be-b969-8b3514e2ab0a.png)

### 4-2) 결과
![image](https://user-images.githubusercontent.com/95295346/168988613-6ae1ef36-dc13-41f8-86bd-774049a21ed2.png)

