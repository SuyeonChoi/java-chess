# java-chess

체스 미션 저장소

## 기능 목록
## 1단계 - 체스판 초기화
- [x]  체스판을 초기화한다.
    - [x]  게임시작은 start, 종료는 end 명령을 입력해야한다.
    - [x]  체스판은 세로로 8줄, 가로로 8줄이다.
        - [x] 세로는 a-h, 가로는 1-8 범위다.
    - [x]  체스판엔 두 개의 진영이 존재한다.
        - [x]  팀 당 체스 피스를 각 16개씩 갖는다.
        - [x]  흰색 팀은 알파벳 소문자로 표시하고 체스판 밑에 위치한다.
        - [x]  검은 팀은 알파벳 대문자로 표시하고 체스판 위에 위치한다.
        - [x]  체스 피스가 없는 곳은 . 으로 표시한다.
    - [x]  첫 랭크에 룩-나이트-비숍-퀸-킹-비숍-나이트-룩, 둘째 랭크에 폰들을 놓는다.
    - [x]  검은 팀 킹과 흰색 팀 킹의 체스피스는 마주보게 배치한다.

### 2단계 - 말 이동
- [ ]  한 턴 씩 번갈아가며 체스피스를 한개씩 움직인다.
- [ ]  `move source 위치 target 위치` 를 입력받는다.
    - [ ]  위치는 (가로위치+세로위치) 형식으로 입력해야한다.
    - [ ]  가로위치는 a~h 사이의 알파벳으로 입력해야한다.
    - [ ]  세로위치는 1~8 사이의 숫자를 입력해야한다.
- [ ]  `source 위치` 에서 `target 위치` 로 체스 피스를 이동한다.
    - [ ]  `source 위치`에 같은 팀의 체스 피스가 있는지 확인한다.
    - [ ]  `target 위치`로 체스 피스가 이동할 수 있는지 확인한다.
        - [ ]  같은 팀의 체스 피스가 있으면 이동할 수 없다.
        - [ ]  상대 플레이어의 체스 피스가 있으면 제거하고 자리를 차지한다.
    - [ ] 체스피스는 타입에 따라 움직인다.
      * 폰
        - [x] 초기상태에서 한 칸 혹은 두 칸 전진한다.
        - [x] 초기상태 이후로는 한 칸씩만 전진한다.
        - [ ] 상대방의 피스는 대각선 한 칸으로만 잡는다.
      * 나이트
        - [ ] 두 칸 전진한 상태에서 좌우로 한 칸 움직인다. 
        - [ ] 다른 피스를 뛰어넘을 수 있다.
      * 비숍
        - [ ] 대각선 방향으로 칸 수의 제한 없이 움직인다. 
      * 룩
        - [ ] 전후와 좌우로 칸 수의 제한 없이 움직인다.
      * 퀸
        - [ ] 전후좌우, 대각선으로 칸수 제한 없이 움직인다.
      * 킹
        - [ ] 전후좌우, 대각선 방향으로 한 칸씩 움직인다.

## 우아한테크코스 코드리뷰

- [온라인 코드 리뷰 과정](https://github.com/woowacourse/woowacourse-docs/blob/master/maincourse/README.md)
