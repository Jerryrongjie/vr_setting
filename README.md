# Unity的安装和调试

## 安装 Unity

首先打开，UnitySetup64-5.6.2f1 进行安装。
需要注意的是，文件路径**必须英文**

![安装](https://github.com/Jerryrongjie/vr_setting/blob/master/1.jpg)

## 安装Java 及配置环境

首先，安装最新版的java，记录安装目录。
![java路径](https://github.com/Jerryrongjie/vr_setting/blob/master/java%E8%B7%AF%E5%BE%84.jpg)

设置环境变量：
- 新建用户变量 Java_home 变量值为Java路径
![环境变量1](https://github.com/Jerryrongjie/vr_setting/blob/master/%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F1.jpg)

- 编辑用户变量中的Path，在尾部新建 **%JAVA_HOME%\bin**
![环境变量2](https://github.com/Jerryrongjie/vr_setting/blob/master/%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F2.jpg)

## 测试系统变量是否配置成功

- 打开 **命令提示符** 按Win + R组合键。
- 输入 java，若出现这样的命令提示则配置成功！
![命令提示符](https://github.com/Jerryrongjie/vr_setting/blob/master/3.jpg)

## 安装 安卓软件开发工具包

首先保证 SDK Manager 位于英文路径，然后打开并按提示安装。
记录 SDK 文件路径。

## 配置 Unity

- 打开unity，新建一个项目，打开Edit-Preferences选项
- 点击Browse，找到刚刚复制的android-sdk-windows文件夹所在的路径 
- JDK地址：Java路径
![配置](https://github.com/Jerryrongjie/vr_setting/blob/master/4.jpg)

- 完成之后，新建场景，保存场景，添加到build里面去切换平台为安卓Android平台
- 点击Player settings修改Other Settings 将右侧的ProductName 修改为自己喜欢的，例如：**.sj，修改完成后，点击Build。

![配置](https://github.com/Jerryrongjie/vr_setting/blob/master/5.jpg)

- 选择路径，并保存APK文件。
- 直接将文件传到手机上就可以用了！！

![配置](https://github.com/Jerryrongjie/vr_setting/blob/master/7.jpg)
