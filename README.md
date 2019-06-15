# simple3dMapDemo
一个简单的动态3d地图demo，可以拿来做大屏展示。


1.软件定位，软件的基本功能

    主要用于大屏展示，也可以作为炫酷的界面，只要你在上面加加加
   
    效果图：
    ![Image text](https://raw.githubusercontent.com/dyx9541/simple3dMapDemo/master/public/images/demo1.png)
    
    图片太大github不给显示，所以模糊了
![Image text](https://raw.githubusercontent.com/dyx9541/simple3dMapDemo/master/public/images/demo.gif)

   
2.运行代码的方法：安装环境，启动命令等

  1）概述
  
    框架：mapbox gl+node.js
    运行环境：node.js

    gis框架是mapbox gl，找了半天，就这个框架支持2.5d地图的（当然后来发现高德也可以，但是没有这么炫的背景地图,因此采用mapbox）

  2）如何启动呢？
  
    s0 首先，
       a.你要去mapbox 上注册一个账号，获得免费的token;
       b.电脑有node.js

    s1 装依赖包 在package.json的目录打开 命令行窗口，输入cnpm install

    s2 装完了，右击下图这个绿色的小三角运行项目
![Image text](https://raw.githubusercontent.com/dyx9541/simple3dMapDemo/master/public/images/QQ%E6%88%AA%E5%9B%BE20190615134031.png)

    s3 在浏览器输入 http://localhost:6111/,就能看到像截图中的界面了


3.简要的使用说明

    你可以用node.js启动，也可以不用node.js直接打开index.html运行。

4.代码目录结构说明

    标标准准的node.js express app 框架,啥都没改，就放了个index.html

5.常见问题说明

    有问题请留言，页面中的图片是随便找的，侵删。
