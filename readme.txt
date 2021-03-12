1. vs환경설정
   각종 익스텐션을 설치해보자
   프리티어, 오토(클로즈,리네임)태그, eslint, css peek 는 기본이다.

   Settings Sync(환경세팅을 깃헙에 올려놓음)
   
   prettier-Code formatter
   Auto Close Tag
   Auto Rename Tag
   
   css peek(ctrl+css 클릭)
   stylelint(css문법체크)

   Highlight Matching Tag(html tag match)
   Bracket Pair Colorizer(js 괄호 match)
   indent-rainbow
   Color Highlight
   Lorem ipsum (ctrl + p)
   vscodie-icons
   live-server (Go Live 버튼 클릭/  Ctrl(Cmd)+L & Ctrl(Cmd)+O )
   Power mode

   Tabnine Autocomplete AI(변수 추천)
   npm Intellisense(dependencies 중 매칭되는 라이브러리 추천)
   React-Native/React/Redux snippets for es6/es7


2. 프로젝트 구조를 알아보자
   html들  + css/images/js

3. html5의 구조를 알아보자
   html
   head
   body

4. head의 구조를 알아보자

   [meta 태그란?]

 

메타태그는 html문서의 정보를 담고 있는 element다.

meta태그 속성에는 http-equiv, name, content 3가지 속성이 있다.

 

- http-equiv="항목명"

웹 브라우저가 서버에 명령을 내리는 속성.

 

- content="정보값"

meta 정보의 내용을 지정

 

- name="정보 이름"

몇 개의 meta 정보의 이름을 정할 수 있으며, 지정하지 않으면 http-equiv와 같은 기능을 가짐

 

[기본적인 meta태그의 설정]

 

<!DOCTYPE html>
<html lang="ko">
<head>
    <!-- 문서모드를 utf-8 로 인코딩 -->
    <meta charset="utf-8">
    
    <!-- 브라우저 문서의 호환성 지정, 최신 엔진으로 렌더링 할 수 있도록 설정 -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    
    <!-- 모바일 접속시 디바이스 크기에 맞춘 화면 렌더링 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    
    <!-- 홈페이지 주제 지정 -->
	<meta name="subject" content="휘두루미 블로그">
    
    <!-- SEO(검색엔진 최적화) 설정 -->
    <meta name="description" content="휘두루미 티스토리 블로그 입니다.">
    <meta name="keywords" content="www,web,world wide web,html,css,javascript">

    <!-- 검색로봇 제어 -->
    <meta name="robots" content="All">
    
    <title>title</title>
</head>





5. body의 구조를 알아보자
6. 이제 태그다
   https://www.advancedwebranking.com/html/




