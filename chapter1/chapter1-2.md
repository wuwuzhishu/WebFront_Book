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

# 第2次

### 目标

### 知识点

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
            ......
            <div id="header">
                <div id="content">
                    <div id="header_left">
                        <h1>批发，从未如此轻松</h1>
                        <p>重新定义批发，为您连接所有客户
                            <br>拥抱移动互联，助您生意再次腾飞</p>
                        <input type="button" value="申请免费试用">
                    </div>
                    <img src="img/p1.png" alt="" class="float_right">
                </div>
            </div>
            <div id="banner">
                <div id="content">
                    <ul>
                        <li>
                            <div id="banner_box">
                                <img src="img/p2.png" alt="">
                                <h3>掌控店铺</h3>
                                <p>实时数据同步，了解店铺运营情况<br>
                                    所有店铺状态，随时随地一手掌握</p>
                            </div>
                        </li>
                        <li>
                            <div id="banner_box">
                                <img src="img/p3.png" alt="">
                                <h3>掌控店铺</h3>
                                <p>实时数据同步，了解店铺运营情况
                                    <br> 所有店铺状态，随时随地一手掌握
                                </p>
                            </div>
                        </li>
                        <li>
                            <div id="banner_box">
                                <img src="img/p4.png" alt="">
                                <h3>掌控店铺</h3>
                                <p>实时数据同步，了解店铺运营情况
                                    <br> 所有店铺状态，随时随地一手掌握
                                </p>
                            </div>
                        </li>
                        <li>
                            <div id="banner_box">
                                <img src="img/p5.png" alt="">
                                <h3>掌控店铺</h3>
                                <p>实时数据同步，了解店铺运营情况
                                    <br> 所有店铺状态，随时随地一手掌握
                                </p>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>            
        </div>
    </body>
</html>
```

CSS

```
......
#header{
    width: 100%;
    background-color: #5f5b5b;
}
#header_left{
    float: left;
    color: #ffffff;
    margin-top: 100px;
}
#header_left h1{
    font-size: 40px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 100;
    margin-bottom: 20px;
}
#header_left p{
    line-height: 30px;
    margin-bottom: 20px;
}
#header_left input{
    width: 200px;
    height: 50px;
    cursor: pointer;
    background-color: #f73f3f;
    border:solid 1px #f73f3f;
    border-radius: 25px;
    color: white;
    font-size: 20px;
}
#header_left input:hover{
    background-color: transparent;
    color: #f73f3f;

}
/* 类选择符以.开始 */
.float_right{
    float: right;
}
#header img{
    height: 400px;
}
#banner{
    width: 100%;
    background-color: #0e0e0e;
    padding: 50px 0;
}
#banner ul{
    list-style: none;
    margin: 0 -50px;
}
#banner ul li{
    float: left;
    width: 25%;
}
#banner_box{
    text-align: center;
    color: white;
}
#banner_box h3{
    color: #ef4c4c;
    margin-top: 20px;
    margin-bottom: 5px;
}
#banner_box p{
    font-size: 14px;
}
```

# 第3次

# 第4次

### 目标

* 完成完成首页帮助和表单部分

### 知识点

### 代码



