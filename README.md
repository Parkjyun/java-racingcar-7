# java-racingcar-precourse

# Car

- [ ]  자동차는 이름을 가질 수 있다.
- [ ]  자동차는 거리를 가질 수 있다.
- [ ]  자동차는 전진할 수 있다.
- [ ]  자동차는 다른 차보다 앞서있는지를 판단할 수 있다.
- [ ]  이름이 같은 자동차는 같은 자동차이다.

# Name

- [x]  이름을 가진다.
- [x]  이름이 같다면 같은 이름으로 취급한다.
- [ ]  잘못된 이름에 대한 예외처리를 한다.
    - [ ]  이름이 5자를 초과하면 예외를 발생시킨다.
    - [ ]  이름이 비어있으면 예외를 발생시킨다.

# Position

- [ ]  자동차의 현재 위치를 갖는다.
- [ ]  현재 위치가 양수가 아니라면 예외를 발생한다.
- [ ]  다른 위치보다 앞서 있는지를 판단한다.
- [ ]  위치를 증가시킬 수 있다.
- [ ]  같은 위치라면 같은 값이다.

# RaceCars

- [ ]  자동차의 목록을 갖는다.
- [ ]  같은 이름을 가지는 자동차가 여러개 있다면 예외를 발생한다.
- [ ]  2개 이상의 자동차를 갖지 않는다면 예외를 발생한다.

# RaceGame

- [ ]  경주에 참여하는 자동차의 목록을 가진다.
- [ ]  1회 round의 race를 할 수 있다.
    - [ ]  race를 진행하며 각각 자동차의 이동여부는 movement를 활용한다.
- [ ]  1회 round 이후 자동차들의 상태를 반환할 수 있다.
- [ ]  경주의 최종 우승자를 반환할 수 있다.

# Movement

- [ ]  이동 가능 여부를 판단한다.
    - [ ]  0-9 사이에서 무작위 값을 구한 후 무작위 값이 4이상일 경우 이동 가능하다.

# RoundCount

- [ ]  시도할 횟수를 가질 수 있다.
- [ ]  시도 횟수로 적절한 값을 사용하지 않을 경우 예외를 발생시킨다.
    - [ ]  숫자가 들어오지 않으면 예외를 발생시킨다.
    - [ ]  1이상의 정수가 들어오지 않으면 예외를 발생시킨다.
- [ ]  시도횟수를 감소시킬 수 있어야한다.
- [ ]  시도횟수가 모두 끝났는지 판단한할 수 있어야 한다.

# 입력

- [x]  사용자는 경주할 자동차 이름을 입력할 수 있다.
    - [x]  이름은 쉼표를 기준으로 구분한다.
    - [x]  비어있는 문자열이 입력되면 예외를 발생시킨다.

- [x]  사용자는 시도할 횟수를 입력할 수 있다.

# 출력

- [ ]  차수별 실행 결과를 출력한다.
    - [ ]  형식은 다음과 같다. {자동차 이름} : {이동한 횟수만큼의 “-”}
- [ ]  우승자 안내 문구를 출력한다.
    - [ ]  단독 우승자 안내 문구를 출력한다.
        - [ ]  형식은 다음과 같다. 최종 우승자 : {우승한 자동차 이름}
    - [ ]  최종 우승자 안내 문구를 출력한다.
        - [ ]  형식은 다음과 같다. 최종 우승자 : {우승한 자동차 이름}, {우승한 자동차 이름} …