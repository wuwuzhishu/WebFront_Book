# 盒子模型

![盒子模型](/assets/盒子模型.png)

参考网址：[https://www.cnblogs.com/smyhvae/p/7256371.html](https://www.cnblogs.com/smyhvae/p/7256371.html)

## CSS选择器

参考网址：[http://www.w3school.com.cn/cssref/css\_selectors.asp](http://www.w3school.com.cn/cssref/css_selectors.asp)

## CSS属性

参考网址：[http://www.w3school.com.cn/cssref/index.asp](http://www.w3school.com.cn/cssref/index.asp)

## 标准文档流

参考网址：[https://blog.csdn.net/diligentkong/article/details/54312829](https://blog.csdn.net/diligentkong/article/details/54312829)

## CSS浮动

参考网址：[http://www.w3school.com.cn/css/css\_positioning\_floating.asp](http://www.w3school.com.cn/css/css_positioning_floating.asp)

* 利用浮动来实现多列布局的方法
* 清除浮动的方法（clear:both或width以及overflow相结合）
* CSS overflow属性

示例代码

``` HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">   
    <title>Document</title>
    <style>
        #box1{
            width: 33%;
            height: 100px;
            background-color: red;
            float: left;/*float浮动*/

        }
         #box2{
            width: 33%;
            height: 100px;
            background-color: green;
            float: left;
        }
         #box3{
            width: 33%;
            height: 100px;
            background-color: blue;
            float: left;;
        }
        #box4{
            width: 600px;
            height: 300px;
            background-color: aqua;
            /* clear:both;清除浮动的一种方式 */
        }
        #box{
            width: 100%;
            overflow: hidden;/*清除浮动的第2种方式，也是比较常用的一种*/
        }
    </style>
</head>
<body>
    <div id="box">
        <div id="box1"></div>
        <div id="box2"></div>
        <div id="box3"></div>
    </div>
    <div id="box4"></div>
</body>
</html>
```
