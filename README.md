# 서울시 공공 와이파이 위치 데이터 기반 서비스 분석 및 시각화

###### 서울시 공공와이파이 서비스 위치 정보
https://data.seoul.go.kr/dataList/OA-20883/S/1/datasetView.do 

###### 서울시 실시간 인구데이터
https://data.seoul.go.kr/dataList/OA-21778/A/1/datasetView.do 

###### 대한민국 행정구역 공간정보 파일
https://github.com/cubensys/Korea_District/tree/master 


### 서울시 공공와이파이 서비스 위치 정보.csv 데이터를 HeatMap(히트맵) 방식으로 시각화
<img width="1492" height="714" alt="heatmap" src="https://github.com/user-attachments/assets/262421e1-fe06-41a5-8caa-a2832ab55595" />

### 자치구별 생활인구 데이터를 HeatMap(히트맵) 형식으로 시각화
<img width="1144" height="714" alt="image" src="https://github.com/user-attachments/assets/a8c39745-47c5-49b4-86c3-63f66119ef67" />

### 현재 설치되어있는 공용와이파이 현황을 시각화.
<img width="941" height="787" alt="image" src="https://github.com/user-attachments/assets/2b04cbc2-bca7-4ab3-bce8-75aac6197da1" />
와이파이(Wi-Fi)의 최대 커버리지 거리는 약 200m 정도이며, 실내 환경에서는 40m 이내로 줄어들 수 있습니다. 실외에서는 개방된 공간에서 약 200m, 실내에서는 벽이나 장애물로 인해 신호가 약해지므로 40m 이내를 정상적인 서비스 범위로 볼 수 있습니다.


### 와이파이기기 설치가 필요한 지역 시각화
<img width="816" height="757" alt="image" src="https://github.com/user-attachments/assets/b62f2dca-b204-469a-b8a5-8d4e2d73b5a6" />
자치구 경계 내부에서 공공와이파이 커버리지(200m)가 닿지 않는 영역만 찾아
해당 지점에 200m 반경의 빨간원(격자 기반 후보지)를 생성한다.
단, 파란원의 커버리지 범위와 겹치는 위치는 빨간원을 생성하지 않는다.
