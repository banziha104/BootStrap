# Grid-System

<br />

> 부트스트랩 그리드 시스템을 이용하여 레이아웃으로 잡으며 12열로 구성되어있음

<ol> 그리드 옵션

    * .col-xs- : 모바일폰 (768px<)
    * .col-sm- : 템플릿 (768px>=)
    * .col-md- : 데스크탑 (992px >=)
    * .col-lg- : 데스크탑 (1200px >=) 
    
<ol>

---

<br />

# 타이포 그래피

> Bootstrap 에서 폰트는 각 브라우저 별로 다르게 표시됨

1. 방법 1: bootstarp.css 에서 body 부분 변경

```javascript
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, /*이 부분에 삽입*/ sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #212529;
  text-align: left;
  background-color: #fff;
}
```

<br />

2. 방법 2: 최소화된 bootstrap.min.css 을 불러오고, font-family를 재지정

```html
<link href="css/bootstrap.min.css" rel="stylesheet">
<style>
    body{
        font-family: Helvetica Neue , Arial, <!--이 부분에 삽입 --> sans-serif;
    }
</style> 
```

<br />

3. 방법 3 : 부트스트랩 웹사이트의 맞춤화 페이지를 이용

[부트스트랩 커스터마이징 사이트](https://getbootstrap.com/docs/3.3/customize/)

<br />

4. 방법 4 : 구글 폰트 이용

[구글 한글 웹 폰트](http://deminoth.github.io/google-font-kor/)

```html

@import url(http://fonts.googleapis.com/earlyaccess/jejugothic.css);
```



