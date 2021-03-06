# ERICAST
[![travis-ci badge](https://travis-ci.org/gunoong011/os_second_project.svg?branch=master)](https://travis-ci.org)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/gunoong011/os_second_project/blob/master/LICENSE)


## 목차 

&nbsp;&nbsp;1.  [프로젝트에 대해서](#about_project)<br>
<br>
&nbsp;&nbsp;2.  [프로젝트 라이선스](#project_license)<br>
<br>
&nbsp;&nbsp;3.  [사용한 라이브러리](#use_library)<br>
<br>
&nbsp;&nbsp;4.  [개발 당시 환경](#enviroment)<br>
<br>
&nbsp;&nbsp;5.  [언어별 코딩 컨벤션](#language_coding)<br>
<br>
&nbsp;&nbsp;6.  [웹사이트를 사용하기 전에](#before_using)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6.1.  [bundle 설치 방법](#install_bundler)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6.2.  [bundle 열기](#open_bundler)<br>
<br>
&nbsp;&nbsp;7.  [웹사이트 기능에 대해](#about_website)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.1.  [create 기능](#create_function)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.2.  [login 기능](#login_function)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.3.  [upload 기능](#upload_function)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.4.  [share 기능](#share_function)<br>
<br>
&nbsp;&nbsp;8.  [개발 참여 방법 안내서](#information)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8.1.  [첫번째 방법](#first_way)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8.2.  [두번째 방법](#second_way)<br>

---

## <div id ="about_project"> 1. 프로젝트에 대해서</div>

*ERICAST*

카드 컨텐츠를 제작하고 유통하는 웹페이지를 만드는 프로젝트 입니다

본 프로젝트는 대학교 오픈소스 프로젝트의 일환으로 진행된 프로젝트 중 하나입니다

---

## <div id ="project_license">2. 프로젝트 라이선스 </div>

* 배포 라이선스 : [Apache License, Version 2.0](https://github.com/gunoong011/os_second_project/blob/master/LICENSE)

* [NOTICE](https://github.com/gunoong011/os_second_project/blob/master/NOTICE.txt) 

위 두가지를 꼭 읽어주시어 라이선스에 착오가 없으시길 바랍니다


---

## <div id = "use_library">3. 사용한 라이브러리 </div>

1. [Flat HTML5/CSS3 LOGIN Form](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#1-flat-html5css3-login-form)

2. [How to Make a Website](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#2-how-to-make-a-website)

3. [Knockout Files Bindings with upload preview and drag & drop](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#3-knockout-files-bindings-with-upload-preview-and-drag--drop)

4. [RRSSB](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#4-rrssb)

5. [Bundler](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#5-bundler)

6. [jQuery](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#6-jquery)

7. [Slides](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#7-slidesjs)

8. [Meme](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md#8-meme)

[Library We Use](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md) 로 들어가시면 통합된 형태로 확인할 수 있습니다


---

## <div id ="enviroment">4. 개발 당시 환경</div> 

당시 개발자의 개발 환경 입니다

OS : OSX 10.12.6

HTML : Version 5.0 

CSS : Version 3.0 

---

## <div id ="language_coding">5. 언어별 코딩 컨벤션 </div>

이 프로젝트에서 지키는 코딩 컨벤션입니다 

코드를 수정할 시에 이 내용을 꼭 확인하여 주시길 바랍니다

* [HTML STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/html_rule.md)

* [CSS STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/css_rules.md)

* [JAVASCRIPT STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md)

---


## <div id = "before_using">6. 웹사이트를 사용하기 전에 </div>

웹사이트를 사용하기 전에 필요한 요소들을 설치하는 방법입니다

### <div id = "install_bundler">6.1. bundle 설치 방법 </div>

**for mac os**

터미널에서 아래의 명령어를 실행해 주세요.

    $ gem install bundler

만약 아래와 같이 권한이 없다고 뜬다면 

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.26.20.png">

아래의 명령어로 다시한번 설치를 해주시기 바랍니다.

    $ sudo gem install bundler

그런 다음 비밀번호를 입력하면 다음과 같이 설치과 완료될 것입니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.26.55.png">



### <div id ="open_bundler">6.2. bundle 열기</div> 

create 기능을 사용하기 위해서는 bundle을 열어야 합니다.

bundle install을 하지 않았다면 위를 참고하여 install 하여 주시기 바랍니다.

bundle install을 했다면 meme폴더로 이동후 폴더 내부에서 아래의 명령어를 실행시키십시오.

    $ bundler exec middleman

그럼 아래와 같이 서버가 열리게 되고 create기능을 사용할 수 있습니다.

<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.23.57.png">
</kbd>
---

## <div id ="about_website">7. 웹사이트 기능에 대해</div>

### <div id ="create_function">7.1. create 기능 </div>

**(1) 배경 사진 넣기**

create에 들어오면 다음과 같은 화면을 보게됩니다.

<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.24.59.png">
</kbd>
<br>
<br>

배경사진을 설정하기 위해서는 아래의 "Drog image here"에 이미지를 드래그하여 넣어주세요.

<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.59.53.png">
</kbd>
<br>
<br>
 
배경사진을 드래그해서 넣었으면 밑에 있는 "Resize image"를 통해 크기를 조절할 수 있습니다.


**(2) 제목 작성**

카드뉴스의 제목은 "Headline"을 통해 작성을 할 수 있습니다.

<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.04.48.png" border="10">
</kbd>
<br>
<br>

**(3)꾸미기**

제목을 작성하였으면 밑에 있는 메뉴들로 수정이 가능합니다.

순서대로

1. 대략적 위치
2. 텍스트의 크기
3. 글씨체


<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.06.21.png">
</kbd>
<br>
<br>

**(4)내용 작성**

credit을 통해 카드뉴스의 내용 작성이 가능합니다.

<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.16.20.png">
</kbd>
<br>
<br>

**(5)배경 색**

overlay를 통해 배경의 색을 선택할 수 있습니다.

<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.16.20.png">
</kbd>
<br> 
<br>

**(6)다운로드**

카드뉴스가 완성되었다면 "Download & upload image"를 클릭 하시면 다운 받을수 있습니다.

<kbd>
<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-24%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.58.08.png">
</kbd>
<br>
<br>

### <div id = "login_function"> 7.2.login 기능 </div>
<kbd>
<img src ="https://github.com/Kimsohyun93/image/blob/master/LOGIN.PNG" width = "40%" heigh = "30%"> 
</kbd>
<br>
<br>
LOGIN 버튼 클릭 시 아이디와 비밀번호를 입력 할 수 있는 팝업창이 뜹니다.<br/>
등록이 안되어 있다면 아래  **create an account** 버튼으로 계정을 만들 수 있습니다.
*아직 실제로 기능 구현은 되지 않습니다.*

### <div id ="upload_function"> 7.3. upload 기능 </div>
<kbd>
<img src ="https://github.com/Kimsohyun93/image/blob/master/UPLOAD.PNG" width = "60%" heigh = "60%" >
</kbd>
<br>
<br>
CREATE 페이지에서 직접 제작한 카드뉴스를 **페이지에 업로드** 할 수 있습니다.  
파일을 **드래그** 하여 선택하거나 **chosse file 버튼**을 통해 선택할 수 있습니다.  
파일이 선택되면 upload버튼으로 카드뉴스를 업로드 할 수 있습니다.  

### <div id = "share_function"> 7.4. share 기능 </div>
<kbd>
<img src = "https://github.com/Kimsohyun93/image/blob/master/CARDNEWS.PNG" width = "80%" heigh = "80%"> 
</kbd>
<br>
<br>
카드뉴스 위의 버튼으로 페이스북과 트위터로 공유할 수 있습니다.

---


## <div id ="information">8. 개발 참여 방법 안내서</div>

개발 참여 방법 안내를 위한 안내서 입니다 

꼭 읽어주시어 참여해주시길 부탁드립니다

### <div id = "first_way">8.1. 첫번째 방법</div> 

<strong> Fork & pull request를 이용하여 참여하기</strong>

<storng> (1) 먼저 [gunoong011/os_second_project repository](https://github.com/gunoong011/os_second_project)에서 `Fork` 버튼을 클릭해 `Fork`해주세요</storng>

<p align ="center">
<img src ="https://github.com/gunoong011/test_demo/blob/master/image_test/real_fork.png">
</p>

<storng> (2) master branch 외에 각자만의 branch를 따로 만들어주세요 </storng>

예시) `git branch` 명령어를 사용하여 branch를 만든 경우 

	$  git branch your_branch_name

your_branch_name에 자신이 만들려는 branch 이름을 넣어 만들어줍니다

위의 명령어로 각자만의 branch 를 만든 후에 만든 branch 로 이동하려면 

	$  git checkout your_branch_name 

위 명령어를 사용하면 됩니다

<storng> (3) 각자의 branch 에서 자유롭게 변경 내용을 작성합니다.</storng>

<storng> (4) 수정하거나 새로 반영된 변경사항을 `commit` 하여 변경 내용을 반영해 줍니다 </storng>

<storng> (5) 변경사항을 [gunoong011/os_second_project](https://github.com/gunoong011/os_second_project) 에 반영하고 싶은 경우 `pull request`를 보냅니다</storng>


```{.no-highlight}
base fork : gunoong011/os_second_project 

base : master 

head fork : your fork repository 

compare : your_branch_name
```

head fork에 각자 repository 이름을 compare 에는 각자 branch 이름을 적고 `pull request`를 만들어주면 됩니다

<storng> (6) 이렇게 보내신 `pull request`를 repository 관리자가 최종적으로 변경사항을 검토하여 반영여부를 결정할 것입니다</storng>


### <div id ="second_way">8.2. 두번째 방법 </div>

직접 변경 내용을 작성하지 않고 단순히 의견을 보내주는 방법입니다

<strong>`issue` 작성하기</strong>

<storng> (1) [gunoong011/os_second_project](https://github.com/gunoong011/os_second_project)에서 `issue` 를 클릭합니다</storng>

<p align ="center">
<img src ="https://github.com/gunoong011/test_demo/blob/master/image_test/create_issue2.png">
</p>

<storng> (2) `new issue` 를 클릭하여 새로운 이슈를 작성합니다</storng>

<p align ="center">
<img src ="https://github.com/gunoong011/test_demo/blob/master/image_test/new_issue3.png">
</p>

<storng> (3) `issue` 작성하기 </storng>

<p align ="center">
<img src ="https://github.com/gunoong011/test_demo/blob/master/image_test/issue_write.png">
</p>

* `Title`에 제목을 작성합니다 

* `Write`를 클릭하고 `Leave a comment` 자리에 의견을 작성할 수 있습니다 ([Markdown 문법](https://gist.github.com/ihoneymon/652be052a0727ad59601)을 사용하여 작성합니다)

* `Assigness` 에는 이 `issue`를 봐야하는 사람들을 클릭합니다 

* `Labels` 을 클릭하여 자신의 `issue`가 어느 범위에 들어가는지 확인하고 해당 사항을 클릭해줍니다

* `Label` 예시 : `bug`, `create`, `duplicate`, `enhancement`,`question` 

<storng> (4) `submit new issue` 를 눌러 `issue`를 제출합니다</storng>

위 내용은 [개발 참여 방법 안내서 전문](https://github.com/gunoong011/os_second_project/blob/master/modify/Developer_Communication_ways_by_noh.md)에서도 확인할 수 있습니다
