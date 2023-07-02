- df.dtypes
  - 모든 컬럼의 데이터 타입 확인
  - n 컬럼의 데이터 타입
    - df.iloc[:,n].dtype

- df.select_dtypes
  - df.select_dtypes(exclude=object)  
    - 수치형 변수 가진 컬럼

- df.fillna
  - 컬럼마다 결측값 채우는 방법이 다를 때
    - data.fillna({1:0.5,2:1})