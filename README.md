# kotlin-racingcar

# 2단계 - 문자열 계산기

### 요구사항

* 사용자가 입력한 문자열 값에 따라 사칙 연산을 수행할 수 있는 계산기를 구현해야 한다.
  문자열 계산기는 사칙 연산의 계산 우선순위가 아닌 입력 값에 따라 계산 순서가 결정된다. 즉, 수학에서는 곱셈, 나눗셈이 덧셈, 뺄셈 보다 먼저 계산해야 하지만 이를 무시한다.
  예를 들어 "2 + 3 * 4 / 2"와 같은 문자열을 입력할 경우 2 + 3 * 4 / 2 실행 결과인 10을 출력해야 한다.
* 메서드가 너무 많은 일을 하지 않도록 분리하기 위해 노력해 본다.
* 테스트할 수 있는 단위로 나누어 구현 목록을 만든다.
    * 덧셈
    * 뺄셈
    * 곱셈
    * 나눗셈
    * 입력값이 null이거나 빈 공백 문자일 경우 IllegalArgumentException throw
    * 사칙연산 기호가 아닌 경우 IllegalArgumentException throw
    * 사칙 연산을 모두 포함하는 기능 구현

### Todo

- [x] 문자열을 입력받는다.
- [x] 숫자와 연산기호를 분리한다.
- [x] 연산기호에 따라 결과값을 계산한다.
- [x] 값을 출력한다.
- [x] 테스트를 작성한다.



# 3단계 - 자동차 경주

### 요구사항

* 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
* 사용자는 몇 대의 자동차로 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
* 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
* 자동차의 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.
* InputView, ResultView 와 같은 클래스를 추가해 분리한다.
* 값을 입력받는 API는 kotlin.io 의 readLine을 이용한다.

### 실행 결과

```
자동차 대수는 몇 대인가요?
3
시도할 횟수는 몇 회인가요?
5

실행 결과
-
-
-

--
-
--

---
--
---

----
---
----

----
----
-----
```

### Todo

- [x] 자동차 대수를 입력받는다.
- [x] 시도할 횟수를 입력 받는다.
- [x] 자동차 게임을 진행한다.
- [x] 자동자 게임 진행과정을 출력한다.
- [x] 테스트를 작성한다.
