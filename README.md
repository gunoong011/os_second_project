
## 프로젝트에 대해서

카드 컨텐츠 제작 및 유통을 하는 웹페이지를 제작하는 프로젝트 입니다.

---

## 라이선스 

* 배포 라이선스 : [Apache License, Version 2.0](https://github.com/gunoong011/os_second_project/blob/master/LICENSE)

* [NOTICE](https://github.com/gunoong011/os_second_project/blob/master/NOTICE.txt) 

---

## 사용한 라이브러리 

[Library We Use](https://github.com/gunoong011/os_second_project/blob/master/modify/Libraries_we_use_by_noh.md) 를 확인하여 주시기 바랍니다

---

## 개발 당시 환경 

OS : OSX 10.12.6

HTML : Version 5.0 

CSS : Version 3.0 

---

## 언어별 코딩 컨벤션 

이 프로젝트에서 지키는 코딩 컨벤션입니다

* [HTML STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/html_rule.md)

* [CSS STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/css_rules.md)

* [JAVA SCRIPT STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md)

---

## 웹사이트를 사용하기 전에 

<strong> bundle 설치 방법 </strong> 

(1) for mac os

터미널에서 아래의 명령어를 실행해 주세요.

    $ gem install bundler

만약 아래와 같이 권한이 없다고 뜬다면 

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.26.20.png">

아래의 명령어로 다시한번 설치를 해주시기 바랍니다.

    $ sudo gem install bundler

그런 다음 비밀번호를 입력하면 다음과 같이 설치과 완료될 것입니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.26.55.png">


(2) for windows os

---

<strong> bundle 열기 </strong> 

create 기능을 사용하기 위해서는 bundle을 열어야 합니다.

bundle install을 하지 않았다면 위를 참고하여 install 하여 주시기 바랍니다.

bundle install을 했다면 meme폴더로 이동후 폴더 내부에서 아래의 명령어를 실행시키십시오.

    $ bundler exec middleman

그럼 아래와 같이 서버가 열리게 되고 create기능을 사용할 수 있습니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.23.57.png">


---

## 웹사이트 기능에 대해

(1) create 기능 

배경 사진 넣기
-----------
create에 들어오면 다음과 같은 화면을 보게됩니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.24.59.png">

배경사진을 설정하기 위해서는 아래의 "Drog image here"에 이미지를 드래그하여 넣어주세요.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.59.53.png">
 
배경사진을 드래그해서 넣었으면 밑에 있는 "Resize image"를 통해 크기를 조절할 수 있습니다.




제목 작성
-------------

카드뉴스의 제목은 "Headline"을 통해 작성을 할 수 있습니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.04.48.png">

꾸미기
-------------

제목을 작성하였으면 밑에 있는 메뉴들로 수정이 가능합니다.

순서대로

1. 대략적 위치
2. 텍스트의 크기
3. 글씨체

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.06.21.png">

내용 작성
-------------

credit을 통해 카드뉴스의 내용 작성이 가능합니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.16.20.png">


배경 색
-------------

overlay를 통해 배경의 색을 선택할 수 있습니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.16.20.png">

다운로드
-------------

카드뉴스가 완성되었다면 "Download & upload image"를 클릭 하시면 다운 받을수 있습니다.

<img src = "https://github.com/nickjw0205/for-image-upload/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202017-11-24%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.58.08.png">



## 개발 참여 방법 안내서

[개발 참여 방법 안내서]
