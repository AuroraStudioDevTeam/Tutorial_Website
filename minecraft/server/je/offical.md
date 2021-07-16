# 官服核心

*本服务端适合喜欢游玩纯净服务器的玩家*

*注：请保证您已经配置好了 Java 8环境*

## 介绍

官服核心故称 *Minecraft_Server*，是由Mojang官方发布的Minecraft服务端

## 优缺点

优点: 
1. **更新最快**(当新的正式版本出现，也会上传该版本的服务端核心)
2. **最稳定**(只要你使用正确，根本不可能出现报错，除非手残)

缺点:
1. 不可以添加插件和Mod
2. 只能看到最新版本的服务端，较老一点的需要寻找网络资源

## 教程

[视频教程](https://www.bilibili.com/video/BV14v4y1Z7wX)

1. 点击[此处](https://www.minecraft.net/zh-hans/download/server/)进入Minecraft Server服务端官方下载地址
2. 点击`下载 minecraft_server.x.xx.x.jar 并用以下命令运行：`中的链接下载服务端核心文件
3. 下载完毕后，请务必将其放在一个空文件夹中
4. 在核心文件的同级目录下，新建一个txt文件，输入如下信息
	```
	java -Xms1G -Xmx1G -jar xxx.jar nogui
	pause
	```
	注意，此处`-Xms`后是服务器使用的最小内存

	`-Xmx`后是服务器使用的最大内存

	`xxx.jar`是服务器的核心文件名，请根据您的核心文件名修改

	`nogui`是指关闭图形界面，此处建议关闭

	`pause`是暂停，如果出错，可以暂停找问题

	假如我的服务端名字是`core.jar`，最小内存`1G`，最大内存`2G`，那么应是:

	```
	java -Xms1G -Xmx2G -jar core.jar nogui
	pause
	```
5. 保存为`start.bat`，放在与核心文件相同的目录下
6. 双击`start.bat`，服务器开始运行
7. 此时你会发现如下信息
```
[main/WARN]: Failed to load eula.txt
[main/INFO]: You need to agree to the EULA in order to run the server. Go to eula.txt for more info.
```
8. 找到与核心文件同级目录下的`eula.txt`并打开
9. 将`eula=false`改为`eula=true`并保存退出
10. 再次点击`start.bat`，直到出现如下文字
```
[Server thread/INFO]: Done (13.190s)! For help, type "help"
```
即为开服成功

*完成以上操作后，您就是一名合格的腐竹，但仅停留在开服，您可以通过其他教程更深入的了解 Minecraft服务端*

