# DoubanFM 客户端
使用Qt4编写的DoubanFM客户端

## 依赖 Dependencies
* libqt4-network libqt4-gui libqt4-core
* libphonon, libphonon-dev, phonon, phonon-backend-(gstreamer|vlc)
* libqjson, libqjson-dev
* gstreamer0.10-fluendo-mp3

## 截图 Screenshot

![截图](https://gitcafe.com/zonyitoo/doubanfm-qt/raw/master/screenshot.png)

## 安装方法 Install Instructions

在Ubuntu 12.10 x86\_64上测试通过

```bash
lrelease lang/*.ts ## 生成*.qm文件
qmake doubanfm-qt.pro
make
```

得到`doubanfm-qt`后直接运行即可

或运行`install.sh`脚本来安装到系统中（For Linux Only），安装好后在桌面系中的的启动器中找到`QDoubanFM`运行即可

## 快捷键 Shortcuts
`Ctrl` + `W` 退出

`Space` 暂停

`Right Arrow` 下一首

`Up Arrow` 喜欢这首歌

`Down Arrow` 扔掉！

## TODO
* <del>基本播放功能</del>
* <del>频道选择</del>
* <del>用户登录</del>
* <del>快捷键</del>
* <del>动画</del>
* <del>i18n支持</del>
* Linux的播放提示 + DBus
* 后台播放 + 托盘提示 (Ubuntu下是Indicator)
* 歌词

## BUGS
* <del>在长时间暂停后重启播放会崩溃</del>
* 在网络不好时卡住会崩溃
* <del>动画有Bug，若打开了频道界面然后鼠标离开，则会让控制面板滑动位置出错</del>

## LICENSE
本项目基于MIT协议发布

MIT: [http://rem.mit-license.org](http://rem.mit-license.org)
