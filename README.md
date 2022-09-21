# 제목(Header)

<!-- # 다음 띄어쓰기 해줄 것! -->

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄 바꿈(Line Breaks)

<!-- 띄어쓰기 두번하거나 <br/> -->

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

<!-- <ol></ol>과 같음, 숫자 1. 만 넣어줘도 됨 -->

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   <!-- 들여쓰기(tab) 2번 -->
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<!-- <a href="https://google.com">GOOGLE</a>   -->

[GOOGLE](https://google.com)

<!-- <a href="https://naver.com" title="NAVER로 이동">NAVER</a>   -->

[NAVER](https://naver.com "NAVER로 이동")

# 이미지(Images)

![대체텍스트](https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg)

<!-- 이미지를 클릭하면 해당 링크로 이동 -->

[![대체텍스트](https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg)](https://velog.io/@hwanky)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문1  
> > > 중중첩된 인용문2  
> > > 중중첩된 인용문3

# 인라인(inline) 코드 강조

<!-- `(백틱) -->

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
텍스트
```

# 표(Table)

position 속성

<!-- 기본적으로 왼쪽 정렬. 콜론을 양쪽에 붙이면 가운데 정렬, 오른쪽에만 붙이면 오른쪽 정렬 -->

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relative |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰 포트      |      X |

# 원시 HTML(Raw HTML)

<!-- 마크다운 문법 안에서 실제 HTML 문법을 사용하는 것 -->

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
<u>하느님</u>이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" targer="_blank">NAVER</a>

<img src="https://velog.velcdn.com/images/hwanky/profile/691ad7ca-f751-4f31-ba45-9ffa267a3286/image.jpg" alt="대체텍스트">

# 수평선(Horizontal Rule)

---

---

---
