# Markdown

1. 정의
   > 마크다운(Markdown)은 일반 텍스트 기반의 경량 마크업 언어다. 일반 텍스트로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업 언어에 비해 문법이 쉽고 간단한 것이 특징이다. HTML과 리치 텍스트(RTF) 등 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 README 파일이나 온라인 게시물 등에 많이 사용된다.  
   > (위키백과)
2. 장점
   1. 문법이 쉽고 간결하다
   1. 관리가 쉽다
   1. 지원 가능한 플랫폼과 프로그램이 다양하다
3. 단점
   1. 표준이 없다(사용자마다 문법이 다를 수 있음)
   1. 모든 HTML 마크업을 대신하지 못한다

# Markdown 문법(Syntax)

## 제목(Header)

- \# 다음 띄어쓰기 해줄 것!

⌨입력

```
# 제목 1(h1)

## 제목 2(h2)

### 제목 3(h3)

#### 제목 4(h4)

##### 제목 5(h5)

###### 제목 6(h6)
```

💻출력

# 제목 1(h1)

## 제목 2(h2)

### 제목 3(h3)

#### 제목 4(h4)

##### 제목 5(h5)

###### 제목 6(h6)

## 문장(Paragraph)

```
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

## 줄 바꿈(Line Breaks)

- 띄어쓰기 두번하거나 \<br/>

⌨입력

```
동해물과 백두산이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
```

💻출력  
동해물과 백두산이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

## 강조(Emphasis)

⌨입력

```
_이탤릭_
**두껍게**
**_이탤릭 + 두껍게_**
~~취소선~~
<u>밑줄</u>
```

💻출력  
_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

## 목록(List)

⌨입력

```
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    <!-- 들여쓰기(tab) 2번 -->
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
```

💻출력

1. 순서가 필요한 목록
1. 순서가 필요한 목록
   <!-- 들여쓰기(tab) 2번 -->
   - 순서가 필요하지 않은 목록
   - 순서가 필요하지 않은 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록

## 링크(Links)

⌨입력

```markdown
<!-- <a href="https://google.com">GOOGLE</a>   -->

[GOOGLE](https://google.com)

<!-- <a href="https://naver.com" title="NAVER로 이동">NAVER</a> -->

[NAVER](https://naver.com "NAVER로 이동")
```

💻출력  
[GOOGLE](https://google.com)

[NAVER](https://naver.com "NAVER로 이동")

## 이미지(Images)

⌨입력

```markdown
![대체텍스트](https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg)

<!-- 이미지를 클릭하면 해당 링크로 이동 -->

[![대체텍스트](https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg)](https://velog.io/@hwanky)
```

💻출력  
![대체텍스트](https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg)

<!-- 이미지를 클릭하면 해당 링크로 이동 -->

[![대체텍스트](https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg)](https://velog.io/@hwanky)

## 기호 표시(Backslash Escapes)

- 역슬래시(\)

⌨입력

```
\*
\-
\.
\()
\[]
\{}
```

💻출력  
\*  
\-  
\.  
\()  
\[]  
\{}

## 인용문(BlockQuote)

⌨입력

```
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문1
> > > 중중첩된 인용문2
> > > 중중첩된 인용문3
```

💻출력

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문1  
> > > 중중첩된 인용문2  
> > > 중중첩된 인용문3

## 인라인(inline) 코드 강조

- ` (백틱)

⌨입력

```
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
```

💻출력  
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

## 블록(block) 코드 강조

- \` (백틱) 3번 사용 ```

⌨입력

````
```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```
````

💻출력

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

⌨입력

````
```css
.list > li {
  color: red;
  top: 40px;
}
```
````

💻출력

```css
.list > li {
  color: red;
  top: 40px;
}
```

⌨입력

````
```bash
$ git commit -m 'Study Markdown'
```
````

💻출력

```bash
$ git commit -m 'Study Markdown'
```

⌨입력

````
```
텍스트
```
````

💻출력

```
텍스트
```

## 표(Table)

position 속성

- 기본적으로 왼쪽 정렬.
- 콜론을 양쪽에 붙이면 가운데 정렬, 오른쪽에만 붙이면 오른쪽 정렬

⌨입력

```
| 값       |          의미          | 기본값 |
| -------- | :--------------------: | -----: |
| static   |       기준 없음        |      O |
| relative |    요소 자신을 기준    |      X |
| absolute | 위치 상 부모 요소 기준 |      X |
| fixed    |      뷰 포트 기준      |      X |
```

💻출력  
| 값 | 의미 | 기본값 |
| -------- | :--------------------: | -----: |
| static | 기준 없음 | O |
| relative | 요소 자신을 기준 | X |
| absolute | 위치 상 부모 요소 기준 | X |
| fixed | 뷰 포트 기준 | X |

## 원시 HTML(Raw HTML)

- 마크다운 문법 안에서 실제 HTML 문법을 사용하는 것

⌨입력

```
동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
<u>하느님</u>이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" targer="_blank">NAVER</a>

<img src="https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg" alt="대체텍스트">
```

💻출력  
동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
<u>하느님</u>이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" targer="_blank">NAVER</a>

<img src="https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg" alt="대체텍스트">

## 수평선(Horizontal Rule)

⌨입력

```
---
***
___
```

💻출력

---

---

---

## 이모지(Emoji)

1. [링크에서 복사+붙여넣기](https://kr.piliapp.com/twitter-symbols/)

1. 단축키 이용
   - windows: `윈도우 키` + `마침표(.)`
   - mac: Command + Control + Space Bar
