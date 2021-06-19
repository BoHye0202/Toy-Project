# 생체 광학 데이터 분석

## 해결해야 하는 문제
광원, 측정 스펙트럼으로부터 뇌 내 성분 농도 산출


## Data
▶train.csv(10MB)
- id : 구분자
- rho : 측정 거리 (단위: mm)
- src : 광원 스펙트럼 (650 nm ~ 990 nm)
- dst : 측정 스펙트럼 (650 nm ~ 990 nm)
- hhb : 디옥시헤모글로빈 농도
- hbo2 : 옥시헤모글로빈 농도
- ca : 칼슘 농도
- na : 나트륨 농도

▶test.csv(10MB)
- id : 구분자
- rho : 측정 거리 (단위: mm)
- src : 광원 스펙트럼 (650 nm ~ 990 nm)
- dst : 측정 스펙트럼 (650 nm ~ 990 nm)

▶sample_submission.csv(1MB)
- hhb : 디옥시헤모글로빈 농도
- hbo2 : 옥시헤모글로빈 농도
- ca : 칼슘 농도
- na : 나트륨 농도
