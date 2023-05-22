
javascript 기초

html과 css는 언어가 아니므로, 프로그램처럼 웹사이트를 만들고 싶으니까 logic을 도입해야 한다

-->마치 어플리케이션처럼 !

-->코드 실행 가능!

`	`1. 상호작용 가능

`	`2. 서버와 데이터 송수신 가능

`	`3. DOM(document object model)조정 가능 

ECMAScript 6+ 버전 이상의 javascript를 사용하는걸 추천.

변수란? 

x = 10 

ISBN(도서식별번호)처럼..

x --> "식별자"

var x = 10;

이라고 하면 var(variation=변수) x = 10 이 메모리 어딘가에 저장된다.

-variable, let, const(const=상수)-----  변수 선언.

var x = 10;

let x = 10;

const example1 = 10; -->example1 은 const로 상수가 되어서 이후에 바뀌지 않는다.(프로그래머는 변하지 않는것을 좋아하므로 const을 가능하면 쓰도록 하자.

선언 VS 할당

var example1 

-선언

var example1 = 10 

-할당

var: 재선언 가능

let: 재선언 불가능, 재할당은 가능

let b = 3;

let b = 4; // 에러(재선언불가)

let a = 3;

a = 4;

console.log(a) // 4가 출력됨.(재할당가능)

const: 재선언, 재할당 불가능 -- > const를 지향하자.

console.log(변수) 

변수를 출력

javascript에서 

0 == '0'

true

0 == [] 

true

'0' == []

false

암시적 형 변환이라고 

0 == '0' dmf gkaus

'0'이 0이 됨. (?)

0 ==[] 을 하면

number([])을 하면

0이 나옴

그래서 타입까지 비교하는 === 을 써야한다.

==을 지양해야함. 왜냐면 암시적 형 변환 때문에 엄밀한 === 을 써야 한다

조건문

javascript에서는 elif가 아니라 else if 를 사용함





