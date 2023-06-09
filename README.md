# 🌸Everything HTML🌸

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#HTML의-구조">HTML의 구조</a></li>
    <li><a href="#시맨틱-태그">시맨틱 태그</a></li>
    <li><a href="#텍스트-입력하기">텍스트 입력하기</a></li>
    <li><a href="#목록-만들기">목록 만들기</a></li>
    <li><a href="#표-만들기">표 만들기</a></li>
    <li><a href="#입력받기">입력받기</a></li>
    <li><a href="#Style">Style</a></li>
    <li><a href="#Image">Image</a></li>
    <li><a href="#AudioVideo">Audio,Video</a></li>
    <li><a href="#Hyperlink">Hyperlink</a></li>
    <li><a href="#tag">tag</a></li>
    <li><a href="#Form">Form</a></li>
    <li><a href="#pseudo selector">pseudo selector</a></li>
    <li><a href="#단축키">단축키</a></li>    
    <li><a href="#font">font</a></li>
  </ol>
</details>

## HTML의 구조

>1. `<!DOCTYPE html>` : 현재 문서가 HTML5 언어로 작성된 웹 문서<br>
>2. `<html> ~ </html>` : 웹 문서의 시작과 끝을 나타내는 태그<br>
>3. `<head> ~ </head>` : 웹 브라우저가 웹 문서를 해석하는 데 필요한 정보를 입력,웹 문서의 정보 ex.`<mata>,<title>`<br>
>4. `<body> ~ </body>` : 실제 웹 브라우저 화면에 나타나는 내용<br>

<br>

## 시맨틱 태그
> 1. `<header>` : 헤더 영역을 나타내는 태그
> 2. `<nav>` : 네비게이션 영역을 나타내는 태그, 웹 문서 위치에 영향을 받지 않음
> 3. `<main>` : 핵심 콘텐츠를 담는 태그
> 4. `<artcle>` : 독립적인 콘텐츠를 담는 태그 ex.블로그의 포스트,뉴스 사이트의 기사 등등
> 5. `<section>` : 콘텐츠 영역을 나타내는 태그
> 6. `<aside>` : 사이드 바 영역을 나타내는 태그
> 7. `<footer>` : 푸터 영역을 나타내는 태그
> 8. `<div>` : 여러 소스를 묶는 태그

<br>

## 텍스트 입력하기
> 1. `<h1~6>` : 제목을 나타내는 태그
> 2. `<p>` : 텍스트 단락을 만드는 태그
> 3. `<br>` : 줄을 바꾸는 태그
> 4. `<blockquote>` : 인용,들여쓰기
> 5. `<strong>` : 중요 텍스트 굵게 표시
> 6. `<b>` : 안 중요 텍스트 굵게 표시
> 7. `<em>, <i>` : 기울인 텍스트 입력
> 8. `<text-shadow>` : 텍스트 그림자 효과
>> * `<h-shadow> <v-shadow>` : 원본 텍스트와 그림자 텍스트 사이 수평/수직 거리(필수)
>> * `<blur-radius>` : 흐릿한 그림자를 만드는 효과(선택)
>> * `<color>` : 그림자 색
>> * `<none>` : 그림자 효과 없음


<br>

## 목록 만들기
> 1. `<ol>,<li>`: 순서 있는 목록을 만드는 태그
> 2. `<ol type= "n">` : 1(숫자), a(영문 소문자), A(영문 대문자), i(로마 숫자 소문자), l(로마 숫자 대문자)
> 3. `<ol start= "m">` : 원하는 숫자(영문)부터 시작 
> 4. `<ul>, <li>` : 순서 없는 목록을 만드는 태그
> 5. `<dl>,<dt>,<dd>` : 설명 목록(이름,값)을 만드는 태그 (들여쓰기)

<br>

## 표 만들기
> 1. `<table>, <caption>` : 표를 만드는 태그
> 2. `<tr>` : 행을 만드는 태그
> 3. `<td>, <th>` : 셀을 만드는 태그
> 4. `<thead>, <tbody>, <tfoot>` : 표의 구조를 지정하는 태그
> 5. `<colspan>` : 셀을 가로로 합치는 태그
> 6. `<rowspan>` : 셀을 세로(아래)로 합치는 태그

<br>

## 입력받기
> 1. `<form>` : 태그 안에 여러가지 구성요소를 넣어 다양한 형태의 입력을 받을 수 있는 태그
> 2. `<input>`  
>> * `<text>` : 일반 텍스트를 입력받을 수 있다
>> * `<password>` : 패스워드를 입력받을 수 있도록, 입력값이 화면에 보이지 않게 한다
>> * `<submit>` : `<form>`태그 내에 입력된 데이터를 서버로 전달해준다
>> * `<button>` : 버튼을 생성한다
>> * `<checkbox>` : 체크박스 형태의 입력을 받을 수 있다
>> * `<radio>` : 라디오 버튼 형태의 입력을 받을 수 있다
>> * `<reset>` : `<form>`태그 안의 사용자 입력을 초기화한다
>> * `<align>` : 이미지 입력에 대한 정렬 방법을 명시한다

<br>

