# 1. 기본 규칙
<br/><br/>
## 1.1. W3C validation

&nbsp;&nbsp;&nbsp;&nbsp;모바일에서 CSS는 사용 가능한 Hack과 CSS3 속성을 제외하고 W3C Validation을 통과해야 한다.
<br/><br/>
## 1.2. 영문 소문자 사용

&nbsp;&nbsp;&nbsp;&nbsp;모든 속성은 영문 소문자로만 작성한다.

|올바른 예|잘못된 예|
|:--------|:--------|
|.class{<br/>&nbsp;&nbsp;font-family: sans-serif;<br/>}|.class{<br/>&nbsp;&nbsp;**Font-Family**: sans-serif;<br/>}|

<br/><br/>
## 1.3. 따옴표 사용 범위
&nbsp;&nbsp;&nbsp;&nbsp;W3C validation을 통과하는 범위안에서 따옴표 사용 제한은 없다.

|예시|
|---|
|font-family: ‘Open Sans';|
|font-family: "Open Sans";|
|둘 다 허용|

<br/><br/>
## 1.4. 들여쓰기

&nbsp;&nbsp;&nbsp;&nbsp;선택자들 간의 들여쓰기는 불허한다.
&nbsp;&nbsp;&nbsp;&nbsp;선택자 안의 가독성을 위한 들여쓰기는 허한다.

|올바른 예|잘못된 예|
|:--------|:--------|
|.form{<br/>&nbsp;&nbsp;background: #FFFFFF;<br/>}<br/>.form input{<br/>&nbsp;&nbsp;background : #F2F2F2;<br/>}|.form{<br/>&nbsp;&nbsp;background: #FFFFFF;<br/>}<br/>&nbsp;&nbsp;**.form input{<br/>&nbsp;&nbsp;&nbsp;&nbsp;background : #F2F2F2;<br/>&nbsp;&nbsp;}**|

<br/><br/>
## 1.5. 글꼴

&nbsp;&nbsp;&nbsp;&nbsp;다른 글꼴을 사용 할 수 있지만 글꼴의 기본은 sans-serif 로 정한다.


<br/><br/>
## 1.6. 공백

1. 쉼표(,)로 구분되는 선택자(selector) 간 공백은 **한 칸**으로 지정한다.
2. 속성(property)간 공백은 없어야 하며 **개행**으로 구분한다.
3. 선택자(selector)와 중괄호({ }) 간 공백은 **한 칸**으로 지정한다.
4. 중괄호({ })와 속성(property) 간 공백은 없어야하며 **개행**으로 구분한다.

<br/><br/>
## 7. 줄바꿈

&nbsp;&nbsp;&nbsp;&nbsp;선택자, 속성, 속성 값 사이 줄바꿈은 허용하지 않으며, 속성 간 줄바꿈은 해주어야 한다.
잘못된 예
