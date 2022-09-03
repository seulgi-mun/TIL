# TIL

> CORS란?

추가 HTTP 헤더를 사용하여, 한 출처에서 실행 중인 웹 애플리케이션이 다른 출처의 선택한 자원에 접근할 수 있는 권한을 부여하도록 브라우저에 알려주는 체제를 말합니다.



<p>
<div>

> CORS를 해결하기 위한 방법이 무엇인가요?

첫번째 방법으로는 웹 프라우저 실행 옵션이나 플러그인을 통한 동일 출처 정책을 회피하는 것입니다.
또 다른 방법으로는 jsonp 방식으로 json 데이터를 가져오는 것입니다
자바스크립트 파일이나 css 파일은 동일 출처 정책에 영향을 받지 않고 가져올 수 있으며 이를 이용해서 자바 스크립트 파일을 json 형식으로 파싱해서 사용할 수 있습니다.

</div>
</p>


<p>
<div>

> api 란?

애플리케이션 프로그램 인터페이스의 줄임말
API는 정의 및 프로토콜 집합을 사용하여 두 소프트웨어 구성 요소가 서로 통신할 수 있게 하는 메커니즘이다
로그램을 작성하기 위한 일련의 부(Sub) 프로그램, 프로토콜 등을 정의하여 상호 작용을 하기 위한 인터페이스 사양을 말한다.
보통 서버와 클라이언트 사이에서 데이터를 주고받기 위해서 사용함

</div>
</p>

<p>

>  REST API 

자원을 이름으로 구분하여 해당 자원의 상태를 주고받는 것을 말합니다.  URI를 통해 자원을 명시하고, Method를 통해 해당 자원의 상태를 주고 받습니다.  UI  사람과 프로그램 사이에서 의사소통 하게 하는 것 함수형 컴포넌트의 장점 함수형 컴포넌트는 단순하게 데이터를 받아서 UI에 뿌려 주기 때문에 코드가 간단합니다. 또한 함수형으로 적으면 Hooks를 사용이 가능하기 때문에 편리합니다. 

</p>

<p>

> 리액트와 vue의 차이는?

리액트는 라이브러리고 vue는 프레임워크다

</p>


<p mt-3>

> 리액트

자바스크립트 라이브러리의 하나로서 사용자 인터페이스를 만들기 위해 사용함
싱글 페이지 애플리케이션이나 모바일 애플이케이션을 만드는데 사용함

</p>


<p mt-3>

> SQL

SELECT * FROM *(테이블 명)

</p>


<p>
<div>

> OOP(Object-Oriented Programming) 란?

OOP는 객체의 관점에서 프로그래밍 하는 것을 의미한다.
대표적으로 Java와 C#이 객체 지향 프로그래밍 언어이다.
C언어를 절차 지향 프로그래밍이라 하는데, 절차 지향 프로그래밍은 프로세스가 함수 단위로 순서대로 진행되는 것을 말한다.
반면 OOP는 객체들의 유기적인 관계를 통해서 프로세스가 진행된다.
즉, 애플리케이션을 구성하는 요소들을 객체로 바라보고, 객체들을 유기적으로 연결하여 프로그래밍 하는 것을 말한다.

</div>
</p>

<p>
<div>

> 절차지향언어 란?

대표적인 예로는 c언어이며 개체를 순차적으로 처리하여 프로그램 전체가 유기적으로 연결되어야 한다
객체지향 언어를 사용하는 것에 비해 더 빨리 처리되어 시간적으로 유리함
컴퓨터의 처리구조와 유사하다

- 장점 :
컴퓨터의 처리구조와 유사해 실행속도가 빠름

- 단점 :
유지보수가 어려움
실행 순서가 정해져 있으므로 코드의 순서가 바뀌면 동일한 결과를 보장하기 어려움
디버깅이 어려움

</div>
</p>


<p>
<div>

> ORM(Object-relational mapping) 이란?

