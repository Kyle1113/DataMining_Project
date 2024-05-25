# Analysis Project for Hosting Events in Neighborhoods with Senior Centers

Techniques, applications, and practices for analyzing the data from diverse sources to plan and optimize event hosting in neighborhoods with senior centers.

## Project-Team 
This is a team project aimed at analyzing demographic and social data to facilitate optimal event planning in neighborhoods with senior centers in Seoul.

### Team members and Roles

- **Soyeon Kim**: Modeling and develop clustering algorithm
- **Yechan Lee**: Data preprocessing and data analysis process
- **Gijun Kim**: Data and feature visualization

---

## 1. Topic Description
The main goal of this project is to determine how to host events for seniors based on demographic data in neighborhoods with senior centers. This goal also includes recommending suitable neighborhoods for hosting such events.

---

## 2. Problem Definition
With an aging population and increasing need for social engagement among senior citizens, it's crucial to identify neighborhoods where events for seniors can have the most impact. The challenge lies in leveraging demographic data to pinpoint these areas and ensure events are planned in a way that maximizes accessibility and participation.

### Challenges:
- Identifying neighborhoods with a significant population of senior citizens.
- Ensuring accessibility for seniors, including those with disabilities.
- Balancing event locations to cover different regions of the city efficiently.

---

## 3. Purpose of the Analysis

### 1) Purpose:
**Neighborhood Identification**: The primary objective is to analyze and recommend neighborhoods for hosting senior events. This involves considering various demographic factors like age distribution, number of senior citizens living alone, and the presence of senior centers.

**Event Planning Optimization**: The secondary goal is to develop an efficient plan for hosting events in these identified neighborhoods, ensuring maximum turnout and engagement.

### 2) Expected Outcomes:
- **Optimal Neighborhoods**: Provide a comprehensive list of neighborhoods ideal for hosting senior events, based on demographic analysis.
- **Efficient Event Plans**: Develop plans that detail how and where to host events for seniors, maximizing accessibility and participation.

### 3) Constraints:
- **Data Sources**: Data obtained from public datasets available on the Seoul Open Data Plaza.
- **Time**: The scope of the data is limited to the Seoul area to ensure project feasibility within a given timeframe.

---

## 4. Main Datasets

1. **서울시 주민등록인구 (연령별/동별) 통계**
   (https://data.seoul.go.kr/dataList/10727/S/2/datasetView.do)
3. **서울시 독거노인 현황 (연령별/동별) 통계**
   (https://data.seoul.go.kr/dataList/10176/S/2/datasetView.do)
5. **서울시 장애인 현황 (연령별/동별) 통계**
   (https://data.seoul.go.kr/dataList/10580/S/2/datasetView.do)
7. **서울시 경로당 정보**
   (https://data.seoul.go.kr/dataList/OA-15052/S/1/datasetView.do)
9. **서울시 국민기초생활 수급자 동별 현황**
    (https://data.seoul.go.kr/dataList/OA-22227/F/1/datasetView.do)

*Data Source: [서울 열린데이터광장](https://data.seoul.go.kr/)*

---

## 5. Preprocessing

### 1) Exploratory Data Analysis (EDA):
- Metadata provided by data sources helps understand the context.
- Used statistics and simple plots (distribution, scatter, and box plots) to analyze data.
- Identified key trends such as neighborhoods with higher concentrations of senior citizens and those living alone.

### 2) Feature Selection and Extraction:
- Selected and combined relevant information from the datasets.
- Created new tables combining relevant data points such as the number of elderly, disabled individuals, and senior centers per neighborhood.
- Matched administrative district data with map service APIs for visualization.

### 3) Visualization:
- Visualized spatial data to easily grasp information.
- Used Spotfire and QGIS for creating visual representations of data.
- Highlighted neighborhoods with high concentrations of senior citizens and senior centers.

---

## 6. Model

### 1) K-means Clustering:
- K-means clustering was used to group neighborhoods with similar characteristics.
- Considered factors such as the number of seniors, presence of senior centers, and accessibility.
- Applied StandardScaler to preprocess data and mitigate the impact of outliers.

---

## 7. Project Flow

### 1) Clustering Analysis:
- Conducted clustering using demographic features.
- Identified key neighborhoods within each cluster for potential event hosting.

### 2) Selection of Specific Neighborhoods:
- Considered accessibility and demographic density.
- Used Hansen estimation method to calculate accessibility index for each neighborhood.
- Selected representative neighborhoods from each cluster based on accessibility and demographic data.

### 3) Event Planning and Evaluation:
- Mapped public transportation stops and senior centers.
- Integrated transportation data to ensure accessibility for seniors.
- Prioritized neighborhoods based on accessibility and demographic need.

### 4) Visualization:
- Created maps showing optimal neighborhoods for hosting events.
- Used QGIS to visualize accessibility and demographic distribution.

---

## 8. Conclusion
This project successfully identified key neighborhoods for hosting events aimed at senior citizens. By leveraging demographic data and spatial analysis, we provided insights into optimal event locations that maximize accessibility and engagement. This approach not only enhances the social well-being of seniors but also ensures efficient resource allocation for community events. The outcomes of this project can significantly improve the planning and hosting of events for seniors in Seoul, contributing to better social integration and quality of life for the elderly population.
