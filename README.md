# AI 기술 구현을 위한 머신러닝 분석 미니프로젝트
## 세종시 무더위 쉼터 최적 위치 선정
🏆 장려상<br>
👨‍💻 팀원: 조용진, 박지태, 서보원, 이다솜<br>
🕑 준비기간: 2022.08.13 ~ 2022.09.25<br>
🖥 분석도구: Python, QGIS

## 1.분석 배경
```
- 최근 3년간 폭염으로 인한 피해는 증가하고 있으며, 특히 미취학 아동 및 노년층에서 빈번하게 발생함
- 코로나 19의 확산으로 이용자 수 감소 및 쉼터 내 코로나 19 감염 가능성으로 미운영 쉼터 수 증가
```
## 2.분석 목표
```
- 폭염에 대한 취약 계층 정의
- 세종시 내 운영되는 무더위 쉼터 현황 분석
- 무더위 쉼터 위치 선정에 영향을 주는 요소 설정
- 영향을 주는 요소를 기반으로 무더위 쉼터가 필요한 지역을 선별
```
## 3. 프로젝트 요약
```
- 폭염에 취약한 계측 정의 -> 피해 사례를 기반으로 65세 이상 고령자를 취약 계측으로 정의
- 상관분석을 통해 사용할 변수 설정
- folium을 활용한 세종시 행정 구역 구분
- QGIS로 세종시 지표면 온도 시각화
- 회귀 분석을 사용하여 쉼터 위치 결정
```
