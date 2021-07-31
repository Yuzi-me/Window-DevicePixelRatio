# Window-DevicePixelRatio
查看本机系统缩放与布局和本机是否为视网膜屏，知道了这种情况后，可以用css media判断界面元素

<br/>
测试地址：http://img.yuzi.me/windows
<br/>
<br/>

### 例：

苹果电脑，是视网膜屏，就可以看出

```html
@media screen and (resolution: 2.5dppx) {
  body {
    zoom: .5;
  }
}

@media only screen and (resolution: 211.2dpi) {
  p {
    background-color: red;
  }
}
```
