# 第1次

### 目标

* 完成首页顶部导航菜单

### 知识点

* 列表标记以及列表导航

* 垂直居中（line-height）、水平居中
* 伪类选择符

### 代码

HTML

```
<html>
    <head>
        <title>轻松批</title>
        <meta charset="utf-8">
        <link rel="stylesheet" href="css/style.css">
    </head>
    <body>
        <div id="wrap">
            <div id="top">
                <div id="content">
                    <div id="top_left">
                        <a href="">
                            <img src="img/logo.png" alt="">
                            <span>让批发更轻松</span>
                        </a>
                    </div>
                    <div id="top_mid">
                        <ul>
                            <li><a href="">首页</a></li>
                            <li>
                                <a href="">服务</a>
                            </li>
                            <li>
                                <a href="">定价</a>
                            </li>
                            <li>
                                <a href="">关于</a>
                            </li>
                        </ul>
                    </div>
                    <div id="top_right">
                        <a href=""><img src="img/h24.png" alt=""></a>
                        <span>123456789</span>
                        <button >立即申请</button>
                    </div>
                </div>
            </div>            
        </div>
    </body>
</html>
```

CSS

```
/* *是一个匹配符，匹配所有的选择符 */
*{
    margin: 0px;
}
a{
    text-decoration-line: none;
}
/* ID选择符以#开始 */
#wrap{    
    width: 100%;
    margin: 0 auto;
}
#top{
    width: 100%;
    height: 80px;
    background-color: #000000;
}
#content{
    width: 90%;
    margin: 0 auto;/*居中显示*/
    overflow: hidden;
}
#top_left,#top_mid,#top_right{
    width: 30%;
    float: left;
    overflow: hidden;
}
#top_left img{
    height: 50px;
    float: left;
    padding-top: 15px;   
}
#top_left span{
    height: 80px;
    display: inline-block;
    float: left;
    line-height: 80px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
    color: #bcbcca;
}
#top_mid ul{
    list-style: none;
}
#top_mid ul li{
    float: left;
    width: 25%;
    height: 80px;
    line-height: 80px;/*行高*/
    text-align: center;/*水平居中*/
}
#top_mid a{
    font-size: 16px;
    color: white;
}
/* 伪类选择符 */
#top_mid a:hover{
    color: red;
}
#top_right{
    color:white;
    float: right;
}
#top_right img{
    height: 40px;
    padding-top: 20px;
    float: left;
}
#top_right span{
    height: 80px;
    display: inline-block;
    float: left;
    line-height: 80px;
    margin-left: 20px;
}
#top_right button{
    width: 100px;
    height: 40px;
    margin-top: 20px;
    margin-left: 20px;
    background-color: black;
    color: white;
    border-radius: 10px;    
    cursor: pointer;/*改变鼠标形状，手*/
}
#top_right button:hover{
    background-color: #f74906;
    border-color: #f74906;
}
```

第2次

第3次

# 第4次

### 目标

* 完成完成首页帮助和表单部分

### 知识点

### 代码



