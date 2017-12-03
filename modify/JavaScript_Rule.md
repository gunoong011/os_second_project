ERICAST JavaScript Style Guide()
================================

ERICAST에 대한 합리적 접근 방법

목차
--------------------------------

**1. [들여쓰기](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#1-들여쓰기)**</br>
**2. [명명규칙](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#2-명명규칙)**</br>
**&nbsp;&nbsp;2.1. [변수](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#21-변수)**</br>
**&nbsp;&nbsp;2.2. [클래스(함수)](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#22-클래스())**</br>
**3. [주석](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#3-주석)**</br>
**4. [공백](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#4-공백)**</br>


### 1. 들여쓰기

&nbsp;&nbsp;들여쓰기는 기본적으로 **Space 2회**로 규정한다.

| Example |
|---------|
|example: function(test) {<br/>&nbsp;&nbsp;1st if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;2nd if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3rd if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;...<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br/>&nbsp;&nbsp;&nbsp;&nbsp;}<br/>&nbsp;&nbsp;}<br/>}|


### 2. 명명규칙

&nbsp;&nbsp;모든 변수, 클래스 등의 이름은 명시하는 명명규칙에 따라서 작성할 수 있도록 한다.

기본적으로 **영문 대소문자, 숫자, 언더스코어**로 작성할 수 있도록 한다.

다른 문자는 **허용하지 않는다.**

#### 2.1. 변수

&nbsp;&nbsp;변수는 이 변수가 어디에 쓰이는 resource인지를 쉽게 알아볼 수 있도록 정한다.

또한, 변수의 이름에서의 **영문 소문자**를 제외한 문자는 허용하지 않는다.

| Bad | Good |
|-----|------|
|var wow = new testClass(); // 역할의 모호성|var number = new testNumber(); // 전문 영소문자|
|var Apple_Fruit = new testFruit(); // 영문 소문자 이외의 문자 사용|var apple = new testFruit(); // 역할의 확실한 표현|

#### 2.2. 클래스(함수)

&nbsp;&nbsp;클래스는 이 변수가 어떠한 역할을 하는 것인지에 대한 **동사**와 **명사**로 조합하여 명명한다.

명명을 할 때에는 **파스칼 표기법**을 준수하되, 역할을 나타내는 동사는 **영문 소문자**로 작성할 수 있도록 한다.

| Bad | Good |
|-----|------|
|TestNamingClass: function() { // 동사가 영문 대문자로 시작</br>&nbsp;&nbsp;test = (a + b);</br>}|testNamingClass: function() { // 표기법 준수</br>&nbsp;&nbsp;test = (a + b);</br>}|

### 3. 주석

&nbsp;&nbsp;주석은 코드의 이해를 돕기 위한 보조문으로 주석은 한줄 주석과 여러줄 주석이 있다.

각 주석은 설명구문의 **들여쓰기에 맞춰쓰는 것**을 원칙으로 한다.

문장의 끝에 주석을 작성할 경우에는 **Space 1회**로 띄어쓰기 하도록 한다.

| Bad | Good |
|-----|------|
|function someFunction() {</br>// statement에 관한 주석</br></br>&nbsp;&nbsp;// 들여쓰기, 주석 전 줄바꿈</br>&nbsp;&nbsp;statements</br>}|function someFunction()&nbsp;{</br></br>&nbsp;&nbsp;// statement에 관한 주석</br>&nbsp;&nbsp;statements</br>}|
|var Value += data1 + data2 - length;//전후 공백 없음|var Value += data1 + data2 - length; // 전후 공백|
|var Value += data1 + data2 - length; /* 여러 줄 주석 */||

&nbsp;&nbsp;여러줄 주석의 경우에는 가독성을 위하여 \*의 **들여쓰기**를 반드시 맞춰주도록 한다.

| Bad | Good |
|-----|------|
|/\*</br>\* '\*' 표시의 정렬이 맞지 않는다.</br>\*/|/\*</br>&nbsp;&nbsp;\* '\*' 표시의 정렬을 맞춘다.</br>&nbsp;&nbsp;\*/|
|...</br>/\* var foo = ''; // 첫줄 문장</br>&nbsp;&nbsp;\* var bar = '';</br>&nbsp;&nbsp;\*var quux;</br>&nbsp;&nbsp;\*/||

&nbsp;&nbsp;위의 마지막 예시와 같은 **코드 주석**이 있다면, 반드시 **한줄 주석들의 모음**으로 처리한다.

| Example |
|---------|
|// var foo = '';</br>// var bar = '';</br>// var quux;|

### 4. 공백

&nbsp;&nbsp;공백은 키워드, 연산자 또는 다른 코드 사이에 있어야 한다.

단, 클래스 선언에 있어서 클래스의 Name 직후는 공백을 두지 않으며,

':' 문자의 뒤에 공백을 하나 삽입 해야한다.

| Bad | Good |
|-----|------|
|var value;</br>if(typeof str==='string') { // 키워드 후 공백</br>&nbsp;&nbsp;value=(a+b);</br>}|createTestClass: function() {</br>&nbsp;&nbsp;value = (a + b);</br>}|

&nbsp;&nbsp;괄호의 직후에는 공백을 제거한다. _단, 괄호 내의 인자들의 나열에서 콤마(,)의 직후에는 공백이 있어야 한다._

| Bad | Good |
|-----|------|
|var arr = \[ 1,2,3,4 \]; // 내부 공백|var arr = \[1, 2, 3, 4\];|
|someFunction(a, b, {</br>&nbsp;&nbsp;&nbsp;&nbsp;prop1: 1,</br>&nbsp;&nbsp;&nbsp;&nbsp;prop2: 2,</br>&nbsp;&nbsp;&nbsp;&nbsp;prop3: 3</br>&nbsp;&nbsp;}</br>); // 닫는 괄호 후 개행|someFunction(a, b, {</br>&nbsp;&nbsp;&nbsp;&nbsp;prop1: 1,</br>&nbsp;&nbsp;&nbsp;&nbsp;prop2: 2,</br>&nbsp;&nbsp;&nbsp;&nbsp;prop3: 3</br>&nbsp;&nbsp;});|
|if ( typeof str === 'string' ) // 괄호 내 공백||
