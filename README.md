# Data Analysis In Python

데이터 분석 연습을 위한 레포지터리입니다. 

## 전국 민간 아파트 분양가 분석
- [주피터 노트북 보기](https://github.com/DAWUNHAN/DataAnalysisInPython/blob/master/%EC%A0%84%EA%B5%AD%20%EC%95%84%ED%8C%8C%ED%8A%B8%20%EB%B6%84%EC%96%91%20%EA%B0%80%EA%B2%A9%20%EB%B6%84%EC%84%9D%ED%95%98%EA%B8%B0.ipynb)
- 데이터셋은 공공데이터 포럼 (https://www.data.go.kr)
    - 전국 평균 분양가격(2013년 9월부터 2015년 8월까지)
    - 주택도시보증공사_전국 평균 분양가격(2019년 12월)
- 활용 functions
    - concat, pivot, transpose in Pandas
    - groupby, pivot_table, info, describe, value_counts
    - bar plot, line plot, scatter plot, lm plot, 히트맵, 상자수염그림, swarm plot, 도수분포표, 히스토그램 
    
## 상가 정보로 기술 통계 값 보기
- [주피터 노트북 보기](https://github.com/DAWUNHAN/DataAnalysisInPython/blob/master/%EC%83%81%EA%B6%8C%20%EC%A0%95%EB%B3%B4%20%EB%B6%84%EC%84%9D%ED%95%98%EA%B8%B0.ipynb)    
- 데이터 출처 : 공공데이터포털 소상공인 상권정보 상가업소 데이터
- 활용
    - Heatmap, 
    - 기술 통계 : 데이터의 갯수, 평균, 표준편차, 최솟값, 1사분위수(25%), 2사분위수(50%), 3사분위수(75%), 최댓값 등
    - 단변량 수치형 변수 시각화
    - 이변량 수치형 변수 시각화
    - 상관 계수
    - Seaborn을 이용한 데이터 시각화 : bar, scatterplot
    - Folium으로 지도 위에 시각화

## 프랜차이즈 매장 위치 분석 (베스킨라빈스와 던킨도너츠, 파리바게트와 뜌레쥬르)
- [주피터 노트북 보기](https://github.com/DAWUNHAN/DataAnalysisInPython/blob/master/%ED%94%84%EB%9E%9C%EC%B0%A8%EC%9D%B4%EC%A6%88%20%EC%9E%85%EC%A0%90%20%EB%B6%84%EC%84%9D.ipynb)
- 공공데이터 포털 : https://www.data.go.kr/dataset/15012005/fileData.do
- 텍스트 데이터 정제하기
- 문자열에서 특정 텍스트 추출하기 (예시: 베스킨라빈스, 배스킨라빈스, Baskinrobbins 등)
- 문자열을 이용하여 위치 정보 사용하기
- folium을 이용하여 데이터 시각화 하기
- folium CircleMarker와 MarkerCluster 그리기

## 스타벅스와 이디야 매장 위치 상관 관계 분석
- [주피터 노트북 보기](https://github.com/DAWUNHAN/DataAnalysisInPython/blob/master/%EC%8A%A4%ED%83%80%EB%B2%85%EC%8A%A4%20%EC%9D%B4%EB%94%94%EC%95%84%20%EB%A7%A4%EC%9E%A5%20%EC%9C%84%EC%B9%98%20%EB%B6%84%EC%84%9D.ipynb)
- 데이터 출처 : https://www.data.go.kr/dataset/15012005/fileData.do
- 구별로 매장수를 표현하기 위해 GeoJSON 파일 로드
- folium을 이용하여 지도 위에 데이터 시각화 하기
- JSON파일을 로드하여 choropleth 구현하기
- 데이터에 따라 지도 위 다른 색상으로 직관적으로 표현하기
- groupby, pivot_table 등 데이터 전처리 하기

## 전국 도시 공원 데이터 분석
- [주피터 노트북 보기](https://github.com/DAWUNHAN/DataAnalysisInPython/blob/master/%EC%A0%84%EA%B5%AD%20%EB%8F%84%EC%8B%9C%EA%B3%B5%EC%9B%90%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D.ipynb)
- 데이터 출처 : https://www.data.go.kr/dataset/15012890/standard.do
- 워크 클라우드를 이용하여 빈도수 표현하기
- Pandas Profiling을 이용하여 인터렉션 기능 구현하기
- 정규표현식을 활용해서 텍스트 데이터 전처리와 데이터 마스킹 기법 활용.
