# 나만의 블로그 만들기!! [중단 새로운 레포지토리 생성... 추후 코드 확인 후 개발 예정]

항해99 3주차 심화 과제

---

## 개발과정

1. MVC 모델 구현
2. login 기능 구현
3. register 기능 구현
4. mySQL DB 연결
5. winston으로 log 관리
6. HTTP 상태코드 적용(로그인, 회원가입 기능)

---

# 사용 framework

1. codepen.io
2. bulma

---

# 사용 라이브러리

1. express
2. ejs
3. body-parser
4. mysql
5. dotenv
6. winston
7. prettier

# 공부 내용

1. promise

- 함수는 한가지 기능만 수행하도록 구현해줘야됨.
- Promise로 만들어주지 않으면 여러 기능을 하는 코드가 만들어짐

- 클래스는 각자의 역활을 분명하게 구분 시켜주는것이 좋음
- userSchema에서는 db를 crud 하는 역활
- user는 데이터를 가지고 검증 및 조작 수행

2. winston

- Debugging 용도로 console.log 사용이 많았는데, 실제 Project 수행 중 서버의 동작을 파악하거나 미처 못찾은 오류를 찾아야될 때 로그 파일을 뒤져보면 원인을 찾을수 있을 확률이 높다고 합니다.
- 그래서 서버에서 동작하는 로그인 회원가입 부분에 2군데에서 사용해보고 연습했습니다.

3. HTTP 상태코드

- 200 : 정상응답 , 300 : 페이지 이동시, 400: 클라이언트에서 실수(409 서버와 클라이언트의 데이터 충돌), 500:서버에서 실수
- 상태 코드 입력시 2중 삼항연산자를 사용했습니다. ex) status: response.success ? 200 : response.err ? 500 : 400
- 이중으로 삼항연산자를 사용한 게 옳은 코드인지는 더 공부를 해봐야 될 것 같습니다.

# 참고

[항해99 3주차 node.js plus]
[youtobe 우리밋_woorimIT 채널]
감사합니다.
