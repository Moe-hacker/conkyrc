魔改自gitee@auroot
原项目地址：https://gitee.com/auroot/conkyrc
### 截图：
![](https://github.com/Moe-hacker/conkyrc/raw/main/screenshot.jpg)
### 安装：
arch系用户使用aur助手安装conky-lua  
debian系用户安装conky-all  
其他系统自己想办法安装conky  
然后：
```
git clone https://github.com/Moe-hacker/conkyrc
cd conkyrc
cp conkyrc ~/.conkyrc
```
如果你的cpu有4个核心：
```
cp 4cpus/clock.lua ~/.clock.lua
```
如果你的cpu有8个核心：
```
cp 8cpus/clock.lua ~/.clock.lua
```
如果你的cpu有6个核心：  
自己写lua文件去吧，我又不会lua，原项目又没有6核心的。。。
