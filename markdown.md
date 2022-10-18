# :heavy_exclamation_mark: [markdown](https://www.markdownguide.org/)
## 1. 마크다운이란?
- Markdown은 일반 텍스트 문서에 서식 요소를 추가하는 데 사용할 수 있는 가벼운 마크업 언어 <br>
- 2004년 John Gruber 가 만든 Markdown은 현재 세계에서 가장 인기 있는 마크업 언어 중 하나

## 2. 마크다운을 사용하는 이유
- 웹사이드, 문서, 메모, 책, 프리젠테이선 등 기술 문서를 만드는 모든 곳에 사용 가능
- markdown 형시그이 텍스트가 포함된 거의 모든 응용프로그램에서 사용 가능 (이식성이 좋음)
- 플랫폼이 독립적 (모든 운영체제에서 사용 가능)

## 3. 마크다운의 프로세스
 a. 텍스트 편집기 또는 전용 markdown 응용 프로그램을 사용하연 markdown 파일 생성<br>
 b. 응용 프로그램에서 markdown 파일 오픈<br>
 c. 응용 프로그램을 사용하여 markdown파일은 HTML문서로 변환<br>
 d. 웹 브라우저에서 HRML파일을 보거나 markdown 응용 프로그램을 사용해 PDF 같은 다른 파일 형식으로 변환<br>

![image](https://user-images.githubusercontent.com/106071623/196365550-1a21bc96-d9b7-4806-9a7b-c22b67ff7318.png)

## 4. 마크다운의 장단점
### 4.1 장점
1. 메모를 작성하고 웹 사이트용 콘테츠를 만들고 인쇄 가능한 문서를 생성하는 빠르고 쉬운 방법
2. 구문을 배우는데 오래 걸리지 않음
3. 일상생활과 업무 등 다양한게 사용하기 좋은 형식

### 4.2 단점
1. 표준이 없어 도구에 따라 변환 방식이나 생성물이 다름
2. 모든 HTML 마크업을 대신하지 못함

# :bangbang: markdown guide
## 1. Header
- 글머리: 1~6까지만 지원
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6 
  
## 2. BlockQuote
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

## 3. list
### 3.1 순서있는 목록
- 어떤 번호를 입력해도 내림차순으로 표현됨
```
1. first
2. second
3. third
```
1. first
2. second
3. third
### 3.2 순서없는 목록
```
* star
  * star
    * star

+ plus
  + plus
    + plus

- minus
  - minus
    - minus
```
* star
  * star
    * star

+ plus
  + plus
    + plus

- minus
  - minus
    - minus

## 4. 코드 표현 방식
### 4.1 HTML 방식
```<pre><code>{code}</code></pre>```
### 4.2 코드 블럭 방식 (```)
<code>
```
코드 작성
```
</code>

## 5. line
```
* * *

***

*****

- - -

---------------------------------------
```
* * *

***

*****

- - -

---------------------------------------

## 6. link
### 6.1 참조링크
```
[title][link]
[link]: url
```
### 6.2 외부링크
```
[title](url)
```
### 6.3 추가
```
- 외부링크: <url>
- 이메일 링크: <aaa@dongyang.ac.kr>
```

## 7. 강조
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```
*single asterisks* <br>
_single underscores_ <br>
**double asterisks** <br>
__double underscores__ <br>
~~cancelline~~ <br>

## 8. 깃허브 이모지
- 구글에 깃허브 이모티콘 혹은 깃허브 이모지라고 검색하면 다양한 링크를 찾을 수 있다.   
<https://www.webfx.com/tools/emoji-cheat-sheet/>
<https://gist.github.com/rxaviers/7360908>

## 9. 참고문헌
- The Markdown Guide Read free sample: <https://www.markdownguide.org/assets/markdown-guide-sample.pdf>

