adb 命令整理

adb  logcat -v time > D:\log.txt    实时输出

adb logcat -v time -s DEMO:e > D:\log.txt  输出日志过滤

adb devices   查看adb设备连接信息

adb shell 进入设备，适合一台设备

adb shell pm list packages -f  输出包名和包路径的关联信息

cd data/data 

rm xxx.apk

adb connect ip

adb disconnect

ls

cd system

cd app

cd ..

adb push  "apkpath"  /system/app

adb remount

adb root

ps |grep xiri



修改 hosts文件命令

cd    /system/etc/hosts      

**echo -e \\n >> /system/etc/hosts**   换行

**echo 192.168.0.246 www.aaa.com >> /system/etc/hosts** 

**echo 125.210.163.39 irs.wasu.cn >> /system/etc/hosts** 

adb shell am start -a android.settings.SETTINGS2  打开设置界面



先adb pull,然后adb push 能修改部分文件。

