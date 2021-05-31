---
layout: post
title:  "반응형 웹을 위한 CSS Media Query"
date:   2021-05-28 14:53:09 +0900
categories: frontend
---

### Media Query
반응형 웹을 위해 반드시 알아야하는 CSS로 Media Query를 이용하기 위해서는 
* Html - viewport meta
* Css - media query 
가 선언되어야 한다.

자세히 설명하자면,
html 파일
```
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width" />
    </head>
</html>
```

css파일
```
@media screen and (min-width: 768px){
    /*화면에 최소 768px 이상일 경우 아래의 코드를 실행*/
}
```

또한, 반응형 웹 개발 시 모바일 버전부터 마크업, 스타일링을 하는 것이 좋다.



