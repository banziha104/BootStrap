# 모달

> 팝업 윈도우를 사용했던 부분을 대체함

```html
<div class="modal fade"         
        id="myModal"                
        tabindex="-1" 
        role="dialog" 
        aria-labelledby="myModalLabel" 
        aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal"><span aria-hidden="true">&times;</span><span class="sr-only">Close</span></button>
        <h4 class="modal-title" id="myModalLabel">모달 제목 </h4>
      </div>
      <div class="modal-body">
      <p>여기는 내용이 들어 가는 곳 </p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">닫기</button>
        <button type="button" class="btn btn-primary">변경 사항 저장</button>
      </div>
    </div> <!-- 모달 콘텐츠 -->
  </div> <!-- 모달 다이얼로그 -->
</div> <!-- 모달 전체 윈도우 -->
```
---

<br />

# 스크롤파이

> 웹 페이지의 위치를 기반으로 네비게이션 바의 메뉴가 변하는 것.

1. 데이터 속성을 이용한 방법

```html
<body data-spy="scroll" data-target="#navbar-example" data-offset="50">
 <div class="container">  
    <nav id="navbar-example" class="navbar navbar-default navbar-fixed-top" role="navigation">
      <div class="container">  
        <div class="navbar-header">
          <button class="navbar-toggle" type="button" data-toggle="collapse" data-target=".bs-example-js-navbar-scrollspy">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">Project Name</a>
        </div>
        <div class="collapse navbar-collapse bs-example-js-navbar-scrollspy">
          <ul class="nav navbar-nav">
            <li><a href="#menu1">메뉴 1</a></li>
            <li><a href="#menu2">메뉴 2</a></li>
            <li><a href="#menu3">메뉴 3</a></li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="scrollcontent" >  
```

2. 자바스크립트를 이용한 사용방법

```javascript
$('body').scrollspy({ target : '#navbar-example'})
```

---

<br />

# 토글되는 탭

```html
<div class="container">  
    <h2>토글되는 탭 </h2>
    <ul class="nav nav-tabs">
      <li class="active"><a href="#home" data-toggle="tab">홈</a></li>
      <li><a href="#tab1" data-toggle="tab">탭 1</a></li>
      <li><a href="#tab2" data-toggle="tab">탭 2</a></li>
      <li><a href="#tab3" data-toggle="tab">탭 3</a></li>
    </ul>
    <!--콘텐츠 부분 -->
    <div class="tab-content">
        <div class="tab-pane fade in active" id="home">
```

---

<br />

# 툴팁

```html
   <h2>기본 링크를 이용한 툴팁</h2>
    <div class="tooltip-test">
      기본  <a href="#" data-toggle="tooltip" title="기본 툴팁">툴팁</a>은 상단에 표시됩니다.  
      방향을 지정할 수 있으며  <a href="#" data-toggle="tooltip" data-placement="left" title="왼쪽 표시">왼쪽</a>으로 툴팁이 표시됩니다. 
      하단으로   <a href="#" data-toggle="tooltip" data-placement="bottom" title="하단에 표시">
         툴팁을 </a> 표시할 수 있습니다. 
      지금 보시는 <a href="#" data-toggle="tooltip" data-placement="right" title="오른쪽에 표시">툴팁은 </a> 오른쪽에 표시됩니다. 

  <hr>
```

---

<br />

# 팝오버

```html
  <div class="inner" >

     <button type="button" class="btn btn-default" title="팝오버 제목" data-container="body" data-toggle="popover" data-placement="left" data-content="여기는 팝오버 부분에 대한 내용이 들어갑니다.">
        팝오버 왼쪽
     </button>

     <button type="button" class="btn btn-primary" title="팝오버 제목" data-container="body" data-toggle="popover" data-placement="top" data-content="여기는 팝오버 부분에 대한 내용이 들어갑니다.">
        팝오버 상단 
     </button>

     <button type="button" class="btn btn-success" title="팝오버 제목" data-container="body" data-toggle="popover" data-placement="bottom" data-content="여기는 팝오버 부분에 대한 내용이 들어갑니다.">
        팝오버 하단 
     </button>

     <button type="button" class="btn btn-warning" title="팝오버 제목" data-container="body" data-toggle="popover" data-placement="right" data-content="여기는 팝오버 부분에 대한 내용이 들어갑니다.">
       팝오버 오른쪽 
     </button>
  </div> 

```

---

<br />

# 경보

```html
<div class="alert alert-danger">
     <a href="#" class="close" data-dismiss="alert">
        &times;
     </a>
     <strong>경고!</strong> 사용하시는 네트워크에 문제가 있어 웹 사이트가 제대로 구동되지 않았습니다. </div>
  </div>
```

<br />

# 컬랩스 (아코디언 효과)

```html
<h2>컬랩스 아코디언 효과 </h2>
    <div class="panel-group" id="accordion">
        <div class="panel panel-default">
          <div class="panel-heading">
            <h4 class="panel-title">
              <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne">
                여기를 클릭해 보세요. #1 
              </a>
            </h4>
          </div>
          <div id="collapseOne" class="panel-collapse collapse in">
```

---

<br />

# 캐러셀

```html
 <h2>캐러셀 슬라이드 효과  </h2>
        <div id="carousel-example-generic" class="carousel slide">
            <!-- Indicators -->
            <ol class="carousel-indicators">
              <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
              <li data-target="#carousel-example-generic" data-slide-to="1"></li>
              <li data-target="#carousel-example-generic" data-slide-to="2"></li>
            </ol>
                 <!-- Carousel items -->
             <div class="carousel-inner">
                <div class="item active">
                   <img src="./slide1.jpg" alt="First slide">
                </div>
                <div class="item">
                   <img src="./slide2.jpg" alt="Second slide">               
                </div>
                <div class="item">
                   <img src="./slide3.jpg" alt="Third slide">                 
                </div>
             </div>
            <!-- Controls -->
              <a class="left carousel-control" href="#carousel-example-generic" data-slide="prev">
                <span class="icon-prev"></span>
              </a>
              <a class="right carousel-control" href="#carousel-example-generic" data-slide="next">
                <span class="icon-next"></span>
              </a>
          </div>
```


