# ‍서버 세미나🏃‍♂️

![업데이트일시](http://img.shields.io/badge/%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8%F0%9F%8E%89-2020.05.26-yellow?style=for-the-badge&logo=appveyor)

## ✔node.js
### node.js란
구글 크롬의 자바스크립트 엔진기반하여 만들어진 `서버 사이드 플랫폼` 이다.<br>
즉 서버를 만들기 위해서 만들어진거야.
> 착각하는게 `웹서버` 자체가 아니다!!!<br>
> 그냥 우리의 코드를 실행시켜주는거야<br>
> 그래서 `http 서버`를 작성해야되

### 비동기 I/O 처리 /이벤트 위주
__단일 스레드 비동기 처리__ 가 특징<br>
그래서 코드를 짤때 난항을 겪는다.

- 단일 스레드
  > 이벤트 핸들러 방식 <br>
  > 실제 일하는거는 `멀티  스레딩`을 해버리기 때문에 `비동기`가 생겨버렸어

### 일급객체란
변수나 데이터 구조안에 담을 수 있으며 파라미터를 전달할 수 있어야 하고 리턴값으로 사용할 수 있어야 해

### 익명함수

함수
```javascript
  function add1(a,b) {
    return a + b
  }
```

익명함수(즉시실행함수)
```javascript
  let add2 = function(a,b) {
    return a + b
  }
```

### 콜백(Callback) 이란 `제일 중요한 개념!!!🔥`
사실 node.js는 콜백이 다라고 할 수도 있다ㅋㅋㅋㅋ

콜백함수 사용법
```javascript
function plus(a,b, callback){
  let result = a + b;
  callback(result);
}

plus(100,100,function(result){
  console.log(`콜백함수 결과: ${result}`);
});
```

`result`가 나올때 까지 __콜백함수__ 는 기달린다!!!

---
## ✔Express 모듈
node.js를 이용해 서버 제작하는 과정을 알아보자<br>
`가벼운 http 웹 프레임워크`

### http 모듈

### 용어 정리 `알아둬야되`
- 미들웨어(midleware)
- 라우터(router)
- 쿠키파서(cookie parser)
- 바디파서(body parser)
- 익스프레스 세션(express-session) `새로운 세션 생성`
- 스태틱(static) `정적인 파일 제공`

### 미들웨어 함수
