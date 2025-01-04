# Predict_EV
*DACON HACKATHON* - [CHALLENGE LINK](https://dacon.io/competitions/official/236424/overview/description)  
데이콘 "전기차 가격 예측 해커톤"에 참여한 내용을 기록합니다.

# DATA
### 데이터 수
- 전체 : 7497
- 결측치 : 2711 (모두 배터리 용량에서 나타남)
### 데이터 컬럼 수
- 전체 데이터 : 11
- 연속형 데이터 : 3 (타겟 포함) -> '배터리용량' '주행거리(km)' '가격(백만원)'
- 범주형 데이터 : 9 -> 'ID' '제조사' '모델' '차량상태' '구동방식' '보증기간(년)' '사고이력' '연식(년)'
### 범주형 변수 고유값
- 제조사의 고유값 (수:7) -> ['P사' 'K사' 'A사' 'B사' 'H사' 'T사' 'V사']
- 모델의 고유값 (수:21) -> ['TayGTS' 'Niro' 'eT' 'RSeTGT' 'i5' 'ION6' 'MS' 'MY' 'Q4eT' 'ID4' 'TayCT'
 'Soul' 'iX' 'MX' 'IONIQ' 'EV6' 'KNE' 'M3' 'i3' 'ION5' 'Tay']
- 차량상태의 고유값 (수:3) -> ['Nearly New' 'Brand New' 'Pre-Owned']
- 구동방식의 고유값 (수:3) -> ['AWD' 'FWD' 'RWD']
- 보증기간(년)의 고유값 (수:11) -> [ 0  6  7  3  1  5  8 10  2  4  9]
- 사고이력의 고유값 (수:2) -> ['No' 'Yes']
- 연식(년)의 고유값 (수:3) -> [2 0 1]