ERICAST HTML Style Guide
===========================

# 목차

&nbsp;&nbsp;**0. [W3C Validation](#w3c)<br/>**
&nbsp;&nbsp;**1. [들여쓰기](#indent)<br/>**
&nbsp;&nbsp;**2. [기본 네이밍](#naming)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.1. [일반 규칙](#basic_rule)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.2. [시작 이름](#begin)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.3. [약속어](#comp)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;2.4. [영어 소문자, 숫자, 언더바(\_)](#combi)<br/>**
&nbsp;&nbsp;**3. [id 및 class 네이밍](#id_class_naming)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;3.1. [id, class](#idNclass)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;3.2. [레이아웃 약속어](#layout_comp)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;3.3. [레이아웃 네이밍 조합](#layout_combi)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;3.4. [객체 네이밍](#object_naming)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;3.5. [class 네이밍 확장](#naming_ext)<br/>**
&nbsp;&nbsp;**4. [이미지 네이밍](#img_naming)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;4.1. [이미지 네이밍](#img)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;4.2. [이미지 네이밍 조합](#img_combi)<br/>**
&nbsp;&nbsp;**5. [파일 및 폴더 네이밍](#file_folder_naming)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;5.1. [파일 및 폴더 네이밍](#file_folder)<br/>**
&nbsp;&nbsp;**&nbsp;&nbsp;&nbsp;&nbsp;5.2. [파일 및 폴더 네이밍 조합](#file_folder_combi)<br/>**
<br/><br/><hr/>

## <div id="w3c">0. W3C Validation</div>

&nbsp;&nbsp;&nbsp;&nbsp;모든 HTML 파일은 [W3C Validation](https://validator.w3.org/#validate_by_uri)에서 통과하여 **오류**가 없어야한다.

<br/><br/><hr/><br/><br/>

## <div id="indent">1. 들여쓰기</div>

&nbsp;&nbsp;&nbsp;&nbsp;들여쓰기는 텝(tab)이 아닌 **space 2칸**으로 한다.<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|&#60;li><br/>&nbsp;&nbsp;&#60;a href='#'><br/>&#60;/li>|&#60;li><br/>&nbsp;&nbsp;&nbsp;&nbsp;&#60;a href='#'><br/>&#60;/li>|


## <div id="naming">2. 기본 네이밍</div>
### <div id="basic_rule">2.1. 일반 규칙</div>

&nbsp;&nbsp;&nbsp;&nbsp;이름은 영문 소문자, 숫자, 언더스코어(\_)로 작성한다.

<br/>

### <div id="begin">2.2. 시작 이름</div>

&nbsp;&nbsp;&nbsp;&nbsp;이름은 **영문 소문자**로만 시작할 수 있다. *단, 주석문은 영문 대문자를 허용한다.*<br/><br/>

|올바른 예|잘못된 예|
|--------|--------|
|btn|Btn|
|btn2|2btn|
|btn|_btn|
|btn|btn_|

<br/>

### <div id="comp">2.3. 약속어</div>

&nbsp;&nbsp;&nbsp;&nbsp;레이아웃 약속어, 객체 약속어, 이미지 약속어에 근거하여 작성한다. 다만, 약속어가 없으면 종류와 특성을 나타내도록 네이밍하거나 공통 네이밍 약속어를 작성한다.

<br/>

### <div id="combi">2.4. 영어 소문자, 숫자, 언더바(\_)</div>

&nbsp;&nbsp;&nbsp;&nbsp;1) 영문 소문자, 숫자, 언더바(\_)만 사용할 수 있다.<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;2) 언더바(\_)는 **단어와 단어 조합**할 때만 사용한다.<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;3) 언더바(\_)가 포함된 약속어는 숫자, 영문 소문자와 조합하여 사용할 수 있다.<br/>

<br/>

|올바른 예|잘못된 예|
|--------|--------|
|section_list|**S**ectionList|
|no1, no2, no3 …. no10||

<br/><br/><hr/><br/><br/>

## <div id="id_class_naming">3. id 및 class 네이밍</div>
### <div id="idNclass">3.1. id, class</div>

&nbsp;&nbsp;&nbsp;&nbsp;1) id는 문서 전체의 고유 식별자 이므로 한 문서에서 동일한 id를 여러 번 사용하지 않는다.<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;2) 레이아웃을 제외한 id는 스타일을 지정하지 않는다.<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;3) class는 문서에서 여러 번 사용할 수 있다.<br/>

<br/>

### <div id="layout_comp">3.2. 레이아웃 약속어</div>

&nbsp;&nbsp;&nbsp;&nbsp;레이아웃에는 예약된 id만 사용한다.<br/><br/>
 
|약속어|범위|
|--------|--------|
|#wrap|페이지 전체 영역|
|#header |머리글 영역 |
|#container |본문 영역 |
|#content |주요 콘텐츠 영역 |
|#footer |바닥글 영역 |

<br/>

### <div id="layout_combi">3.3. 레이아웃 네이밍 조합</div>

&nbsp;&nbsp;&nbsp;&nbsp;레이아웃에 디자인 속성을 추가/변경하려면 class를 사용한다.

<br/>

### <div id="object_naming">3.4. 객체 네이밍</div>

&nbsp;&nbsp;&nbsp;&nbsp;1) 객체는 class만 사용할 수 있으며, 전사 공통 마크업 템플릿의 class와 중복되지 않아야 한다.<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;2) 개발과 연동되는 동적 객체도 class만 사용한다.<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;3) 팝업, iframe에도 동일한 규칙을 적용한다.<br/><br/>

