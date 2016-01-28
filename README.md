# XImageView
---------------

XImageView 可以显示超大尺寸的图片, 并支持缩放，双击放大， 拖动，单击，长按等手势操作,
并不会出现 OOM 的情况! 欢迎使用

![image](https://github.com/liungkejin/XImageView/blob/master/images/S60129-005846.jpg)

这是一张 20 M 的地球图
![image](https://github.com/liungkejin/XImageView/blob/master/images/S60129-010516.jpg)

## Issues
1. 不能很好的兼容 ViewPager

## Usage

```xml
<cn.kejin.android.views.XImageView
	android:id="@+id/xImageView"
	android:layout_height="match_parent"
	android:layout_width="match_parent" />

```

```java
try {
	mXImageView.setImage(getAssets().open("b.jpg"));
}
catch (IOException e) {
	e.printStackTrace();
}
```

