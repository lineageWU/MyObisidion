一、常用adb命令

1、adb devices：查看已连接的设备

2、adb version：查看adb的版本序列号

3、adb -s <设备名字>：指定某设备做什么（设备名字用1的方法可以查看）

4、adb install <安装包.apk>：安装应用（写清楚apk的完整路径）adb -s <设备名字> install <安装包.apk>：指定设备安装应用

5、adb shell：通过远程shell命令来控制模拟器/设备

6、exit：退出shell远程连接，回到原路径。（Ctrl+d，退出shell，回到默认路径）

7、adb connect：连接

8、adb diaconnect：断开连接

9、adb logcat -v time > 1.log：打印日志

