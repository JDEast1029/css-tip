# css-tip
```text
对图片做一个等比缩放然后裁切中间部分
.container {
  width: 80px;
  height: 80px;
  background: url("http://p.qpic.cn/qqconadmin/0/292590fd5c4a4553864f8f56f8d29a92/0");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}
```

```text
input disable属性下面 更改文本框或者按钮的颜色（对IOS兼容处理）

input:disabled, input[disabled]{ 
  color: red; 
  -webkit-text-fill-color:red; 
  -webkit-opacity:1; 
  opacity: 1; 
}
```
