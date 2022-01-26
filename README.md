# 제목(Header)

# 제목 1 (# 1개 : h1 태그)
## 제목 2 (# 2개 : h2 태그)
### 제목 3 (# 3개 : h3 태그)
#### 제목 4 (# 4개 : h4 태그)
##### 제목 5 (# 5개 : h5 태그)
###### 제목 6 (# 6개 : h6 태그)

# 문장(Paragraph)
동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세  
줄바꿈 처리하려면 띄어쓰기 두번한다. <br/>
또는 <br/> 태그를 사용한다.

# 강조(Emphasis)
_이텔릭_  
**두껍게**
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록    
    1. 순서가 필요한 목록(들여쓰기 두번)
    1. 순서가 필요한 목록(들여쓰기 두번)
1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요없는 목록
- 순서가 필요없는 목록
    - 순서가 필요없는 목록(들여쓰기 두번)
    - 순서가 필요없는 목록(들여쓰기 두번)
        - 순서가 필요없는 목록(들여쓰기 네번)
- 순서가 필요없는 목록
- 순서가 필요없는 목록

# 링크(Links)
<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)

<a href="https://naver.com" title="naver로 이동">NAVER</a>  
[NAVER](https://naver.com "naver로 이동")

# 이미지(Image)
![HEROPY](https://heropy.blog/css/images/logo.png)
# 이미지 선택시 소괄호 URL로 이동됨
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문 작성
>> 중접된 인용문
>>> 중접된 인용문 1  
>>> 중접된 인용문 2  
>>> 중접된 인용문 3  

# 인라인(inline) 코드 강조
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있다.

# 블럭(block) 코드 강조 (코드블럭)
```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```javascript
function func(){
    console.log('a');
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세
```
# 표(Table) 
( '--|' 는 표의 머리와 몸통을 구분하는 용도이다.  
, ':' 으로 정렬을 설정할 수 있다. )  
position 속성 
값 | 의미 | 기본값
:--|:--:|--:|
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)
: 마크다운에서 실제 HTML 문법을 사용하는 것을 말한다.  

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
<span style="text-decoration:underline">하느님</span>이 보우하사 우리나라 만세

# 수평선(Horizontal Rule)
---
***
___
