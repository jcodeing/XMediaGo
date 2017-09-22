![logo](https://raw.githubusercontent.com/jcodeing/XMediaGo/master/readme/kmedia_logo.png)
----
![logo](https://raw.githubusercontent.com/jcodeing/XMediaGo/master/readme/demo_sr_1.gif)
![logo](https://raw.githubusercontent.com/jcodeing/XMediaGo/master/readme/demo_ui.gif)
![logo](https://raw.githubusercontent.com/jcodeing/XMediaGo/master/readme/demo_sr_2.gif)
----
KMedia是一个Android应用级媒体框架,它可以助你快速搭建媒体应用.
内部重新定义Android MediaPlayer API并对其封装, 简化和扩展一些原生API不支持的功能.
其中涵盖了, PlayAB ABLoop PositionUnitLoop PlaybackSpeed MediaQueue PlayerService/Binding
AudioNotifier MediaButtonReceiver AudioFocusManage MultipleMediaEngine... 等功能的快速实现.
以及, 对视频播放实现方面的封装. 其中将视频视图主要分为:SurfaceView ControlGroupView ControlLayerView三个部分.
能够快速并灵活的实现目前视频相关应用的大部分功能, 包括 视频浮窗/拖动调整位置大小 竖屏/全屏自动切换 全屏锁定 手势调整亮度/音量/进度
字幕/切换/拖动 视频段落/间隔复读 变速 视频续集/列表/循环播放 动态切换视频控制层 控制层分离... 等功能的快速实现.