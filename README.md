# 🏎️ 자동차 경주 🏁

---
작성자 : [임재홍](https://github.com/ahpicl64)
# 🔧 구현 목록

---

---
## 기능 1️⃣ 문자열 입력

---

### [1.1 사용자 값 입력]
- [ ] `1.1.1` 사용자가 콘솔에 문자와 숫자, 구분자로 이루어진 차량들의 이름을 입력, `2.1.1`으로 간다.
- [ ] `1.1.2` 사용자가 콘솔에 숫자로 이루어진 차량들의 이동 횟수를 입력, `2.2.3`으로 간다. 

---

---
## 기능 2️⃣ 계산

---
### [2.1 차량(이름) 등록]
- [ ] `2.1.1` 입력받은 내용을 `쉼표(,)`를 구분자로하여 각 이름 / 차량으로 분리
- [ ] `2.1.2` 각 차량을 컬렉션에 등록

### [2.2 차량 이동 거리 계산]
- [ ] `2.2.1` 각 차량의 `0-9`까지의 `무작위 정수`를 산출, `Randoms.pickNumberInRange(0, 9);`를 사용
- [ ] `2.2.2` 무작위 값이 `4` 이상인 차량은 `1칸 전진` 각 차량별 값은 `2.3.1`로 보낸다
- [ ] `2.2.3` 입력받은 `이동 횟수 만큼 반복`

### [2.3 우승자 결정]
- [ ] `2.3.1` 각 차량별 이동 거리를 누적 `3.2.2`로 보낸다
- [ ] `2.3.2` 각 차량별 이동거리를 비교, 가장 멀리간 차량 및 동률 차량을 산출
- [ ] `2.3.3` 우승자 명단 작성, `3.3.1`로 보낸다. 2명 이상일 시 `2.3.4`로 보낸다
- [ ] `2.3.4` 컬렉션 이름 사이 구분자(,) 입력
---

---
## 기능 3️⃣ 출력
### [3.1 최초 입력단계]
- [ ] `3.1.1` 입력 전 메시지 출력 `경주할 자동차 이름(이름은 쉼표(,) 기준으로 구분)` `시도할 횟수`

### [3.2 프로그램 실행단계]
- [ ] `3.2.1` 안내 메시지 출력 `실행 결과`
- [ ] `3.2.2` `2.3.1`에서 받은 거리를 동일한 개수의 `-`로 변환하여 출력한다.
- [ ] `3.2.3` 2회 이상의 이동 횟수 시, 연속적으로 차량과 차량별 이동거리 출력

### [3.3 프로그램 종료 전]
- [ ] `3.3.1` `최종 우승자 : ` `2.3.3`또는 `2.3.4`에서 받은 명단을 출력한다

---

### 허용되는 경우
- `특수문자`외에 제약을 두지는 않는다. (한글, 영어, 숫자)

### 제약사항
- 이름은 `5자 이하`로 입력

### 그 외 구현할 기능

---

## 예외 처리
- [ ] 잘못된 구분자 입력시 
- [ ] 5자 이상의 이름을 입력하거나, 이름에 특수문자를 사용 시
- [ ] 이름에 공백 (" ", "") 을 입력 시
- [ ] 이동 횟수(차수)에 0 또는 공백 (" ", "")을 입력 시
