### 기능 목록
- constructor(): computer_num,user_num 객체 속성 생성
- 게임시작()-play : 사용자 숫자 입력 받는 함수 호출, 컴퓨터 숫자를 맞추지 못했을때 호출되는 함수
- 게임종료()-endGame : 결과 안내문 출력, 게임 새로 시작 or 종료 입력 받기

- 유저숫자입력()-getUserInputNumber: 사용자의 숫자를 입력받는다.
- 게임결과()-resultGame: 스트라이크, 볼 결과 조건문으로 함수 호출

- 유저 숫자 배열로 변환()-changeUserNumberToArray: 유저가 입력한 숫자를 배열로 바꾸는 기능, 컴퓨터숫자와 비교하기 위한 목적
- 컴퓨터랜덤숫자선택()-selectComputerNumber(): 컴퓨터 랜덤 숫자 선택 기능
- 같은 숫자 찾기()-findEqualNumber: 같으면 스트라이크, 다르면 볼
- 볼 결과 출력 - resultBall: 게임계속(사용자입력받기)
- 낫싱 출력 - resultNothing: 게임계속(사용자입력받기)
- 볼 스트라이크 결과 출력- resultStrikeAndBall:  게임계속(사용자입력받기)

### 사용자 입력값 예외 목록
- getUserInputNumber(): 사용자 입력 타입은 숫자만 가능, 사용자 입력값은 숫자 3개만 가능, 서로 다른 3개의 숫자만 가능, 1에서 9 사이의 숫자 가능
- endGame(): 사용자 입력 타입은 숫자만 가능, 사용자 입력값은 1과 2 중 하나만 가능

### 테스트 목록
- changeComputerNumberToArray(): 입력 타입은 숫자만 가능, 반환값은 배열
- changeUserNumberToArray(): 입력 타입은 숫자만 가능, 반환값은 배열
- findEqualNumber(): 반환값 strike, ball 타입은 숫자
- resultGame(): 입력 타입은 숫자
- resultBall(): 입력 타입은 숫자
- resultStrikeAndBall(): 입력 타입은 숫자

