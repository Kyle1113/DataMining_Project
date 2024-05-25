# Seoul Senior Welfare Center Analysis Project for Event Hosting

## DataMining Team Project 4team

## 행사 주최를 위한 서울시 노인복지센터 분석 프로젝트

---

## Summary
- 서울시에 존재하는 동마다의 인구 밀도 및 노인 밀도 등의 인구 통계학적 데이터를 기반하여 경로당의 설립장소 추천
- 경로당이 존재하는 동에 통계학적 데이터를 기반하여 어떠한 행사를 주최하는 가에 대한 분석

## Data PreProcessing
### 데이터 수집 및 분석
1. **서울시 주민등록인구 (연령별/동별) 통계**  
   *https://data.seoul.go.kr/dataList/10727/S/2/datasetView.do*
2. **서울시 독거노인 현황 (연령별/동별) 통계**  
   *https://data.seoul.go.kr/dataList/10176/S/2/datasetView.do*
3. **서울시 장애인 현황 (연령별/동별) 통계**  
   *https://data.seoul.go.kr/dataList/10580/S/2/datasetView.do*
4. **서울시 경로당 정보**  
   *https://data.seoul.go.kr/dataList/OA-15052/S/1/datasetView.do*
5. **서울시 국민기초생활 수급자 동별 현황**  
    *https://data.seoul.go.kr/dataList/OA-22227/F/1/datasetView.do*

*Data Source: [서울 열린데이터광장](https://data.seoul.go.kr/)*

### 데이터 전처리
1. 결측치 제거 및 필요하지 않는 Feature 제거
2. 데이터의 각 행의 내용 정렬 및 일치작업
3. 전체 데이터에 필요한 Feature 확인
4. 경로당이 존재하는 동의 Feature 생성
5. 모든 동의 Feature 생성

### 시각화(EDA) - 서울시 동별

### 모델링

#### K-means Clustering

###### PCA

###### Silhouette 계수

### 시각화(EDA) - 경로당 존재 동별
