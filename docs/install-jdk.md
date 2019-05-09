# 安装JDK

欲开始Java的开发之旅，你需要首先安装Java的开发环境。一般而言，Java的开发环境指的就是JDK (Java Development Kit)。接下来，我们会详细介绍如何一步一步地安装JDK。

## 下载并安装JDK

首先，请访问[这个链接](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)并选择你的操作系统对应的安装包。

例如，你的操作系统是64位的Windows，那么就选择`Windows x64`，如图所示。

![1](https://www.runoob.com/wp-content/uploads/2013/12/java-download-1.jpg)

下载完成后，一路点击下一步即可。

## 配置环境变量

安装完成后，右击`我的电脑`，点击`属性`，选择`高级系统设置`：

![1](https://www.runoob.com/wp-content/uploads/2013/12/win-java1.png)

选择`高级`选项卡，点击`环境变量`：

![1](https://www.runoob.com/wp-content/uploads/2013/12/java-win2.png)

得到如图所示的画面：
 
![1](https://www.runoob.com/wp-content/uploads/2013/12/java-win3.png)

在`系统变量`栏中设置两个变量`JAVA_HOME`和`Path`，注意：

- **大小写无所谓！** 
- **若已存在则点击`编辑`，不存在则点击`新建`！**

`JAVA_HOME`和`PATH`的值分别是：

### `JAVA_HOME`

指向你的JDK的安装目录，例如`C:\Program Files\Java\jdk1.8.0_211`，如图所示：

![1](https://www.runoob.com/wp-content/uploads/2013/12/java-win4.png)
![1](https://www.runoob.com/wp-content/uploads/2013/12/java-win5.png)

### `Path`

如果`Path`变量已经存在，点击`编辑`，在原先的值之前添加`%JAVA_HOME%\bin;`

如果`Path`变量不存在，点击`新建`，设置值为`%JAVA_HOME%\bin`

#### Windows 7

![1](https://www.runoob.com/wp-content/uploads/2013/12/java-win6.png)

![1](https://www.runoob.com/wp-content/uploads/2013/12/java-win7.png)

#### Windows 10

![1](https://www.runoob.com/wp-content/uploads/2013/12/44A70696-B2E6-4055-B88F-7FC0222DCCA4.png)

 
