### Glyphicons

>font-awesome 처럼 쓸수 있음. [Glyphicon 모음](http://bootstrapk.com/components/)

```html
<button class="btn-lg btn-info glyphicon glyphicon-sound-dolby"> Dolby</button>
```

<br />

---

### 드롭다운

> 메뉴를 눌렀을 때 하단으로 펼쳐지는 것을 말함 자바스크립트와 jquery가 같이 있어야 작동함

```html
<div class = "dropdown">
    <a data-toggle="dropdown" href="#">여기를 클릭</a>
    <ul class="dropdown-menu" role="menu">
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#">1번 메뉴</a></li>
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#">2번 메뉴</a></li>
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#">3번 메뉴</a></li>
        <li role="presentation" class="divider"></li>
        <li role="presentation"><a role="menuitem" tabindex="-1" href="#"></a></li>
    </ul>
</div>
```

<br />

---

### 버튼 그룹

> 버튼 그룹으로 묶을 수있음

```html
<div class="btn-group">
    <button type="button" class="btn btn-danger">버튼1</button>
    <button type="button" class="btn btn-warning">버튼2</button>
    <button type="button" class="btn btn-info">버튼3</button>
    <button type="button" class="btn btn-success">버튼4</button>
</div>
```

<br />

---

### 버튼 드롭다운

> 버튼을 눌렀을 때 드롭다운 버튼 가능


```html
<div class="btn-group">
         <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown"> 버튼1   <span class="caret"></span>
         </button>
       <ul class="dropdown-menu" role="menu">
        <li><a href="#">메뉴 1</a></li>
        <li><a href="#">메뉴 2</a></li>
        <li><a href="#">메뉴 3</a></li>
        <li class="divider"></li>
        <li><a href="#">다른 메뉴 </a></li>
      </ul>
    </div>    
```

---

<br />

### 입력 그룹


```html

<div class="input-group">
    <span class="input-group-addon"><span class="glyphicon glyphicon-user"></span></span>
    <input type="text" class="form-control" placeholder="아이디">
</div>
<div class="input-group">
    <span class="input-group-addon"><span class="glyphicon glyphicon-lock"></span></span>
    <input type="text" class="form-control" placeholder="비밀번호">
</div>
```

---

<br />

### 네비게이션

> 네비게이션과 네비게이션 바 두가지의 내비게이션 기능이 있다 .nav 라는 선택자이용

알약형 : 좌우정렬 가능하고 수직으로 만들수 있음, 양쪽정렬도 가능

```html
 <div class="col-md-3">
     <ul class="nav nav-pills nav-stacked">
         <li class="active"><a href="#">메뉴1</a></li>
         <li><a href="#">메뉴2</a></li>
         <li><a href="#">메뉴3</a></li>
         <li><a href="#">메뉴4</a></li>
     </ul>
    </div>
```

<br />

탭형 

```html
<br>  
  <div class="clearfix"></div>
    <h4>탭형 네비게이션 양쪽 정렬 </h4>
     <ul class="nav nav-tabs nav-justified">
         <li class="active"><a href="#">메뉴1</a></li>
         <li><a href="#">메뉴2</a></li>
         <li><a href="#">메뉴3</a></li>
         <li><a href="#">메뉴4</a></li>
     </ul>
    <br>
```


## 네비게이션 바