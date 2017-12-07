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


### 네비게이션 바


### 경로와 페이지 네이션

> 페이지 네이션
```html

<ul class="pagination">
    <li><a href="#">1</a></li>
    <li><a href="#">2</a></li>
    <li><a href="#">3</a></li>
    <li><a href="#">4</a></li>
    <li><a href="#">5</a></li>
    <li><a href="#">6</a></li>
    <li><a href="#">7</a></li>
    <li><a href="#">8</a></li>
    <li><a href="#">9</a></li>
</ul>
```

> 경로

```html
  <ol class="breadcrumb">
    <li><a href="#">Home</a></li>
    <li><a href="#">menu1 </a></li>
    <li class="active">submenu</li>
  </ol>
```

<br />

---

### 라벨과 배지

> 라벨은 커뮤니티 게시판이나 블로그에 새로운 글이 올라온 경우 새로운 글이 있다는 것을 표시해주는 역할과 비슷 

```html
<div class="container">  
<h1> 라벨과 배지 </h1>

<h4>라벨 사용 </h4>
 <table class="table">
  <thead>
   <tr>
     <th>번 호 </th>
     <th>제 목</th>
     <th>글쓴이</th>
   </tr>
   </thead>
   <tr>
     <td>1</td>
     <td>테이블 테스트  테이블 테스트 테이블 테스트  <span class="label label-default"> New </span></td>
     <td>홍길동</td>
   </tr>
   <tr>
     <td>2</td>
     <td>테이블 테스트  테이블 테스트 테이블 테스트 <span class="label label-danger"> 중요 </span></td>
     <td>임꺽정 </td>
   </tr>
   <tr>
     <td>3</td>
     <td>테이블 테스트  테이블 테스트 테이블 테스트 <span class="label label-info"> 정보 </span></td>
     <td>성춘향 </td>
   </tr>   
 </table>
  <hr>

<span class="label label-default">Default</span>
<span class="label label-primary">Primary</span>
<span class="label label-success">Success</span>
<span class="label label-info">Info</span>
<span class="label label-warning">Warning</span>
<span class="label label-danger">Danger</span>


<hr>
<h4> 배지 </h4>

    <div class="col-xs-3">
     <ul class="nav nav-pills nav-stacked">
         <li class="active"><a href="#">  <span class="badge pull-right">42</span>메뉴1</a></li>
         <li><a href="#">메뉴2</a></li>
         <li><a href="#">메뉴3</a></li>
         <li><a href="#"><span class="badge pull-right">10</span> 메뉴4</a></li>
     </ul>
    </div>
```

### 점보트론

> 점보트론은 사이트에서 일반적으로 프론트 페이지 또는 아주 중요한 페이지에서 해당 콘텐츠를 강조할 떄 사용

```html
<div class="container">
    <div class="jumbotron">
        <div class="container">
            <h1>Hello, World! <small>점보트로오오오온</small></h1>
            <p> 일반글꼬오오올</p>
            <p><a class="btn btn-success btn-lg">Learn More</a></p>
        </div>
    </div>
</div>
```

<br />

### 썸네일

```html
<div class="row">
    <div class="col-sm-6 col-md-3">
      <div class="thumbnail">
        <img src="DSC_6305.jpg" alt="...">
          <div class="caption">
            <h3>제목과 </h3>
            <p>내용도 넣을 수 있다.</p>
            <p><a href="#" class="btn btn-primary" role="button">Button</a> <a href="#" class="btn btn-default" role="button">Button</a></p>
        </div>
      </div>
    </div> 
```

<br />

### 경보와 진행바

```html
<div class="progress">
    <div class="progress-bar progress-bar-danger" role="progressbar" aria-valuenow="40">
        40%
    </div>
</div>
<div class="container">
    <div class="alert alert-success"></div>
    <div class="alert alert-info"></div>
    <div class="alert alert-warning"></div>
    <div class="alert alert-danger"></div>
</div>
```

### 미디어 객체 목록 그룹 패널 , Wells

> 미디어 객체는 게시판 또는 블로그에서 댓글을 처리하는 부분을 말함

```html

```

> 패널