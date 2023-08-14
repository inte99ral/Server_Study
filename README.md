# 링크

- [윈도우 서버 구축](https://studyforus.tistory.com/62)
- [인프런 강의](https://www.inflearn.com/course/%EC%9C%A0%EB%8B%88%ED%8B%B0-mmorpg-%EA%B0%9C%EB%B0%9C-part4)

# 서론

## 서버란?

- 다른 컴퓨터에서 연결이 가능하도록 대기 상태로 상시 실행중인 프로그램

<br/>

- Web Server

  - HTTP protocol 기반, Stateless
  - 질의/응답 형태
  - 가볍고 최적화 되어있다

<br/>

- Game Server

  - TCP protocol 기반, Binary, Stateful
  - 실시간 Interaction
  - 요청 갱신이 계속되야함

<br/>

- 식당과의 비유
  | 식당 | 게임 서버 |
  | :---------------: | :-----------------: |
  | 전체 손님 한도 | 최대 동시 접속자 |
  | 한 방의 일행 한도 | 게임 장르 및 채널링 |
  | 직원 역할 구분 | 로직, 네트워크, DB |
  | 직원 수 | 쓰레드 개수 |
  | 직원 역할 비율 | 쓰레드 모델 |
  | 주문 받는 구조 | 네트워크 모델 |
  | 주문 대기 시간 | 반응성(FPS) |
  | 장부 및 결제 | DB |
