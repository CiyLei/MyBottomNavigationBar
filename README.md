# my_bottom_navigation_bar

不知道为什么谷歌爸爸的`BottomNavigationBar`都不能自定义取消缩放，没办法，拷出源码改（修改的地方有中文注释）。

![Image text](https://raw.githubusercontent.com/CiyLei/MyBottomNavigationBar/master/image/a.gif)

如果添加的`BottomNavigationBarItem`超过3个，请写死`type`

```dart
bottomNavigationBar: MyBottomNavigationBar(
  type: MyBottomNavigationBarType.fixed,
)
```
