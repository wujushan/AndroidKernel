# **深入理解Android内核设计思想**

# 18 SystemUI
## System Bars
### Status Bar
-  状态通知栏，会一直存在（除非应用程序主动将其隐藏掉）

 **代码**
- Service部分，路径：frameworks/base/services/java/com/android/server
- 应用部分，路径：framworks/base/packages/SystemUI


### Navigation Bar
- Android 4.0 之后加入的元素
    - 为那些没有物理按键的设备提供便利
    - 提供Home、Back、Recents和Menu键

### Combined Bar
- 专门为Tablet设计的一种系统栏形式
### Notifications

**特性**
  - 通知信息格式可定制
  - 支持更多手势操作
  - 支持更多常用功能

### 其他
- 最近运行的应用程序
- ScreenShot截屏
- 壁纸
- 等等
