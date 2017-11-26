<a href="value">속성</a>

[속성](#value)


# 1. 기본 규칙
## 1.1. W3C validation

&nbsp;&nbsp;&nbsp;&nbsp;모바일에서 CSS는 사용 가능한 Hack과 CSS3 속성을 제외하고 W3C Validation을 통과해야 한다.
<br/><br/>
## 1.2. 영문 소문자 사용

&nbsp;&nbsp;&nbsp;&nbsp;모든 속성은 영문 소문자로만 작성한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|.class{<br/>&nbsp;&nbsp;font-family: sans-serif;<br/>}|.class{<br/>&nbsp;&nbsp;**Font-Family**: sans-serif;<br/>}|

<br/><br/>
## 1.3. 따옴표 사용 범위
&nbsp;&nbsp;&nbsp;&nbsp;W3C validation을 통과하는 범위안에서 따옴표 사용 제한은 없다.<br/><br/>

|예시|
|---|
|font-family: ‘Open Sans';|
|font-family: "Open Sans";|
|둘 다 허용|

<br/><br/>
## 1.4. 세미콜론 사용
&nbsp;&nbsp;&nbsp;&nbsp;각 속성의 끝은 항상 세미콜론으로 끝을 맺는다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|.class{<br/>&nbsp;&nbsp;font-family: sans-serif;<br/>}|.class{<br/>&nbsp;&nbsp;font-family: sans-serif<br/>}|

<br/><br/>
## 1.5. 들여쓰기

&nbsp;&nbsp;&nbsp;&nbsp;선택자들(selectors) 간의 들여쓰기는 **불허**한다. 가독성을 위한 선택자 내 속성들간의 들여쓰기는 **허**한다. 들여쓰기의 공백은 space 2칸으로 통합한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|.form{<br/>&nbsp;&nbsp;background: #FFFFFF;<br/>}<br/>.form input{<br/>&nbsp;&nbsp;background : #F2F2F2;<br/>}|.form{<br/>&nbsp;&nbsp;background: #FFFFFF;<br/>}<br/>&nbsp;&nbsp;**.form input{<br/>&nbsp;&nbsp;&nbsp;&nbsp;background : #F2F2F2;<br/>&nbsp;&nbsp;}**|

<br/><br/>
## 1.5. 글꼴

&nbsp;&nbsp;&nbsp;&nbsp;다른 글꼴을 사용 할 수 있지만 글꼴의 기본은 **sans-serif** 로 정한다.

<br/><br/><hr/><br/><br/>

# 2. 공백
## 2.1. 선택자 간 공백

&nbsp;&nbsp;&nbsp;&nbsp;쉼표(,)로 구분되는 선택자(selector) 간 공백은 **한 칸**으로 지정한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html,&#94;body {<br/>&nbsp;&nbsp;margin: 0;<br/>}<br/>|**html,body** {<br/>&nbsp;&nbsp;margin: 0;<br/>}<br/>|

<br /><br />
## 2.2. 속성 간 공백
&nbsp;&nbsp;&nbsp;&nbsp;속성(property)간 공백은 없어야 하며 **개행**으로 구분한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body {<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|html, body {<br/>&nbsp;&nbsp;**margin: 0;padding: 0;**<br/>}<br/><br/>|

<br/><br/>
## 2.3. 선택자(selector)와 중괄호({ }) 간 공백
&nbsp;&nbsp;&nbsp;&nbsp;선택자(selector)와 중괄호({ }) 간 공백은 **한 칸**으로 지정한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body&#94;{<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|html, **body{**<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|

## 2.4. 속성(property)과 중괄호({ }) 간 공백
&nbsp;&nbsp;&nbsp;&nbsp;속성(property)과 중괄호({ }) 간 공백은 없어야하며 **개행**으로 구분한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body {<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|html, body **{margin:** 0;<br/>&nbsp;&nbsp;**padding: 0;}**<br/><br/><br/>|

<br/><br/><hr/><br/><br/>

# 3. 줄바꿈

&nbsp;&nbsp;&nbsp;&nbsp;선택자, 속성 값 사이 줄바꿈은 **불허**하며, **속성 간 줄바꿈**은 해주어야 한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body {<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/><br/><br/><br/>|**html,<br/>body**{<br/>&nbsp;&nbsp;margin: <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0;<br/>&nbsp;&nbsp;padding:<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0;<br/>}<br/>|

<br/><br/><hr/><br/><br/>

# 4. 선택자(selector)

&nbsp;&nbsp;&nbsp;&nbsp;W3C validation을 통과하는 범위안에서 선택자(selector)사용에 대한 제한은 없다.

<br/><br/><hr/><br/><br/>

# <div id="value">5.속성</div>
## 5.1. 속성 선언 순서

&nbsp;&nbsp;&nbsp;&nbsp;속성을 선언할 때 표기된 순서를 참고하여 선언한다.<br/><br/>

|순서|속성|관련속성|
|----|----|--------|
|1	 |display|visibility|
|2	 |overflow|-|
|3	 |float|clear|
|4	 |position|top, right, bottom, left, z-index|
|5	 |width, height|-|
|6	 |margin, padding|-|
|7	 |border|-|
|8	 |background|-|
|9	 |font|color, letter-spacing, text-align, text-decoration, text-indent, vertical-align, white-space 등|
|10	 |animation|animation, transform, transition, marquee 등|
|11	 |etc|언급되지않은 나머지 속성들|

<br/><br/><hr/><br/><br/>


