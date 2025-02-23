---
title:  "HTML_Header"
categories:
  - html
---

# HTML을 시작하며

Visual Studio Code(이하 VSC)라는 편집기를 이용하여  HTML을 학습할 예정이다.

HTML이라는 언어는 타 언어 [ Ex) CSS, JS] 등 다른 언어와 함꼐 웹 사이트를 구성하며, HTML자체는 웹을 구성하는 뼈대라고 생각하면 된다.
HTML은 브라우저에서 보여주기 때문에 .html 확장자인 파일을 열어주면 된다. HTML의 특이한 점은 브라우저에서 출력을 하기 때문에 HTML문법을 따르지 않아도 사용자에게 콘텐츠를 보여준다는 것이다. 그렇기에 브라우저에서 HTML 파일에 에러가 있다고 하더라도 알려주지 않기 떄문에 유의해야 할 필요가 있다.


## 헤더 사용하기
HTML tag 사이에 넣는 인자는 title이나 image 등등 여러가지를 넣을 수 있다.
예시를 들어 한가지를 보자 h1이라는 tag는 웹의 헤더,  즉 주제목이 되는 것이다.

```html
<h1>Hello This is my website!!</h1>
```

HTML tag 작성 후 웹 사이트를 새로고침해보면 큰 폰트로 "Hello This is my website!!"가 출력되는 것을 알 수 있다.



![h1](https://user-images.githubusercontent.com/120043674/207639425-dd0196de-e7b0-42f1-8631-b9121c94f045.png)



h1이 아닌 자신이 임의로 작성한 tag를 만들어서 사용할 수 있다.

```html
<h1>Hello This is my website!!</h1>
<asdf>This is text</asdf>
```

asdf라고 아무 의미 없는 글자로 만든 임의의 tag를 작성한 후 확인했다.



![h2](https://user-images.githubusercontent.com/120043674/207639450-42d07078-b9e8-4756-a519-852193a4401e.png)



브라우저에서 정상적으로 출력되는 것을 알 수 있다.
