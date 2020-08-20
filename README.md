<div align="center">
   <img width="160" src="assets/mirai.png" alt="logo"></br>


   <img width="95" src="assets/mirai.svg" alt="title">

----
Mirai 是一个在全平台下运行，提供 QQ Android 和 TIM PC 协议支持的高效率机器人库

这个项目的名字来源于
     <p><a href = "http://www.kyotoanimation.co.jp/">京都动画</a>作品<a href = "https://zh.moegirl.org/zh-hans/%E5%A2%83%E7%95%8C%E7%9A%84%E5%BD%BC%E6%96%B9">《境界的彼方》</a>的<a href = "https://zh.moegirl.org/zh-hans/%E6%A0%97%E5%B1%B1%E6%9C%AA%E6%9D%A5">栗山未来(Kuriyama <b>Mirai</b>)</a></p>
     <p><a href = "https://www.crypton.co.jp/">CRYPTON</a>以<a href = "https://www.crypton.co.jp/miku_eng">初音未来</a>为代表的创作与活动<a href = "https://magicalmirai.com/2019/index_en.html">(Magical <b>Mirai</b>)</a></p>
图标以及形象由画师<a href = "">DazeCake</a>绘制
</div>

# 🎃MiraiOK 
取名于Mirai OneKey，前身为MiraiGo。  
一个用于启动wrapper的wrapper ~~(套娃狂魔)~~ 但是使其易用许多
##### ~~sa~一起进入mirai的世界吧~ ~~
![Compile MiraiOK](https://github.com/LXY1226/miraiOK/workflows/Compile%20MiraiOK/badge.svg)


### ✨如果需要使用mirai-native 请下载windows-386版本

使用方式：下载&运行  
linux: wget -c 下面表格的链接 && chmod +x miraiOK* && ./miraiOK*  
↑被逼的 应该有更好的方法
Arch: ```yaourt -S miraiok-bin``` 或 ```yay mirok-bin```

## 已经能做到
- [x] 从几个比较~~稳定~~的镜像源下载
- [x] 自动更新mirai运行需要的东西
- [x] 一球人需要的自动登录
- [x] Actions自动推送到oss便于下载
- [x] MiraiOK自升级 

#### 下载地址
|系统|备注|
|-------------|---|
|[Windows-386](http://t.imlxy.net:64724/mirai/MiraiOK/miraiOK_windows_386.exe)|mirai-native用|
|[Windows-amd64](http://t.imlxy.net:64724/mirai/MiraiOK/miraiOK_windows_amd64.exe)|不用native的话|
|[Linux-amd64](http://t.imlxy.net:64724/mirai/MiraiOK/miraiOK_linux_amd64)|服务器用品|
|[Linux-arm64](http://t.imlxy.net:64724/mirai/MiraiOK/miraiOK_linux_arm64)|64位arm派用品|
|[Linux-arm](http://t.imlxy.net:64724/mirai/MiraiOK/miraiOK_linux_arm)|arm派用品|
|[Darwin-amd64](http://t.imlxy.net:64724/mirai/MiraiOK/miraiOK_darwin_amd64)|MacOS用品 已测试，感谢fjh1997大佬|

> ***上面的链接已失效，我仅保留了两个文件，Linux-amd64与Linux-arm64，请去Download文件夹自行寻找***  


### Tips
创建`.DEBUG`文件来开启DEBUG输出 ~~(虽然没什么东西)~~  
修改`config.txt`来使用Mirai自带的自动登录  


## TODO 
- [ ] 校验文件  
- [ ] WEB前端 
- [ ] 插件中心  

