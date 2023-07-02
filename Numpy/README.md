- np.arange
  - np.arange(시작점(생략 시 0), 끝점(미포함), step size(생략 시 1))
  - 실수 단위도 표현 가능

- np.nonzero
  - np.nonzero(array)
  - 요소들 중 0이 아닌 값들의 index 들을 반환해 주는 함수

- np.tile
  - np.tile(A,repeat_shape)
    - A 배열이 repeat_shape 형태로 반복되어 쌓인 형태 반환해주는 함수

- np.allclose
  - np.allclose(A,B)
  - 두 배열이 같으면 True / 다르면 False

- np.linspace
  - np.linspace(구간 시작점, 구간 끝점, 구간 내 숫자 개수,endpoint=True)
  - 구간 시작점에서 구간 끝 점(포함) 사이를 구간 내 숫자 균일한 간격으로 개수만큼 나눈다.

- np.arctan / np.arctan2
  1. numpy.arctan(x1, x2)
    - arc tangent of x1/x2.
    - 출력 범위가 [-pi/2, pi/2]
    - 180도 이상 차이나는 각의 arctan 값은 구분이 안됨(ex: arctan(0), arctan(180) 은 같음).
  2. numpy.arctan2(x1, x2)
    - arc tangent of x1/x2.
    - 출력 범위가 [-pi, pi]
    - C언어 atan2 함수와 같음.