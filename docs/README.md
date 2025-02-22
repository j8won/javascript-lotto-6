
## 로또
- 로또 번호의 숫자 범위는 1~45까지이다
- 1개의 로또를 발행할 때 중복되지 않는 6개의 숫자를 뽑는다
- 로또의 번호가 6개가 아닐 경우 예외 처리한다
- 로또의 번호 중 중복되는 경우가 있다면 예외 처리한다

## 로또 생성
- 구입 금액을 1,000원 단위로 받아, 1000원에 한 장씩 로또 티켓을 발행한다
- 구입 금액이 숫자가 아닌 경우 예외 처리한다
- 구입 금액이 1,000원 단위가 아닌 경우 예외 처리한다
- 구입 금액의 문자열이 0으로 시작하면 예외 처리한다

## 당첨 번호
- 당첨 번호는 중복되지 않는 1~45까지의 6개의 숫자다
- 당첨 번호가 6개가 아닐 경우 예외 처리한다
- 당첨 번호가 모두 숫자가 아닐 경우 예의 처리한다
- 당첨 번호가 중복되는 경우 예외 처리한다


- 보너스 번호는 당첨 번호를 제외한 1~45까지의 1개의 숫자다
- 보너스 번호가 당첨 번호와 중복되는 경우 예외 처리한다

## 로또 당첨
- 로또의 번호와 당첨 번호 및 보너스 번호를 비교해 당첨 내역을 구한다
  - 1등: 6개 번호 일치 / 2,000,000,000원
  - 2등: 5개 번호 + 보너스 번호 일치 / 30,000,000원
  - 3등: 5개 번호 일치 / 1,500,000원
  - 4등: 4개 번호 일치 / 50,000원
  - 5등: 3개 번호 일치 / 5,000원

## 입력
- 로또 구입 금액을 입력받는다
- 당첨 번호를 입력받는다
- 보너스 번호를 입력받는다

## 출력
- 발행한 로또 수량 및 번호를 출력한다
- 로또 번호는 오름차순으로 정렬한다
- 당첨 내역을 출력한다
- 수익률을 출력한다
- 수익률을 소수점 둘째 자리에서 반올림한다
