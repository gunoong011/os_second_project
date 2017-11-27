# Developer Communication ways

## 시작하기에 앞서

코드를 수정해서 반영할 시에는 저희 프로젝트에서 준수하는 언어별 코딩컨벤션을 지켜주시길 바랍니다

<strong> 언어별 코딩 컨벤션</strong>

* [HTML STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/html_rule.md)

* [CSS STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/Kimsun.md)

* [JAVA SCRIPT STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/Hong.md)

----


## 개발 참여 방법 

### 첫번째 방법 

1. 먼저 gunoong011/os_second_project repository 를 `Fork` 해주세요 

(사진- Fork를 가리키는)

2. master branch 외에 각자만의 branch를 따로 만들어주세요 

예시) `git branch` 명령어를 사용하여 branch를 만든 경우 

	$  git branch your_branch_name

your_branch_name에 자신이 만들려는 branch 이름을 넣어 만들어준다

위의 명령어로 각자만의 branch 를 만든 후에 만든 branch 로 이동하려면 

	$  git checkout your_branch_name 

위 명령어를 사용하면 된다

3. 각자의 branch 에서 자유롭게 변경 내용을 작성합니다.

4. 수정하거나 새로 반영된 변경사항을 `commit` 하여 변경 내용을 반영해 줍니다 

5. 변경사항을 gunoong011/os_second_project 에 반영하고 싶은 경우 `pull request`를 보냅니다


```{.no-highlight}

base fork : gunoong011/os_second_project 

base : master 

head fork : your fork repository 

compare : your_branch_name

```

head fork에 각자 repository 이름을 compare 에는 각자 branch 이름을 적고 `pull request`를 만들어주면 됩니다

6. 이렇게 보내신 pull request를 repository 관리자가 최종적으로 변경사항을 검토할 것입니다
