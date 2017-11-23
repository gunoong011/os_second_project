# 1. W3C validation
모바일에서 CSS는 사용 가능한 Hack과 CSS3 속성을 제외하고 W3C Validation을 통과해야 한다.

# 2. 영문 소문자 사용
모든 속성은 영문 소문자로만 작성한다.

# 3. 따옴표 사용 범위
W3C validation을 통과하는 범위안에서 따옴표 사용 제한은 없다.
예)
font-family: ‘Open Sans’;
font-family: “Open Sans”;
둘 다 허용

# 4. 들여쓰기
선택자들 간의 들여쓰기는 불허한다. 
예)
잘못된 예
.form{
	background: #FFFFFF;
}
	.form input{
		background: #f2f2f2;
	}
올바른 예
.form{
	background: #FFFFFF;
}
.form input{
	background: #f2f2f2;
}
선택자 안의 가독성을 위한 들여쓰기는 허한다.

# 5. 글꼴
모든 글꼴의 기본은 sans-serif이다.

# 6. 공백
1. 쉼표로 구분되는 선택자 간 공백은 한 칸으로 지정한다.
2. 속성간 공백은 없어야 하며 개행으로 구분한다.
3. 선택자와 중괄호 간 공백은 한 칸으로 지정한다.
4. 중괄호와 속성 간 공백은 없어야하며 개행으로 구분한다.

# 7. 줄바꿈
선택자, 속성, 속성 값 사이 줄바꿈은 허용하지 않으며, 속성 간 줄바꿈은 해주어야 한다.
잘못된 예
