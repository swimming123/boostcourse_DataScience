# boostcourse_DataScience

👍이번주 학습 내용은 다음 링크를 참고해주세요! [1주차 학습 내용](스터디 전용 강좌 1주차 학습 안내 링크)
1. 데이터 분석 환경 구성:https://www.boostcourse.org/ds112/joinLectures/28140
2. 데이터 분석 준비하기:https://www.boostcourse.org/ds112/joinLectures/28138


🔽 답안 예시

Pandas를 통한 파일 저장과 불러오기

to_csv("파일명", index=False) : csv 파일로 저장하기
read_csv("파일명") : csv 파일 불러오기
shape를 통한 행과 열의 수 보기
head, tail, sample 을 통한 일부 데이터 가져오기
DataFrame의 info(), describe() 등을 통한 요약과 기술통계 값 구하기

info()
describe()
nunique()
index
columns
values
Pandas의 DataFrame과 Series의 이해

Series : 1차원 벡터구조
DataFrame : 2차원 행렬구조
색인하기

[컬럼]
.loc[행]
.loc[행, 열]
.loc[조건식, 열]
DataFrame의 데이터 타입 이해하기

날짜 데이터의 변환
DataFrame 다루기

열(column) 인덱싱
행(index) 인덱싱
행, 열 인덱싱
정렬하기 : sort_values 사용하기
조건식 사용하기
빈도수 구하기

한 개의 변수 : series.value_counts()
두 개의 변수 : pd.crosstab()
groupby 와 pivot_table

다양한 연산식의 사용