|분류|약속어|영역/객체|
|:----:|:------:|---------|
|(공통) | .gnb | 최상위 전역 내비게이션 영역|
|(공통) | .sta | 서비스 이름, 연관 서비스, 검색 영역|
|(공통) | .lnb_ | 현재 서비스의 지역 내비게이션 영역|
|(공통) | .snb_ | 측면 내비게이션 영역|
|(공통) | .aside_ | 문서의 주요 부분을 표시하고 남은 콘텐츠 영역|
|(공통) | .spot_ | 강조하는 상위 콘텐츠 영역|
|(공통) | .path_ | 현재 페이지의 경로|
|(공통) | .nav_ | 내비게이션 요소|
|(공통) | .ad_ | 광고 요소|
|(공통) | .paginate | 페이지 목록 요소|
|(공통) | .ly | 레이아웃 요소|
|(공통) | #u_skip | 스킵네비게이션|
|(공통) | .blind | 숨김영역|
|(공통) | .u_ | 공통요소|
|(그루핑) | .section_   heading | 태그(h1~h6)를 포함한 요소들의 그루핑|
|(그루핑) | .group_ section | 보다 낮은 단계의 heading 태그를 포함한 요소들의 그루핑|
|(그루핑) | ._area | 위치에 제한이 없는 특정 기능을 수행하는 요소들의 그루핑|

<br/>

### <div id="naming_ext">3.5. class 네이밍 확장</div>

&nbsp;&nbsp;&nbsp;&nbsp;1) 종속 확장 class : 기본형 class에 종속되어 여백, 색깔, 행간 등의 몇 가지 속성을 부여하고 할 때 사용하는 class<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;2) 독립 확장 class : 기본형 class의 변형이 타입으로 분류할 만큼 클 경우 사용하는 class
 
<br/>

|기본형|확장형|설명|
|------|------|----|
|mykin_list|mykin_list_v1, mykin_list_v2...| 종속 확장  class|
|mykin_list|mykin_list2, mykin_list3 |독립 확장 class|

<br/><br/><hr/><br/><br/>

## <div id="img_naming">4. 이미지 네이밍</div>
### <div id="img">4.1. 이미지 네이밍</div>

&nbsp;&nbsp;&nbsp;&nbsp;1) 같은 분류의 이미지가 두 개 이상이면 **파일 이름 마지막에 숫자**를 추가하여 구분한다.<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;2) 이미지 네이밍은 이미지 확장자와 관계 없이 **순차적**으로 적용한다. 예) bu_dot1.git, 
bu_dot2.jpg, bu_dot3.png<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;3) **임시 이미지**는 tmp_를 조합한다. 예) tmp_myeonguni.png<br/><br/>
&nbsp;&nbsp;&nbsp;&nbsp;4) 이미지 약속어는 다음 약속어 분류에 근거하여 작성한다.

<br/>

|약속어|분류|
|------|----|
|h_ | 제목|
|p_ | 문장|
|gnb_, lnb_, snb_ | 내비게이션|
|tab_ | 탭|
|btn_ | 버튼|
|bu_ | 볼릿|
|ico_ | 아이콘|
|line_ | 선|
|bg_ | 배경, 박스|
|img_ | 이미지|
|_off, _over, _on | 상태 변화|
|ad_ | 광고|
|tmp_ | 임시|
|sp_ | 스프라이트 이미지|

<br/>

### <div id="img_combi">4.2. 이미지 네이밍 조합</div>

&nbsp;&nbsp;&nbsp;&nbsp;이미지 이름은 '**형태, 의미, 상태**' 순서로 조합한다.<br/><br/>

|올바른 예|잘못된 예|설명|
|---------|---------|----|
| tab1_recomm_on |on_recommend_tab1 | '형태_의미_상태' 순서로 조합한다.|
| btn_naver_mail.gif |bnm.gif | 임의로 축약하지 않는다.|
| btn_srch.gif |btn_Search.gif | 영문 소문자를 사용한다.|
| btn_srch.gif |1btn_search.gif | 숫자로 시작하지 않는다.|

<br/><br/><hr/><br/><br/>

## <div id="file_folder_naming">5. 파일 및 폴더 네이밍</div>
### <div id="file_folder">5.1. 파일 및 폴더 네이밍</div>

&nbsp;&nbsp;&nbsp;&nbsp;다음 분류와 예제를 따른다.

<br/>

### <div id="file_folder_combi">5.2. 파일 및 폴더 네이밍 조합</div>

&nbsp;&nbsp;&nbsp;&nbsp;HTML 파일은 '**메뉴이름**'으로 작성한다.<br/><br/>

|분류 | 조합 예 | 설명|
|-----|---------|-----|
|(HTML)|news.html|'메뉴이름'으로 작성한다.|

<br/>
