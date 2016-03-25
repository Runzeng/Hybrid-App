#购物商城项目
用Ionic+Node+Mongodb做的一个购物商城项目(前端部分)

##环境：
1. 自己安装Ionic和android环境
2. ionic platform add android
3. npm install
4. bower install

##ng-cordova插件：
1. cordova plugin add https://github.com/EddyVerbruggen/Toast-PhoneGap-Plugin.git
2. cordova plugin add cordova-plugin-camera（调用手机摄像头）

##特殊的js插件放在locallib目录下
1. MUI用bower下载的不是完整版，只有50多kb，而完整版是86kb，如果想用可以手动下载MUI然后引入各种js和css


##数据模型
1. 购物车数量模型  localStorage["cartCount"]       
2. 判断是够第一次启动应用 localStorage["isFirst"]  /js/route.js
3. 头像  localStorage["touxiang"]

##打包apk
  ionic build android
