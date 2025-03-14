# 卷摆计时器

一个对线上学习者非常有用的计时器小工具，一个计时器用于记录学习时间，另一个计时器用于记录放松时间，可以起到督促学习的效果。

**一些交互上的优点：**

窗口在不使用时会自动缩小减小屏幕占用；拖拽窗口和其任意组件可以移动窗口；双击按钮可以锁定该计时器的显示；在编辑框中输入数字可以更改记录的时间。

**代码优化：**

相较于旧版做了代码重构和美观优化，手动绘制了按钮和窗口渐变隐藏的动画，创建了非常多的可复用的mixin类可以在以后的程序中使用。

### 效果展示

<img src="https://github.com/Bonjir/WorkRelaxTimer/blob/main/.github/(1).jpg" width="50%" height="50%" />

<img src="https://github.com/Bonjir/WorkRelaxTimer/blob/main/.github/(2).jpg" width="50%" height="50%" />

<img src="https://github.com/Bonjir/WorkRelaxTimer/blob/main/.github/(3).jpg" width="50%" height="50%" />

<img src="https://github.com/Bonjir/WorkRelaxTimer/blob/main/.github/(4).jpg" width="50%" height="50%" />

### TODO

- [ ] tooltip
- [ ] 右键列表
- [ ] 每日数据统计

- [x] ~~mini窗口label的显示，哪个启用显示哪个，然后双击锁定~~
- [x] ~~添加CrashHandler模块，解决崩溃与异常退出的处理和恢复~~
- [x] ~~添加Logger模块用于日志记录~~
- [x] ~~添加DataManager模块，自动保存卷摆时间数据~~
- [x] ~~使日志记录模块更加智能~~

### BUG

- [x] ~~拖拽mini窗口后mini消失_dragging没有解除，需要再次在主窗口点击才能解除~~

- [x] ~~miniwindow的layout更新后位置及大小出错问题~~

- [x] ~~edit控件回车失效问题~~

- [x] ~~解决莫名其妙按钮字体变大的问题~~

- [x] ~~解决电脑休眠后字体改变问题~~

- [x] ~~双击和单击分离开~~

- [x] ~~拖拽时将不触发点击事件~~



**Cursor真是太厉害了，我要成为超级TAB王！**

