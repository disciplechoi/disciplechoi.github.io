---
layout: post
title:  "Page Layout 정리"
date:   2021-05-26 09:55:09 +0900
categories: frontend
---

*이 포스팅은 김버그님의 HTML&CSS는 재밌다*를 수강하며 정리한 내용입니다.

## 1. Grid System(Bootstrap 기준으로 설명)
![그리드시스템 전체 설명](https://cdn.rawgit.com/MakeSchool-Tutorials/sa-2018-landing-page/master/P08-Grid-System/assets/three_rows.png)

코드는 다음과 같이 작성, 반드시 **container>row>col>자신이 원하는 div**의 순서로 작성할 것.

```
<div class="container">
    <div class="row">
        <div class="col-1">
        <p>col-1</p>
        </div>
    </div>
</div>
```

시작은 모바일부터 하는 것이 좋다.
```
<div class="container">
    <div class="row">
        <div class="col-12 col-md-6 col-lg-4 col-xl-3">
        <p>col-1</p>
        </div>
    </div>
</div>
```