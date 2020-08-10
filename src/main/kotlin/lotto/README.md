# kotlin-lotto

#### 예상 시나리오
1. 구입금액을 입력받는다
2. 구입할 수 있는 로또의 갯수를 돌려준다.
3. 갯수만큼 자동으로 로또티켓을 생성한다.
4. 지난주 당첨번호를 입력받는다
5. 당첨통계를 낸다
6. 수익률을 낸다

#### 구현할 기능 리스트
##### 1) 구입금액 입력 - (readLine)
- 1000원 이하의 값 입력시에는 다시 입력받게함

##### 2) 입력한 금액만큼 로또 자동발급
- 로또 한 세트당 6개의 숫자가 발급되어짐
- 6개의 숫자는 중복될 수 없음

##### 3) 당첨번호 입력
- 로또 한 세트당 6개의 숫자가 발급되어짐
- 6개의 숫자는 중복될 수 없음

##### 4) 당첨통계
- 자동생성된 로또번호와 입력받은 당첨번호를 비교함
- 3,4,5,6개 번호가 일치하는 로또의 count를 구함

##### 5) 수익률 계산
- 구입금액 대비 당첨금액에 대한 수익률을 계산함


#### 요구사항
1. 모든 기능을 TDD로 구현해 단위 테스트가 존재해야 한다.
2. indent(인덴트, 들여쓰기) depth를 2를 넘지 않도록 구현한다. 1까지만 허용한다.
3. 함수(또는 메서드)의 길이가 15라인을 넘어가지 않도록 구현한다
4. 기능을 구현하기 전에 README.md 파일에 구현할 기능 목록을 정리해 추가한다.
5. git의 commit 단위a는 앞 단계에서 README.md 파일에 정리한 기능 목록 단위로 추가한다.