# video_player
基于FFmpeg+SDL2 实现的简易播放器

### 说明
+ 请使用VS2019打开并切换到debug & x86 下编译运行(不出意外f5即可一键启动)。
+ 已实现音视频同步，自我感觉效果不错。(视频通过动态帧率同步音频)。
+ UI部分使用简单的SDL，所以不可改变窗体大小。
+ 控制台第一列是当前视频帧和上一视帧的实际间隔(秒)，第二列是视频时钟和音频时钟(pts)的修正值。

### 图示
![运行截图](http://huahua.qn.xlvfan.com/show.png)

### 吐槽
+ 下视频测试的时候使用了优酷客户端，然后自动转
  码出来的视频后半截pts炸裂了，我以为是我程序
  出现了BUG，调试了好久……。淦。

###### @xMushroom
