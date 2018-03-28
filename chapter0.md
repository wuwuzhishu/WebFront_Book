### 课程的知识点

* HTML：[http://www.w3school.com.cn/html/index.asp](http://www.w3school.com.cn/html/index.asp "w3school-HMTL教程")
* CSS：[http://www.w3school.com.cn/css/index.asp](http://www.w3school.com.cn/css/index.asp "w3school-CSS教程")
* JavaScript和JQuery：[http://www.w3school.com.cn/js/index.asp](http://www.w3school.com.cn/js/index.asp "w3school-JavaScript教程")

### 开发工具

* Visual Studio Code
* Google Chrome

### 浏览器（兼容性）

* Google Chrome
* Firefox
* IE或Edge
* Safri
* Opera

### 内容

* HTML整体结构

```
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	
</body>
</html>
```

在body中添加内容：

```
<html>
    <head>
        <meta charset="UTF-8">
        <title>第一个网页</title>       
    </head>
    <body>
        <p>段落1</p>
        <p>段落1</p>
        <p>段落1</p>
        <p>段落1</p>
        <h1>标题1</h1>
        <h2>标题2</h2>
        <h3>标题3</h3>
        <h6>标题6</h6>
    </body>
</html>
```

* CSS内部样式

```
<html>
    <head>
        <meta charset="utf-8">
        <title>第一个网页</title>
        <!-- 
            css的语法格式：
            选择符{属性:属性值;......}
            选择符有很多种，先介绍基本的三种：
            1.标记（标签）选择符
            2.ID选择符（以#开始）
            3.类选择符（以.开始）            
        -->
        <style type="text/css">
            p{
                color: red;
                font-size: 30px;
                text-align: center;
            }
            #teshu{
                color: blue;
                text-align: right;
            }
            .teshu2{
                color: green;
            }
        </style>       
    </head>
    <body>
        <p>段落1</p>
        <p id="teshu">段落1</p>
        <p class="teshu2">段落1</p>
        <p>段落1</p>
        <h1>标题1</h1>
        <h2>标题2</h2>
        <h3>标题3</h3>
        <h6>标题6</h6>
    </body>
</html>
```



