# 제목(Header)

<!-- # -> h #개수의 따라 중요도가 달라짐 적을수록 중요 -->

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

<!-- 뛰어스기 2번 -->

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산 <br/>
대한 사람 대한으로 길이 보존하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

<!-- 숫자 1만 넣으면 알아서 순서되로 만들어줌 -->
<!-- 들여쓰기 두번 하면 자식 목록생성 -->
<!-- - 점으로 이루어진 목록 만듬 -->

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
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

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<!-- a태그 target 속성에 관한 마크다운은 없음 -->

<a href="https://www.google.co.kr" target="_blank">GOOGLE</a>


# 이미지(Images)

 <!-- 링크와 이미지 차이 앞에 !있는지 없는지 -->

![HEROPY](https://heropy.blog/css/images/logo.png)

 <!-- 이미지에 링크 넣기 -->

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> (네이버 국어 사전)


>인용문을 작성하세요!
>> 중첩된 인용문
>>> 중첩된 인용문 1  
>>> 중첩된 인용문 2  
>>> 중첩된 인용문 3  

# 인라인(inline) 코드 강조
<!-- 강조하고 싶은 단어 백틱으로 감싸주기 -->

CSS에서 `background` 혹은  
`background-image` 속성으로 요소에  
배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position : absolute;
  top : 40px;
}
```

```javascript
function func() {
  var a = "aaa";
  return a;
}
```

```bash
$ git commit -m 'study markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X


<!-- |(버틸컬 바)를 통해서 표를 만들수 있다 -->
<!-- :(콜론 기호)를 추가하여 좌우 가운데 정렬을 할수있다) -->

# 원시 HTML(Raw HTML)
동해물과 <u>백두산</u>이 마르고 닳도록</br>
하느님이 보우하사 우리나라 만세

<a href="https://www.google.co.kr" target="_blank">GOOGLE</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="heropy">

# 수평선(Horizontal Rule) 

---

***

___