객체와 관계형 데이터베이스의 데이터를 자동으로 매핑(연결)해주는 것을 말한다.
객체 지향 프로그래밍은 클래스를 사용하고, 관계형 데이터베이스는 테이블을 사용한다.
객체 모델과 관계형 모델 간에 불일치가 존재하므로 ORM을 통해 객체 간의 관계를 바탕으로 SQL을 자동으로 생성하여 불일치를 해결한다.
데이터베이스 데이터 와 Object 필드를 매핑함
객체를 통해 간접적으로 데이터베이스 데이터를 다룬다.
Persistant API라고도 할 수 있다. -> 예) JPA, Hibernate 등
MVC 패턴에서 모델(Model)을 기술하는 도구.

</div>
</p>

<p>
<div>

> 자바스크립트란?

객체 기반의 스크립트 프로그래밍 언어이다. 
웹 브라우저 내에서 주로 사용되며, 다른 응용 프로그램의 내장 객체에도 접근할 수 있는 기능을 가지고 있다
HTML로는 웹의 내용을 작성하고, CSS로는 웹을 디자인하며, 자바스크립트로는 웹의 동작을 구현할 수 있다
자바스크립트는 주로 웹 브라우저에서 사용되나, Node.js와 같은 프레임워크를 사용하면 서버 측 프로그래밍에서도 사용할 수 있다
현재 컴퓨터나 스마트폰 등에 포함된 대부분의 웹 브라우저에는 자바스크립트 인터프리터가 내장되어 있다

</div>
</p>


<p>
<div>

> Vue란?

Vue.js는 웹 애플리케이션의 사용자 인터페이스를 만들기 위해 사용하는 오픈 소스 프로그레시브 자바스크립트 프레임워크다.

</div>
</p>

<p>
<div>

> 함수형 프로그래밍이란?

함수형 프로그래밍은 하나의 프로그래밍 패러다임으로 정의되는 일련의 코딩 접근 방식이며, 자료처리를 수학적 함수의 계산으로 취급하고 상태와 가변 데이터를 멀리하는 프로그래밍 패러다임을 의미한다.
함수형 프로그래밍 언어로 설계된 클로저,스칼라,하스켈 등의 언어가 있고, 자바스크립트,코틀린,파이썬 등에도 최근 버전에 함수형 프로그래밍 문법이 추가 되었다.


- 장점

높은 수준의 추상화를 제공한다 <br>
함수 단위의 코드 재사용이 수월하다 <br>
불변성을 지향하기 때문에 프로그램의 동작을 예측하기 쉬워진다 <br>

- 단점

순수함수를 구현하기 위해서는 코드의 가독성이 좋지 않을 수 있다 <br>
함수형 프로그래밍에서는 반복이 for문이 아닌 재귀를 통해 이루어지는데 (deep copy), 재귀적 코드 스타일은 무한 루프에 빠질 수 있다 <br>
순수함수를 사용하는 것은 쉬울 수 있지만 조합하는 것은 쉽지 않다 <br>

</div>
</p>

<p>
<div>

> HTTP란?

HTTP는 W3 상에서 정보를 주고받을 수 있는 프로토콜이다.
HTTP는 클라이언트가 요청을 생성하기 위한 연결을 연다음 응답을 받을때 까지 대기하는 전통적인 클라이언트-서버 모델을 따른다.
주로 HTML 문서를 주고받는 데에 쓰인다.
HTTP는 무상태 프로토콜이며, 이는 서버가 두 요청 간에 어떠한 상태나 데이터를 유지하지 않음을 의미한다. 
주로 TCP를 사용하고 HTTP/3부터는 UDP를 사용하며, 80번 포트를 사용한다.
일반적으로 안정적인 TCP/IP 레이어를 기반으로 사용하는 응용 프로토콜이다

</div>
</p>


<p>
<div>

> 데이터 모델링이란?

업무정보를 구성하는 기초정보를 약속된 표기법에 의해 표현함으로써 업무내영을 정확하게 분석
분석된 모델로 싱제 데이타 베이스를 생성하야 시스템 개발 및 데이터 관리에 사용하기 위해 수행함

</div>
</p>

