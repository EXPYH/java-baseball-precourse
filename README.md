# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

## 구현 기능 목록
### 1. UI
1. 게임 메인 메뉴
  * 프로그램 시작 시 / 라운드 종료 시 출력
    * "게임을 새로 시작하려면  1, 종료하려면 2를 입력하세요."
    * 1 누르면 새로운 게임 시작, 2 누르면 프로그램 종료.
  * 게임 메뉴 입력 예외 구현 (1, 2 이외 입력시)
    * 예외 시 메시지 출력 후 다시 메인 메뉴 출력

2. 게임 플레이 관련
* 세자리 입력
  * 예외 처리
    * 미입력
    * 숫자 이외의 입력
    * 3자릿수 미만의 입력
    * 세자릿수 초과의 입력
    
* 게임 중간결과 출력
  * "n 스트라이크 n 볼"
  * "나씽"
    
* 정답 확인 시 정답 출력

### 2. 게임 로직
1. 정답 생성 기능
* 3자리 정수 생성
  * 1-9 사이의 서로 다른 숫자로 이뤄진 세 자리 정수

2. 정답 계산 기능
  * n스트라이크 / n볼 / 나씽 계산


