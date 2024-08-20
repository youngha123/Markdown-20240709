# Markdown

### 마크다운이란?
텍스트 기반의 마크업 언어로 읽고 쓰기 편하게 구성되어있음.  
특수기호와 문자를 활용하여 간단한 구조를 작성할 수 있음.    
HTML과 호환됨.

#### 장단점
장점
1. 간단함
2. 특별한 도구가 필요하지 않음
3. 텍스트로 저장되기 떄문에 용량 활용이 높음

단점    
1. 표준이 없음
2. 모든 HTML 요소를 대신하지 못함

### 헤더 
- HTML Header 요소와 동일한 것으로 문서의 제목을 나타냄  
- h1 ~ h6 까지의 제목을 표현할 수 있음  
- '#' 이라는 기호로 헤더를 표시
# Header1 (HTML - h1)
## Header2 (HTML - h2)
### Header3 (HTML - h3)
###### Header6 (HTML - h6)

### 블록 인용
- 인용구를 표현할 때 사용
- '>' 이라는 기호를 사용하여 표현

> 첫번째 인용구  
> > 두번째 인용구

### 리스트 
- 나열된 항목을 나타낼때 사용
- 순서가 존재하는 리스트 (HTML ol 요소), 순서가 존재하지 않는 리스트(HTML ul)
- '1.' 기호로 순서가 존재하는 리스트를 표현
- '*', '+', '-' 기호로 순서가 존재하지 않는 리스트를 표현 

1. apple
2. banana
3. cacao

- apple
- banana
- cacao

+ apple
+ banana
+ cacao

### 코드 
- 코드를 작성하기 위한 영역을 지정
- HTML code 요소와 동일
- '```' 기호로 표현

```
public static void main(String args[] args) {
    system.out.println();
} 
```

- 시작하는 '```' 뒤에 표현하고자하는 언어를 지정하면 문법 강조를 할 수 있음

``` java
public static void main(String args[] args) {
    system.out.println();
} 
```

### 구분선 
- HTML hr 요소와 동일한 것
- 영역을 구분하고자 할 때 사용
- '* * *', '***', '*****', '- - -', '-------------------' 기호로 표현 가능
***
- - -

### 링크
- HTML a 요소와 동일한 것
- '[키워드][링크의 구분자]'
- '[링크의 구분자]: url'

[MARKDOWN GUIDE][MARKDOWN GUIDEid]   
[마크다운 가이드][MARKDOWN GUIDEid]

[MARKDOWN GUIDEid]: https://www.markdownguide.org/ "MARKDOWN GUIDE"

### 텍스트 강조
- 기울임꼴, 굵은글씨, 취소선을 표현
- '*', '_' 기호로 기울임꼴 표현
- '**', '__' 기호로 굵은글씨 표현
- '~~' 기호로 취소선 표현

내가 그린 *기린 그림*은 ~~잘 그린~~ **기린 그림**  

### 이미지
- HTML img 요소와 동일한 것
- ![이미지 설명](이미지 경로)

![강아지](https://image.ytn.co.kr/general/jpg/2017/1018/201710181100063682_d.jpg)

### HTML 사용

- 마크다운 대신 HTML 사용 가능

<h2 style="color: red">HTML 텍스트</h2>
