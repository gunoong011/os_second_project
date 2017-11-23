ERICAST JavaScript Style Guide()
================================

ERICAST에 대한 합리적 접근 방법

목차
--------------------------------

1. 들여쓰기
2. 문장의 종료
3. 명명규칙
4. 전역변수
5. 선언과 할당
7. 주석
8. 공백
6. etc


들여쓰기
--------------------------------
들여쓰기는 기본적으로 Space 2회로 규정한다.

따라서, 들여쓰기가 N번 반복 될 경우
2N회의 들여쓰기로 표현하여야 한다.

    example: function(test) {
      1st if () {
        2nd if () {
          3rd if () {
            ...
          }   
        }
      }
    }



주석
---------------------------------
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

공백
---------------------------------
공백은 키워드, 연산자 또는 다른 코드 사이에 있어야 한다.

    // Good
    var value;
    if (typeof str === 'string') {
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