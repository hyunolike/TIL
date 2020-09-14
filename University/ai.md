# 인공지능👨‍🎓
`마지막 대학교 수업` 

![업데이트일시](http://img.shields.io/badge/%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8%F0%9F%8E%89-2020.09.07-green?style=for-the-badge&logo=appveyor)
## 4차 산업혁명(인공지능) 출현 이유
1. __SNS__ 출현(개인화 이유) 
2. 고객들의 다양한 요구
3. 인터넷 -> 빅데이터
4. 인공지능(빅데이터를 지능적으로 추출하기 위해서 나왔어)
5. Deep Learning(예시: 알파고 등)

- `인공지능` 
 > 탐색, 추론, 기계학습(딥러닝) <br/>

 
😋 현재 `2020` 기준으로 기계학습이 가장 인기가 많다!!



## 인공지능의 역사

### Gotfried Leibniz
`직관적으로 만듬`
- `미적분` 을 만들었음
- 사람의 생각을 수식으로 만들 수 있을까??

### George Boole
`체계적으로 발전!!`
- 사람의 생각을 계산하기 위한 __대수학__ 제안
    1. Operand : `proposition` (=0/1)
    2. Operator : and, or, `implication`
    3. Priority
    4. Equivalence rules <br/>
    
😛 여기서 ` ` 이 표시가 __기존 대수학__ 과 다른점이야

- Implication
- 명제 논리를 이용한 문제 해결!!! -> 하지만 명제 논리에서 `삼단논법의 문제점` 발견!!

#### 술어 논리(Predicate Logic)
`삼단논법의 문제점을 해결` __술어__ 와 __논리__ 를 통한 문제해결

#### 한정자(Quantifier)와 추론
__전체한정자(Universal quantifier)__ 와 __존재한정자(Existential quantifier)__ 


### Bertrand Russell
- 프레게의 논리주의(Logicism)
`수학은 논리의 확장이다`

- 러셀의 페러덕스
`다음 집합 R은 자기 자신에 속하는가? 속하지 않는가?`<br/>
😎결과적으로 __집합론에 문제가 있음을 암시__ -> 수학의 근본 위기 초래

### David Hilbert
1. 모든 수학 표현은 __정교한 형식 언어__ 로 기술되어야 한다.
2. __모든 참인 문장은 해당 형식 언어를 이용해 증명 가능__ 해야 한다.

### Alan Turing
1. 정교한 형식 언어 -> `Turing Machine`
    > 5개의 기본 요소로 알고리즘으로 기술될 수 있는 모든 문제가 해결 가능함을 보여줌

2. Completeness -> 일부문제는 위 기계로 해결되지 않음

### 🤗컴퓨터의 시초
1. ENIAC
2. EDVAC

### John von Neumann
1. Engineering viewpoint(focusing on HOW)
2. Mathematical viewpoint(focusing on WHAT) 

### 😁인공지능의 시초
`Alan Turing`
- __Turing Test__ : 기계가 지능이 있다는 것은 어떻게 정의 할 것인가?

## 😋본격적인 인공지능 시작 파트
### 인공지능이란 무엇인가
- Agent : 인공지능 문제를 푸는 주체
- Agen의 지능적 행위 <br/>
    `Perception + Learning + Action`

### 기계가 생각할수 있을까?
- "생각한다"의 정의는? 직접적인 정의는 어려우므로, __튜링 테스트__ 로 설명

### 인공지능의 접근 방법
- 기호적(Symbolic) 접근 방법
    - `텍스트 데이터` 기반으로 __추론__ 수행 
    - 하향식 설계 방법
    - 명제논리, 술어논리, 지식기반 시스템(전문가 시스템)...
- 비기호적(Subsymbolic) 접근 방법
    - `수치(신호) 데이터` 기반으로 __기계학습__ 수행
    - 상향식 설계 방법
    - 자극반응 에이전트, 신경망 회로, 딥러닝...

### 인공지능의 역사
- 인공지능을 향항 첫걸음(~1950)
    - 아리스토텔레스의 삼단논법
    - 라이프니츠의 보편적인 대수학
    - Boole의 명제논리
    - Frege의 술어 논리 
    - Turing의 기계에 대한 지능 테스트
- AI에 대한 큰 기대(~1960) 
    - McCarthy에 의해 최초로 "인공지능" 이라는 용어가 소개
    - Logic Theorist, GPS(General Problem Solver) 등 간단한 추론 프로그램 소개
- 현실의 직면(~1970 초반)
    - 장난감 수준의 문제만이 해결 가능함을 파악
    - 미/영 정부의 프로젝트 지원 중단
- 성공에 대한 기대(~1990)
    - 전문가시스템의 성공
    - 방대한 지식을 추론에 이용할 겨웅 현실 시계에 유용
- 실질적인 인공지능 구현(2000~)
    - 딥러닝의 성공
    - 음성인식, 자율주행, 쇼핑 등 다양한 분야에서 적용
    
## Stimulus-Response-Agent (자극 반응 에이전트)
### 에이전트
- Agent: 인공지능 문제를 풀기 위해 설계된 __자율적인(Autonomous)__ 주체
    - Stateless: `메모리 없이` 자극에 즉각적으로 반응하는 에이전트(SR, Stimulus-response agent)
    - Stateful: `메모리를 이용해` 자극에 대한 학습 내용을 바탕으로 행동하는 에이전트(Planning agent)

### 에이전트 - 이성적(Rationality) 란
- Rationality is not the same as perfection
- On the other hand, omniscience always makes the right decision among all possible situation
- Rationally maximizes expected performance based on the percept sequence to date, while perfection (omniscience) maximizes actual performance

### 자극반응 에이전트(SR agent)
- 내부 상태가 없으며, 환경의 자극에 간단한 반응을 보이는 기계

- 지각과 행동 구성 요소

- 특징벡터(Featured vector) 정의 : 메모리 적게 차지하도록~~ 행동함수의 복잡도 감소
- 행동함수(Action plan) 정의 : 특징 벡터 값에 따라~~

### 부울대수(Boolean Algebra)
- SR에이전트의 __특징벡터와 행동함수를 표현하는데 적합__





