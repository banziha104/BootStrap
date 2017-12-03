# 테이블 

> 부트스트랩은 테이블에 대한 css를 제공함

* table : 넓이가 100%인 테이블이 생성되고 border가 적용됨
* table table-striped : 각 행에 색깔을 넣어줌
* table table-bordered : 테두리를 만듬
* table table-hover : 마우스를 위에 올려두면 강조효과
* table table-condensed : 각셀이 타이트하게 보임

<br />

---

# 폼

* > 상위 태그에 .form-group을 달아줌, input 태그에는 form-control을 달아줌

```html
<form role="form">
<div class="form-group">
    <lable for="Name">이름</lable>
    <input type="text" class="form-control" placeholder="이름">    
</div>
</form> 
```

* > inline 스타일

```html

<form role="form" class="form-inline">
<div class="form-group">
    <lable for="Name">이름</lable>
    <input type="text" class="form-control" placeholder="이름">    
</div>
</form>
```

* > 그리드시스템을 이용한 수평폼

```html
 <form class="form-horizontal" role="form">  
    <div class="form-group">   
        <label for="Name" class="col-xs-2 col-lg-2 control-label">이름</label>
        <div class="col-xs-10 col-lg-10">
            <input type="text" class="form-control" placeholder="이름"> 
        </div>
    </div>   
```

* > textarea의 경우 row