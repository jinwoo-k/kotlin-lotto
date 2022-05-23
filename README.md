# kotlin-lotto

## 2단계 - 로또(자동)
### 기능 요구사항
- 로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야 한다.
- 로또 1장의 가격은 1000원이다.
### 프로그래밍 요구 사항
- 모든 기능을 TDD로 구현해 단위 테스트가 존재해야 한다. 단, UI(System.out, System.in) 로직은 제외
- 핵심 로직을 구현하는 코드와 UI를 담당하는 로직을 구분한다.
- UI 로직을 InputView, ResultView와 같은 클래스를 추가해 분리한다.
- indent(인덴트, 들여쓰기) depth를 2를 넘지 않도록 구현한다. 1까지만 허용한다.
- 예를 들어 while문 안에 if문이 있으면 들여쓰기는 2이다.
- 힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 메서드)를 분리하면 된다.
- 함수(또는 메서드)의 길이가 15라인을 넘어가지 않도록 구현한다.
- 함수(또는 메서드)가 한 가지 일만 잘 하도록 구현한다.
- 기능을 구현하기 전에 README.md 파일에 구현할 기능 목록을 정리해 추가한다.
- git의 commit 단위는 앞 단계에서 README.md 파일에 정리한 기능 목록 단위로 추가한다.


### 구현 기능 목록
- RandomNumberGenerator
  - [ ] 1~45 사이에 숫자 6개를 반환한다.
- Lotto
  - [ ] 1~45 사이 숫자 6개를 갖는 프로퍼티를 초기화한다.
  - [ ] RandomNumberGenerator를 생성자 파라미터로 받아 임의의 값으로 초기화한다.
  - [ ] 사용자가 입력한 숫자를 파라미터로 받아 초기화한다.
- LottoShop
  - [ ] 금액을 입력하면 몇개의 로또를 발급해야하는지를 반환한다.
  - [ ] 천원단위로 떨어지지 않으면? > 천원단위 내림하여 계산한다.
  - [ ] 당첨번호(Lotto)를 반환한다.
- PurchaseRecord
  - [ ] 구매한 Lotto 들을 프로퍼티로 갖는다.
