ERICAST JavaScript Style Guide()
================================

ERICAST�� ���� �ո��� ���� ���

����
--------------------------------

[Link] [1. �鿩����] (https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md#1-�鿩����, "Link to 1")
2. ����Ģ
3. �ּ�
4. ����
5. etc


### 1. �鿩����

�鿩����� �⺻������ Space 2ȸ�� �����Ѵ�.

����, �鿩���Ⱑ N�� �ݺ� �� ���
2Nȸ�� �������� ǥ���Ͽ��� �Ѵ�.

| Example |
|---------|
|example: function(test) {<br/>&nbsp;&nbsp;1st if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;2nd if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3rd if () {<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;...<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br/>&nbsp;&nbsp;&nbsp;&nbsp;}<br/>&nbsp;&nbsp;}<br/>}|


### 2. ����Ģ

��� ����, Ŭ���� ���� �̸��� ����ϴ� ����Ģ�� ���� �ۼ��� �� �ֵ��� �Ѵ�.

�⺻������ ���� ��ҹ���, ����, ������ھ�� �ۼ��� �� �ֵ��� �Ѵ�.

�ٸ� ���ڴ� ������� �ʴ´�.

#### 2.1 ����

������ �� ������ ��� ���̴� resource������ ���� �˾ƺ� �� �ֵ��� ���Ѵ�.

����, ������ �̸������� ���� �ҹ��ڸ� ������ ���ڴ� ������� �ʴ´�.

    // Bad
    var wow = new testClass(); // ������ ��ȣ��
    var Apple_Fruit = new testClassFruit(); // ���� �ҹ��� �̿��� ���� ���

    // Good
    var apple = new testClassFruit(); // ���� ���ҹ���

#### 2.2 Ŭ����(�Լ�)

Ŭ������ �� ������ ��� ������ �ϴ� �������� ���� ����� ���� �����Ͽ� ����Ѵ�.

����� �� ������ �Ľ�Į ǥ����� �ؼ��ϵ�, ������ ��Ÿ���� ����� ���� �ҹ��ڷ� �ۼ��� �� �ֵ��� �Ѵ�.

    // Bad
    TestNamingClass: function() { // Class�� ������ ��Ÿ���� ���簡 ���� �빮�ڷ� ����
      test = (a + b);
    }

    // Good
    testNamingClass: function() { // ���� ���� �ҹ���, �Ľ�Į ǥ��� �ؼ�
      test = (a + b);
    }


### 3. �ּ�

�ּ��� �ڵ��� ���ظ� ���� ���� ���������� �ּ��� ���� �ּ��� ������ �ּ��� �ִ�.

�� �ּ��� �������� �鿩���⿡ ���羲�� ���� ��Ģ���� �Ѵ�.

������ ���� �ּ��� �ۼ��� ��쿡�� Space 1ȸ�� ���� �ϵ��� �Ѵ�.

    // Good
    function someFunction() {

        // statement�� ���� �ּ�
      statements
    }

    // Bad - �鿩���� ����, �ּ� ���� �� �� ��� ����
    function someFunction() {
    // statement�� ���� �ּ�
      statements
    }

    // Good
    var Value += data1 + data2 - length; // �ּ� ǥ�� ���� ����

    // Bad
    var Value += data1 + data2 - length;//�ּ� ǥ�� ���� ���� ����

    // Bad
    var Value += data1 + data2 - length; /* ���� �� �ּ� */


������ �ּ��� ��쿡�� �������� ���Ͽ� \*�� �鿩���⸦ �ݵ�� �����ֵ��� �Ѵ�.

    // Good
    /*
     * '*' ǥ���� ������ �����.
     */
 
    // Bad
    /*
    * '*' ǥ���� ������ ���� �ʴ´�.
    */

    // Bad - �ּ��� ù�ٿ� ������ ��
    ...
    /* var foo = '';
     * var bar = '';
     *var quux;
     */

���� ������ ���ÿ� ���� �ڵ� �ּ��� �ִٸ�, �ݵ�� ���� �ּ����� �������� ó���Ѵ�.

    // Good
    // var foo = '';
    // var bar = '';
    // var quux;

### 4. ����

������ Ű����, ������ �Ǵ� �ٸ� �ڵ� ���̿� �־�� �Ѵ�.

��, Ŭ���� ���� �־ Ŭ������ Name ���Ĵ� ������ ���� ������,

':' ������ �ڿ� ������ �ϳ� ���� �ؾ��Ѵ�.

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

��ȣ�� ���Ŀ��� ������ �����Ѵ�.

��, ��ȣ ���� ���ڵ��� �������� �޸�(,)�� ���Ŀ��� ������ �־�� �Ѵ�.

    // Good
    var arr = [1, 2, 3, 4];

    // Good
    someFunction(a, b, {
      prop1: 1,
      prop2: 2,
      prop3: 3
    });

    // Bad - ��ȣ �ȿ� ����
    if ( typeof str === 'string' )

    // Bad - ��ȣ �� ����, �޸� �� ���� ����
    var arr = [ 1,2,3,4 ];

    // Bad - ��ü�� �ݴ� ��ȣ ������ ����
    someFunction(a, b, {
        prop1: 1,
        prop2: 2,
        prop3: 3
      }
    );