# java-racingcar-precourse

## 기능 요구사항

### 입력

- [ ] 경주할 자동차 이름을 입력받는다.
- [ ] 시도할 횟수를 입력받는다.

### 입력값 검증

- [ ] 자동차 이름은 쉼표(,)를 기준으로 구분해서 입력해야 한다.
- [ ] 자동차 이름은 5자 이하만 가능하다.
- [ ] 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시킨 후 애플리케이션은 종료되어야 한다.

### 게임 진행

- [ ] 0에서 9 사이에서 무작위 값을 구한다.
- [ ] 0에서 9 사이의 무작위 값이 4 이상인지 확인한다.
- [ ] 입력했던 시도 횟수만큼 전진을 시킨다.
- [ ] 전진할 때마다 각 자동차별로 (-) 표시를 추가한다.
- [ ] 각 차수마다 전진을 시키고 실행 결과를 저장한다.
- [ ] 자동차별로 총 전진한 횟수를 저장한다.
- [ ] 자동차별 총 전진한 횟수에 따라 우승자를 판단한다.
- [ ] 우승자가 한 명인지 여러 명인지 판단한다.

### 출력

- [ ] 자동차 이름을 입력받을 때 "경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)"를 출력한다.
- [ ] 시도할 횟수를 입력받을 때 "시도할 횟수는 몇 회인가요?"를 출력한다.
- [ ] 차수별 실행 결과를 출력한다.
- [ ] 단독 우승자 안내 문구를 출력한다.
- [ ] 공동 우승자 안내 문구를 출력한다.
- [ ] 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분해 출력한다.