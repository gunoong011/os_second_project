ERICAST JavaScript Style Guide()
================================

ERICAST에 대한 합리적 접근 방법

목차
--------------------------------

[1. 들여쓰기](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#1-들여쓰기)

2. 명명규칙

3. 주석

4. 공백

5. etc


### 1. 들여쓰기

들여쓰기는 기본적으로 Space 2회로 규정한다.

따라서, 들여쓰기가 N번 반복 될 경우
2N회의 공백으로 표현하여야 한다.

| Example |
|---------|
|example: function(test) {<br/>&nbsp;&nbsp;1st if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;2nd if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3rd if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;...<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br/>&nbsp;&nbsp;&nbsp;&nbsp;}<br/>&nbsp;&nbsp;}<br/>}|


### 2. 명명규칙

모든 변수, 클래스 등의 이름은 명시하는 명명규칙에 따라서 작성할 수 있도록 한다.

기본적으로 영문 대소문자, 숫자, 언더스코어로 작성할 수 있도록 한다.

다른 문자는 허용하지 않는다.

#### 2.1 변수

변수는 이 변수가 어디에 쓰이는 resource인지를 쉽게 알아볼 수 있도록 정한다.

또한, 변수의 이름에서의 영문 소문자를 제외한 문자는 허용하지 않는다.

    // Bad
    var wow = new testClass(); // 역할의 모호성
    var Apple_Fruit = new testClassFruit(); // 영문 소문자 이외의 문자 사용

    // Good
    var apple = new testClassFruit(); // 전문 영소문자

#### 2.2 클래스(함수)

클래스는 이 변수가 어떠한 역할을 하는 것인지에 대한 동사와 명사로 조합하여 명명한다.

명명을 할 때에는 파스칼 표기법을 준수하되, 역할을 나타내는 동사는 영문 소문자로 작성할 수 있도록 한다.

    // Bad
    TestNamingClass: function() { // Class의 역할을 나타내는 동사가 영문 대문자로 시작
      test = (a + b);
    }

    // Good
    testNamingClass: function() { // 동사 영문 소문자, 파스칼 표기법 준수
      test = (a + b);
    }


### 3. 주석

주석은 코드의 이해를 돕기 위한 보조문으로 주석은 한줄 주석과 여러줄 주석이 있다.

각 주석은 설명구문의 들여쓰기에 맞춰쓰는 것을 원칙으로 한다.

문장의 끝에 주석을 작성할 경우에는 Space 1회로 띄어쓰기 하도록 한다.

    // Good
    function someFunction() {

        // statement에 관한 주석
      statements
    }

    // Bad - 들여쓰기 없음, 주석 전에 한 줄 띄기 없음
    function someFunction() {
    // statement에 관한 주석
      statements
    }

    // Good
    var Value += data1 + data2 - length; // 주석 표시 전후 공백

    // Bad
    var Value += data1 + data2 - length;//주석 표시 전후 공백 없음

    // Bad
    var Value += data1 + data2 - length; /* 여러 줄 주석 */


여러줄 주석의 경우에는 가독성을 위하여 \*의 들여쓰기를 반드시 맞춰주도록 한다.

    // Good
    /*
     * '*' 표시의 정렬을 맞춘다.
     */
 
    // Bad
    /*
    * '*' 표시의 정렬이 맞지 않는다.
    */

    // Bad - 주석의 첫줄에 문장이 옴
    ...
    /* var foo = '';
     * var bar = '';
     *var quux;
     */

위의 마지막 예시와 같은 코드 주석이 있다면, 반드시 한줄 주석들의 모음으로 처리한다.

    // Good
    // var foo = '';
    // var bar = '';
    // var quux;

### 4. 공백

공백은 키워드, 연산자 또는 다른 코드 사이에 있어야 한다.

단, 클래스 선언에 있어서 클래스의 Name 직후는 공백을 두지 않으며,

':' 문자의 뒤에 공백을 하나 삽입 해야한다.

    // Good
    var value;
    if (typeof str === 'string') {
      value = (a + b);
    }

    // Good
    createTestClass: function() {
      value = (a + b);
    }

    // Bad
    var value;
    if(typeof str==='string') {
      value=(a+b);
    }

괄호의 직후에는 공백을 제거한다.

단, 괄호 내의 인자들의 나열에서 콤마(,)의 직후에는 공백이 있어야 한다.

    // Good
    var arr = [1, 2, 3, 4];

    // Good
    someFunction(a, b, {
      prop1: 1,
      prop2: 2,
      prop3: 3
    });

    // Bad - 괄호 안에 공백
    if ( typeof str === 'string' )

    // Bad - 괄호 안 공백, 콤마 뒤 공백 없음
    var arr = [ 1,2,3,4 ];

    // Bad - 객체의 닫는 괄호 다음에 개행
    someFunction(a, b, {
        prop1: 1,
        prop2: 2,
        prop3: 3
      }
    );
