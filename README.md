# css 垂直居中

## [预览](https://ggzzddd.github.io/css/index3)

```
.wraper{
  position:relative;
  border:1px solid red;
  height: auto;
  min-height:100vh;
  .box{
    width:130px;
    height:130px;
    border:1px solid red;  
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%)
  }
}
```
## [预览](https://ggzzddd.github.io/css/index2)

```
.wraper{
  display: flex; 
  justify-content: center;
  align-items: center;
  min-height:100vh;
  width:100%;
  border:1px solid red;
  .box{
    width:230px;
    height:230px;
    border:1px solid red;
  }
}

```

## [预览](https://ggzzddd.github.io/css/index1)
```
.wraper{
  position:relative;
  .box{
    position:absolute;
    top:50%;
    left:50%;
    width:100px;
    height:100px;
    margin:-50px 0 0 -50px;
  }
}
```