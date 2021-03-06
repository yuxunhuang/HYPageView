# HYPageView

### 创建方式
```
// titles：标题数组  
// childVCs：每个标题对应要显示的控制器  
// parentVC：标题控制器对应的父控制器
// titleStyle： 控制器标题的样式
let pageView = HYPageView.init(frame: view.bounds, titles: titles, childVCs: childVCs, parentVC: self, titleStyle: titleStyle)
view.addSubview(pageView)
```
```
// 设置样式
let titleStyle = HYTitleStyle()
titleStyle.hasScrollLine = true
```

![type_01](https://github.com/yuxunhuang/HYPageView/blob/master/gif/HYPageView_01.gif?raw=true)

```
// 设置样式
titleStyle.hasScrollLine = true
titleStyle.lineScrollType = .RealTime
```
![type_02](https://github.com/yuxunhuang/HYPageView/blob/master/gif/HYPageView_02.gif?raw=true)

```
// 设置样式
titleStyle.hasGradient = true
// titleStyle.selectedColor = UIColor(red: 1.0, green: 0.5, blue: 0, alpha: 1.0)

```
![type_03](https://github.com/yuxunhuang/HYPageView/blob/master/gif/HYPageView_03.gif?raw=true)

```
// 设置样式
titleStyle.hasGradient = true
titleStyle.selectedFont = UIFont.systemFont(ofSize: 16)
```
![type_04](https://github.com/yuxunhuang/HYPageView/blob/master/gif/HYPageView_04.gif?raw=true)
