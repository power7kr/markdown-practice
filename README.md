# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
<br/>
# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
<br/>

# 줄바꿈(Line Breaks)
### 띄어쓰기 2번하기 (띄어쓰기 2개를 못읽는 곳도 있음)
### \<br>, \<br/> 도 됨
동해물과 백두산이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산  
대한 사람 대한으로 길이 보전하세
<br/>

# 강조
_이텔릭_ <br/>
**두껍게** <br/>
**_이텔릭 + 두껍게_** <br/>
~~취소선~~ <br/>
<u>밑줄</u>

# 목록

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. **들여쓰기 2번으로 내부 목록**
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - **들여쓰기 2번으로 내부 목록**
- 순서가 필요하지 않은 목록

# 링크(Links)
<a href = "https://google.com">그냥 HTML처럼 쓰기</a><br/>
[마크다운식](https://google.com)<br/>
<a href = "https://google.com" title="마우스를 하이퍼링크에 올리면 설명이 뜸!">설명을 HTML처럼 쓰기</a><br/>
[마크다운식](https://google.com "마우스를 하이퍼링크에 올리면 설명이 뜸!")<br/>
<a href = "https://google.com" title="마우스를 하이퍼링크에 올리면 설명이 뜸!" target="_tab">대신 이건 안됨...(새 창에 띄우기) HTML로만 됨</a><br/>

# 이미지(Images)

![SEAGULL](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDkvFCLSMbUU6Bqb1m-0y3LPAQ7_Gcs-PNZw&usqp=CAU)

#### 응용: 링크 이미지
[![LINK IMAGE](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQaBYQcLnpgF9_09-hrtIDFo4HWmSviYytv-w&usqp=CAU)](https://google.com)

# 인용문(BlockQuote)

> 앞에 꺽쇠를 달아서 인용문을 만들기
>> 중첩된 인용문을 만들기
>>> 중중첩된 인용문을 만들기

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.<br/>
> (네이버 국어 사전)

# 인라인(inline) 코드 강조

`백틱 기호`로 강조를 할 수 있습니다
CSS에서 `background` 혹은 background-image 속성으로 요소에 배경이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

\```html<br>
`원하는 코드`<br>
\```<br>
라는 기호로 블록코드를 사용할 수 있습니다.


```html
이것은 HTML의 블록코드 안에 있습니다.
```

```java
public static void main(const string[] args)
{
  //this is main function
  System.out.println("이것은 자바의 블록코드 안에 있습니다.");
}
```

```cpp
this_is_test::this_is_method(){
  //this is this_is_test class's method
  std::cout<< "이것은 cpp의 블록코드 안에 있습니다." << std::endl;
}
```

# 표(Table)
## position 속성
값 | 의미 | 기본값
--:|:--|:--:
static | 요소의 기준이 없음 | O
relative | 요소 자신을 의미함 | X
absolute | 위차 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해불과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

<img width="1000px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRe5xJrGwCVXglXv9U0mxjA0ROxWeZlgQhyQ&usqp=CAU" alt="image"/><br/>

# 수평선(Horizontal Rule)

다음은 수평선을 쓸 수 있는 기호들이다<br/>
\- - -  
- - -
\***
***  
\___
___


