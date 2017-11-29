ERICAST CSS Style Guide
===========================

# 목차

&nbsp;&nbsp;**1. [기본규칙](#basic_rules)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;1.1. [W3C Validation](#valid)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;1.2. [영문 소문자 사용](#text)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;1.3. [따옴표 사용 범위](#quote)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;1.4. [세미콜론 사용](#semicolon)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;1.5. [들여쓰기](#indent)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;1.6. [글꼴](#font)<br/>**
&nbsp;&nbsp;**2. [공백](#space)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.1. [선택자 간 공백](#space_bw_selecs)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.2. [속성 간 공백](#space_bw_props)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.3. [선택자와 중괄호 간 공백](#space_bw_selecNbrace)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.4. [속성과 중괄호 간 공백](#spcae_bw_propNbrace)<br/>**
&nbsp;&nbsp;**3. [줄바꿈](#newline)<br/>**
&nbsp;&nbsp;**4. [선택자](#selecs)<br/>**
&nbsp;&nbsp;**5. [속성](#property)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;5.1. [속성 선언 순서](#prop_order)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;5.2. [속성 값 축약](#prop_simpl)<br/>**
&nbsp;&nbsp;**6. [주석](#comment)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;6.1. [기본 형식](#comment_basic)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;6.2. [작성자 정보 표기](#author_info)<br/>**
<br/><br/><hr/>

## <div id="basic_rules">1. 기본 규칙</div>
### <div id="valid">1.1. W3C Validation</div>

&nbsp;&nbsp;&nbsp;&nbsp;모바일에서 CSS는 사용 가능한 Hack과 CSS3 속성을 제외하고 [W3C Validation](http://jigsaw.w3.org/css-validator/#validate_by_uri)을 통과해야 한다.

<br/>

### <div id="text">1.2. 영문 소문자 사용</div>

&nbsp;&nbsp;&nbsp;&nbsp;모든 속성은 **영문 소문자**로만 작성한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|.class{<br/>&nbsp;&nbsp;font-family: sans-serif;<br/>}|.class{<br/>&nbsp;&nbsp;**Font-Family**: sans-serif;<br/>}|

<br/>

### <div id="quote">1.3. 따옴표 사용 범위</div>
&nbsp;&nbsp;&nbsp;&nbsp;W3C validation을 통과하는 범위안에서 따옴표 **사용 제한은 없다.**<br/><br/>

|예시|
|---|
|font-family: ‘Open Sans';|
|font-family: "Open Sans";|
|둘 다 허용|

<br/>

### <div id="semicolon">1.4. 세미콜론 사용</div>
&nbsp;&nbsp;&nbsp;&nbsp;각 속성의 끝은 항상 **세미콜론으로 끝**을 맺는다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|.class{<br/>&nbsp;&nbsp;font-family: sans-serif;<br/>}|.class{<br/>&nbsp;&nbsp;font-family: sans-serif<br/>}|

<br/>

### <div id="indent">1.5. 들여쓰기</div>

&nbsp;&nbsp;&nbsp;&nbsp;선택자들(selectors) 간의 들여쓰기는 **불허**한다. 가독성을 위한 선택자 내 속성들간의 들여쓰기는 **허**한다. 들여쓰기의 **공백은 space 2칸**으로 통합한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|.form{<br/>&nbsp;&nbsp;background: #ffffff;<br/>}<br/>.form input{<br/>&nbsp;&nbsp;background : #f2f2f2;<br/>}|.form{<br/>&nbsp;&nbsp;background: #ffffff;<br/>}<br/>**&#94;&#94;.form input{<br/>&#94;&#94;&#94;&#94;background : #f2f2f2;<br/>&#94;&#94;}**|

<br/>

### <div id="font">1.6. 글꼴</div>

&nbsp;&nbsp;&nbsp;&nbsp;다른 글꼴을 사용 할 수 있지만 글꼴의 기본은 **sans-serif** 로 정한다.

<br/><br/><hr/><br/><br/>

## <div id="space">2. 공백</div>
### <div id="space_bw_selecs">2.1. 선택자 간 공백</div>

&nbsp;&nbsp;&nbsp;&nbsp;쉼표(,)로 구분되는 선택자(selector) 간 공백은 **한 칸**으로 지정한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html,&#94;body {<br/>&nbsp;&nbsp;margin: 0;<br/>}<br/>|**html,body** {<br/>&nbsp;&nbsp;margin: 0;<br/>}<br/>|

<br />

### <div id="space_bw_props">2.2. 속성 간 공백</div>
&nbsp;&nbsp;&nbsp;&nbsp;속성(property)간 공백은 없어야 하며 **개행**으로 구분한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body {<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|html, body {<br/>&nbsp;&nbsp;**margin: 0;padding: 0;**<br/>}<br/><br/>|

<br/>

### <div id="space_bw_selecNbrace">2.3. 선택자(selector)와 중괄호({ }) 간 공백</div>
&nbsp;&nbsp;&nbsp;&nbsp;선택자(selector)와 중괄호({ }) 간 공백은 **한 칸**으로 지정한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body&#94;{<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|html, **body{**<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|

<br/>

### <div id="spcae_bw_propNbrace">2.4. 속성(property)과 중괄호({ }) 간 공백</div>
&nbsp;&nbsp;&nbsp;&nbsp;속성(property)과 중괄호({ }) 간 공백은 없어야하며 **개행**으로 구분한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body {<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/>|html, body **{margin:** 0;<br/>&nbsp;&nbsp;**padding: 0;}**<br/><br/><br/>|

<br/><br/><hr/><br/><br/>

## <div id="newline">3. 줄바꿈</div>

&nbsp;&nbsp;&nbsp;&nbsp;선택자, 속성 값 사이 줄바꿈은 **불허**하며, **속성 간 줄바꿈**을 적용한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|html, body {<br/>&nbsp;&nbsp;margin: 0;<br/>&nbsp;&nbsp;padding: 0;<br/>}<br/><br/><br/><br/>|html,<br/>body{<br/>&nbsp;&nbsp;margin: <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0;<br/>&nbsp;&nbsp;padding:<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0;<br/>}<br/>|

<br/><br/><hr/><br/><br/>

## <div id="selecs">4. 선택자(selector)</div>

&nbsp;&nbsp;&nbsp;&nbsp;W3C validation을 통과하는 범위 안에서 선택자(selector)사용에 대한 **제한은 없다.**

<br/><br/><hr/><br/><br/>

## <div id="property">5. 속성</div>
### <div id="prop_order">5.1. 속성 선언 순서</div>

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

<br/>

### <div id="prop_simpl">5.2. 속성 값 축약</div>

&nbsp;&nbsp;&nbsp;&nbsp;각 속성들의 값은 아래의 표와 같은 경우 축약할 수 있다.<br/><br/>

|축약 전|축약 후|설명|
|-------|-------|----|
|left: 0px;|left: 0;|값이 0일 경우 단위를 생략한다.|
|margin: 5px 5px 5px 5px;<br/>margin: 0 auto 0 auto;<br/>margin: 30px 50px 40px 50px;|margin: 5px;<br/>margin: 0 auto;<br/>margin: 30px 50px 40px;|동일한 속성 값(상, 우, 하, 좌)일 경우 축약한다.|

<br/><br/><hr/><br/><br/>

## <div id="comment">6. 주석</div>
### <div id="comment_basic">6.1. 기본 형식</div>

&nbsp;&nbsp;&nbsp;&nbsp;주석의 형식은 기본적으로 `/* */` 을 사용한다. 주석에 대한 제한은 없다.

<br/>

### <div id="author_info">6.2. 작성자 정보 표기</div>

&nbsp;&nbsp;&nbsp;&nbsp;css 파일의 최상단에 작성자에 대한 정보를 **1회 작성**한다. 작성자 정보에는 **소속, 이름, 수정날짜**를 작성한다. 기존 작성자와 다른 작성자라면 기존 작성자의 정보 아래에 자신의 정보를 작성한다.

<br/>
