# Aurora Tutorial Java配置教程

*有关于 Minecraft的 Java配置教程*

*注：除了难以理解的地方，本教程暂时没有图片*

*注：本教程仅适用于 Windows 操作系统*

**消歧义: 不是关于Java开发(jdk)**

## 如何配置Java环境

*注: 本教程适用于Java 32位下载*

[视频教程](https://www.bilibili.com/video/bv1Ct4y1B7hY)

1. 点击[此处](https://java.com/zh-CN/download/)前往Java中文官网的下载页面
2. 点击`同意并开始免费下载`
3. 下载完`Java 安装程序`后，执行该程序
4. 弹出安装程序窗口后，一直按`下一步`或其近义词，直到按下`完成`
5. 为了检查当前的Java环境是否配置完毕，我们可以打开一个命令提示符（CMD）窗口。

	在Windows Vista/7系统下，点击`开始菜单`，在搜索框中输入`cmd`，回车

	在Windows XP系统下，点击`开始菜单`->`运行`，输入`cmd`并回车。你也可以使用`运行`的快捷键：`Windows+R`

	在Windows 10系统下，按下快捷键`Windows+R`，输入`cmd`，回车进入cmd控制台。或者右键桌面左下角`开始`按钮，点击`命令提示符`进入
6. 输入`java -version`，回车
7. 若出现大概与以下内容相似的，即配置完毕(教程结束)
```
java version "1.8.0_261"
Java(TM) SE Runtime Environment (build 1.8.0_261-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.261-b12, mixed mode)
```
8. 若您得到的是类似如下内容，请看下一步
```
'Java' 不是内部或外部命令，也不是可运行的程序或批处理文件
```
9. 尝试以下步骤，将Java添加到你的系统环境变量中
	1. 右键点击`此电脑`或`我的电脑`
	2. 点击`属性`
	3. 点击`高级系统设置`。
	4. 点击`环境变量`。
	5. 在`系统变量下`，选中`Path`变量。
	6. 点击`编辑`
	
		在Windows XP/Vista/7系统下，在内容的结尾处加上`;"c:\Program Files\Java\bin"`。如果你在64位系统上使用32位Java，则使用`;"c:\Program Files (x86)\Java\bin"`。确定

		在Windows 10系统下，点击`新建`，输入`%JAVA_HOME%\bin`，回车。再次点击`新建`，输入`%JAVA_HOME%\jre\bin`，回车。确定
	7. 重启电脑。
	8. 再次打开命令提示符输入`java -version`并回车，验证。

*教程结束*