## Style
> 1. `<background-color>` : 바탕색을 지정한다
> 2. `<color>` : 텍스트의 색상을 지정한다
> 3. `<font-famliy>` : 텍스트의 글꼴을 지정한다
> 4. `<font-size>` : 글꼴의 사이즈를 정할 수 있다
> 5. `<text-align>` : 텍스트를 정렬할 수 있다 
>> * center : 중앙정렬
>> * lift : 왼쪽 정렬
>> * right : 오른쪽 정렬
>> * justify : 양쪽 정렬
> 6. Selector
>> * `#` : id Selector, 각 태그를 유일하게 구분
>> * `.` : class Selector,여러 태그를 그룹으로 묶어 동일한 css스타일 적용 가능
>> * `tag name` : tag name Selector
>> * child selector: `div > strong { color : dodgerblue; } ` div 직계 자식인 strong에만 적용
>> * descendent selector: `ul strong { color : dodgerblue; }` ul의 자손 strong에 적용
>> * `*` : 전체 셀렉터, 와일드 문자를 사용하여 모든 태그에 적용
>> * `input[type=text] { color : red; } `: 속성 셀렉터, 값이 일치하는 태그에만 적용하는 셀렉터


<br>

## Image
> 1. `<img src = "이미지 파일 경로" alt ="대체용 텍스트">` 
> 2. `<width>` : 이미지의 너비 (%,px)
> 3. `<height>` : 이미지의 높이 (%,px)

<br>

## AudioVideo
> 1. `<object width="너비" height="높이" data="파일"></object>` : 오디오,비디오,자바애플릿,pdf 등등 가능
> 2. `<embed src="파일 경로" width="너비" height="높이">` : object와 다르게 닫는 태그가 없음. 오디오,비디오,이미지 등 가능
> 3. `<audio src="오디오파일 경로"></audio>` : 배경음악이나 효과음 등 오디오 파일 삽입
> 4. `<vidio src="비디오파일 경로"></vidio>` : 비디오 파일 삽입
> 5. `<audio>,<video>` 태그의 속성
>> * `<controls>` : 플레이어 화면에 컨트롤 바를 표시한다
>> * `<autoplay>` : 오디오나 비디오를 자동으로 실행한다
>> * `<loop>` : 오디오나 비디오를 자동으로 실행한다 
>> * `<muted>` : 오디오나 비디오 소리를 제거한다
>> * `<preload>` : auto 기본값, metadata, none
>> * `<width>,<height>` : 너비와 높이를 지정한다
>> * `<poster="파일 이름">` : video에서 사용하는 태그로 비디오가 재생되기 전까지 화면에 표시될 포스터의 이미지를 지정한다

<br>

## Hyperlink 
> 1. `<a herf="링크 주소"> 텍스트 or 이미지</a>` : `<a>`안에 img태그를 넣으면 이미지에도 링크를 만들 수 있다
> 2. `<target="blank">` : 새 탭에서 링크를 열어준다

<br> 

## tag
> 1. `target` 
>> * `_blank` : 새로운 윈도우나 탭(tab)
>> * `_self` : 링크가 위치한 현재 프레임
>> * `parent` : 현재 프레임의 부모 프레임
>> * `_top` : 현재 윈도우 전체
>> * `프레임 이름` : a태그 에 name으로 명시된 프레임

<br>

## Form
> `<form[속성="속성값"]>여러 폼 요소</form>` : 입력받은 자료를 어떤 방식으로 서버에 넘길지, 어떤 프로그램을 사용할지 지정한다
> 1. name : 자바스크립트로 폼을 제어할 때 사용할 폼의 이름을 지정한다
> 2. action : `<form>`태그 안에 내용을 처리해 줄 서버 프로그램을 지정한다
> 3. target : action 속성에서 지정한 스크립트 파일을 현재 창이 아닌 다른 위치에서 열도록 한다
> 4. method <br>
>>    * get : 256~4096byte(입력제한), 주소표시줄에 사용자가 입력한 내용이 드러나는 단점<br>
>>    * post : 입력 길이 제한 없음, 사용자가 입력한 내용이 드러나지 않는다

<br>

## pseudo selector
> 1. `linked` : 방문 전 링크 상태
> 2. `visited` : 방문 후 링크 상태
> 3. `:hover` : 마우스가 해당 요소 위에 있을 때 요소의 스타일을 변경할 수 있다
> 4. `:active` : 마우스가 해당 요소를 클릭하는 순간부터 떼는 순간까지 요소의 스타일을 변경할 수 있다
> 5. `focus` : 마우스가 해당 요소를 클릭하면 요소의 스타일을 변경할 수 있다
> 6. `nth-child(even)` : 짝수 번째 모든 자식 태그에 스타일 적용
> 7. `nth-child(odd)` : 홀수 번째 모든 자식 태그에 스타일 적용
> 8. `first-letter` : 블록형 태그 첫글자에 스타일 적용, 인라인 태그 안됨
> 9. `first-line` : 블록형 태그 첫 라인에 스타일 적용

<br>
  
## Font 
> 1. `font-family`
> 2. `font-size`
> 3. `font-style`
> 4. `font-weight`

<br>
  
## 단축키 
> 1. `<!-- -->` : 주석 ctrl +/ 

[first](#)

