# SchoolViolence_Analytics  
## - 데이터로 바라본 서울시 학교폭력의 실태와 영향 요인 분석
서울시 공공데이터를 활용하여 학교폭력에 영향을 미치는 외부 요인을 분석한 프로젝트입니다.

### 📋 프로젝트 개요
- **프로젝트 기간**: 2024.07.01 ~ 2024.07.15 (2주)
- **사용 기술**: Python, Jupyter Lab, BigQuery
- **주요 분석 도구**: EDA, 상관계수 분석

### 💡 프로젝트 설명
공공데이터를 기반으로 서울시의 폭력 범죄 데이터를 분석했습니다. 특히 학교폭력에 초점을 맞추어, 학생과 학교를 둘러싼 외부 요인이 학교 폭력 발생에 영향을 미칠 것이라는 가설을 검증해보았습니다.

### 📊 데이터 수집
#### 주요 데이터셋
- 학교폭력 신고 데이터 (스마트치안 빅데이터 플랫폼)
- 학교폭력 유형별 검거현황 (공공데이터포털)
- 서울시 학업중단율 통계 (서울열린데이터광장)
- 서울시 국세징수 통계 (서울열린데이터광장)
- 서울시 공공체육시설 정보 (서울열린데이터광장)
- 서울시 녹지현황 통계 (서울열린데이터광장)
- 서울시 이혼율 통계 (서울열린데이터광장)
- 서울시 고등학교 진학률 데이터 (학교알리미)

#### 분석 기준
- 기준년도: 2021년
- 분석단위: 서울시 행정구별

### 🔍 주요 분석 결과
#### 1. 학교폭력 발생 현황
- 최다 발생 지역: 강서구(79건)
- 최소 발생 지역: 종로구(6건)

#### 2. 영향 요인 분석
다음 4가지 카테고리에서 학교폭력과의 상관관계를 분석:
- 학업성취도 (대학진학률, 학업중단율)
- 경제수준 (소득세, 상속세 등)
- 학교 주변환경 (체육시설, 녹지공간)
- 가정환경 (이혼율)

#### 3. 핵심 발견사항
- 이혼 건수와 학교폭력 발생 간 높은 상관관계(0.91) 발견
- 학생 수와 학교폭력 발생 간 중간 수준의 상관관계(0.51~0.75) 확인
- 경제적 수준이나 학업성취도는 유의미한 상관관계를 보이지 않음

### 🔎 한계점
1. 인과관계 증명의 한계
2. 개인정보 보호로 인한 심층 분석의 제약
3. 갈등 관계의 데이터화 어려움

### 📈 개선 방향
- 개인의 심리상태 관련 데이터 추가 수집 필요
- 가정환경 요인에 대한 더 세분화된 분석 필요
- 시계열 분석을 통한 장기적 추세 파악 필요

### 더 자세한 내용을 알고 싶다면? 
- [📃 Velog에서 자세한 분석 과정 보기](https://velog.io/@peng_data/%ED%95%99%EA%B5%90%ED%8F%AD%EB%A0%A5%EC%97%90-%EC%98%81%ED%96%A5%EC%9D%84-%EB%AF%B8%EC%B9%98%EB%8A%94-%EC%99%B8%EB%B6%80%EC%9A%94%EC%9D%B8%EC%9D%B4-%EC%9E%88%EC%9D%84%EA%B9%8C)
- [📊 프로젝트 전체 발표자료 보기](https://drive.google.com/file/d/1V4Wkqc7T0Depbg1spnSMsPTTFyVxzQx3/view?usp=sharing)
