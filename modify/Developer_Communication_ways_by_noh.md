# 개발 참여 방법 안내서

## 시작하기에 앞서

코드를 수정해서 반영할 시에는 저희 프로젝트에서 준수하는 언어별 코딩컨벤션을 지켜주시길 바랍니다

<strong> 언어별 코딩 컨벤션</strong>

* [HTML STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/html_rule.md)

* [CSS STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/Kimsun.md)

* [JAVA SCRIPT STYLE GUIDE](https://github.com/gunoong011/os_second_project/blob/master/modify/JavaScript_Rule.md)

----


## 개발 참여 방법 

### 첫번째 방법 

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

---

### 두번째 방법 

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
