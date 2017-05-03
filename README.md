# LXBlock_Demo
How to use Block?

## 我的博客地址：http://www.jianshu.com/p/02ba71b05ac1

## 一、忘记block格式

快速使用：<br>
![image](http://upload-images.jianshu.io/upload_images/1859399-1691b285b59a116b.png?imageMogr2/auto-orient/strip%7CimageView2/2)<br>
![image](http://upload-images.jianshu.io/upload_images/1859399-dace14ccd574d3e4.png?imageMogr2/auto-orient/strip%7CimageView2/2)<br>

## 二、block简介<br>
返回值类型(^block变量名)(形参列表) = ^(形参列表) {<br>
};<br>
调用Block保存的代码<br>
block变量名(实参);<br>

默认情况下,Block内部不能修改外面的局部变量<br>
Block内部可以修改使用__block修饰的局部变量<br>

Block的模式<br>
1.无参数无返回值的Block<br>
2.有参数无返回值的Block<br>
3.有参数有返回值的Block<br>
