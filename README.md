Android开发、调试工具索引
===============

###开发文档
1. eoe 开发百科: http://wiki.eoeandroid.com/%E9%A6%96%E9%A1%B5

###开发工具
####数据统计
1. umeng
2. flurry
3. gfan

####反编译工具
1. apktool
2. droidbox
3. [androguard](https://code.google.com/p/androguard/)

####测试，质量工具
[Quality-Tools-for-Android] (https://github.com/stephanenicolas/Quality-Tools-for-Android)

##adb
ADB server didn't ACK
1. reboot
2. http://stackoverflow.com/questions/26217055/adb-server-didnt-ack

###dumpsys
**IMEI**
adb shell dumpsys iphoneinfo:  IMEI号以及网络制式

**dump service**
com.juude.yunbademos/com.juude.yunbademos.StatsService

adb shell dumpsys activity top : 当前activity的hierarchy

###x2ools
##调试工具
**EventLogTags.logtags**
stetho https://github.com/facebook/stetho
##测试工具
**gt**  http://gt.tencent.com/download.html

###AndroidViewClient

###droidScripts

###droidMocks
1. 使用修改adb的方式,建立socket通信
2. 获取activity  forceStop等自动匹配
3. notification start nane = 
4. 反射引擎，可以在基础上写Python脚本

###logcat
pidca.py
显示时间:
* logcat -v http://www.herongyang.com/Android/Debug-adb-logcat-Command-Log-Format-Control.html
* 

###hierarchy3
1. systemserver
2. focusedWindow
3. 通过hash值找对象
4. 通过windowToken 找PhoneWindow。
5. 获取每个window属性

###debug tools to write
1. 读取log
2.  显示当前应用所有的信息
3. profile info

###android性能工具
1. traceview
http://developer.android.com/tools/debugging/debugging-tracing.html

For each node, dmtracedump shows <ref> callname (<inc-ms>, <exc-ms>,<numcalls>), where

<ref> -- Call reference number, as used in trace logs
<inc-ms> -- Inclusive elapsed time (milliseconds spent in method, including all child methods)
<exc-ms> -- Exclusive elapsed time (milliseconds spent in method, not including any child methods)
<numcalls> -- Number of calls
生成图片 ： dmtracedump -h  -g trace.png trace.trace > o.html
2. mat
3. systrace
4. hierarchyviewer

###类似项目
https://github.com/inferjay/AndroidDevTools

