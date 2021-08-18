# Front-End 개발
SSAC 수업내용 기록

## 표기법
- 사용자가 이름을 지정하는 경우
- 여러 단어를 사용해서 이름을 지정하는 경우
- 공백 대신에 단어와 단어 구분
```
html-css : kebab case

html_css : snake case - Python

htmlCss : camel case - JavaScript, JAVA, C, C++

HtmlCss : Pascal case - JavaScript, JAVA, C, C++ ( Class )

* Front End
- HTML( class / id ) : kebab case
- File/Folder name : snake case
- JS : camel case
- JS ( class ) : Pascal case
```

## HTML
* HTML Introduction
 https://www.w3schools.com/html/html_intro.asp

> 웹페이지 구조 표시
> 
> 웹페이지 콘텐츠 표시
>  - 텍스트 콘텐츠
>  - 멀티미디어 콘텐츠 : 이미지, 비디오, 오디오

```
<tagname> CONTENTS </tagname>

** 시작태그만 있는 Element : Empty element
```

### HTML Element
https://www.w3schools.com/html/html_elements.asp

> 포함관계 
> - 기준에 따라서 조상요소(Ancestor), 부모요소(Parent), 자식요소(Child), 자손요소(Decendant)

```
<html>
  <body>
    <h1>Web page</h1>
  </body>
</html>

* html : body의 부모요소, h1의 조상요소

* body : html의 자식요소, h1의 부모요소

* h1 : html의 자손요소, body의 자식요소
```
