# 📝 숫자 야구 게임

1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 맞추는 게임이다.

## ✨ 기능 구현 목록

- [ ] **컴퓨터 랜덤 숫자 생성** : 컴퓨터는 1에서 9까지 서로 다른 임의의 수 3개를 생성합니다.

- [ ] **사용자 입력값 검증** : 사용자 입력값이 입력 요구 사항과 다르다면 `throw`문 사용해 예외를 발생시킨 후 애플리케이션를 종료합니다.

  - [ ] 1에서 9까지 서로 다른 임의의 수 3개
  - [ ] 게임이 끝난 경우 재시작/종료를 구분하는 1과 2 중 하나의 수

- [ ] **출력값 계산** : 컴퓨터 랜덤 숫자와 사용자 입력값을 비교하여 볼과 스트라이크의 개수를 계산합니다.

  - [ ] 같은 수가 같은 자리에 있으면 스트라이크 + 1
  - [ ] 같은 수가 다른 자리에 있으면 볼 + 1

- [ ] **결과 출력** : 볼과 스트라이크 개수별로 다른 문구를 출력합니다.
  - [ ] 스트라이크가 3개인 경우
    - [ ] 입력값이 1인 경우 게임 재시작
    - [ ] 입력값이 2인 경우 게임 종료
  - [ ] 볼과 스트라이크 모두 0개인 경우 `낫싱` 출력
  - [ ] 볼만 1개 이상인 경우 `n볼` 출력
  - [ ] 스트라이크만 1개 이상인 경우 `n스트라이크` 출력
  - [ ] 볼과 스트라이크 모두 1개 이상인 경우 `n볼 n스트라이크` 출력