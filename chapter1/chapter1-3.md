# 服务页面说明

本次课程为实验，需要学生参考首页来完成

服务页面HTML代码

```
<html>
    <head>
        <title>轻松批</title>
        <meta charset="utf-8">
        <link rel="stylesheet" href="css/style.css">
    </head>
    <body>
        <!-- 包裹层 -->
        <div id="wrap">
            <!-- 顶部部分 -->
            <div id="top">
                <!-- 内容部分 -->
                <div id="content">
                    <div id="top_left">
                        <a href="">
                            <img src="img/logo.png" alt="">
                            <span>让批发更轻松</span>
                        </a>
                    </div>
                    <div id="top_mid">
                        <ul>
                            <li>
                                <a href="index.html">首页</a>
                            </li>
                            <li class="active">
                                <a href="service.html">服务</a>
                            </li>
                            <li>
                                <a href="price.html">定价</a>
                            </li>
                            <li>
                                <a href="about.html">关于</a>
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
           <!-- 服务页面主题部分 -->
            <div id="service_body">
                <div id="content">
                    <div id="service_top">
                        <h1>四大服务体系<span>解除后顾之忧</span></h1>
                        <p>从使用到理念，从培训到技巧，解决您开店的所有问题！</p>
                    </div>
                    <ul>
                        <li>
                            <div id="service_box">
                                <img src="img/p6.png" alt="">
                                <h3>极致产品</h3>
                                <p>最好的产品就是最好的服务
                                    <br>简单，易用，好用到极致</p>
                            </div>
                        </li>
                        <li>
                            <div id="service_box">
                                <img src="img/p9.png" alt="">
                                <h3>用户沟通群组</h3>
                                <p>最好的产品就是最好的服务
                                    <br>简单，易用，好用到极致</p>
                            </div>
                        </li>
                        <li>
                            <div id="service_box">
                                <img src="img/p8.png" alt="">
                                <h3>全天候服务</h3>
                                <p>最好的产品就是最好的服务
                                    <br>简单，易用，好用到极致</p>
                            </div>
                        </li>
                        <li>
                            <div id="service_box">
                                <img src="img/p7.png" alt="">
                                <h3>功能持续更新</h3>
                                <p>最好的产品就是最好的服务
                                    <br>简单，易用，好用到极致</p>
                            </div>
                        </li>
                    </ul>        
                </div>
            </div>
            <!-- 底部部分 -->
            <div id="bottom">
                <div id="content">
                    <ul>
                        <li>
                            <h3>关于我们</h3>
                            <p>轻松批是广州市晶焰网络科技有限公司专为批发行业开发的成套批发管理工具，我们致力于解决批发行业的各种痛点，并为客户提供更好和更优质的产品。</p>
                        </li>
                        <li>
                            <h3>合作伙伴</h3>
                            <p class="color_green">阿里云--阿里巴巴网络服务平台</p>
                            <p>商米--小米控股商用设备提供商</p>
                        </li>
                        <li>
                            <h3>联系方式</h3>
                            <p>
                                <img src="img/1-email.png" alt="">
                                <span>qsp@baokuant.com</span>
                            </p>                            
                            <p>
                                <img src="img/1-phone.png" alt="">
                                <span>+86 13826027418</span>
                            </p>
                            <p>
                                <img src="img/1-address.png" alt="">
                                <span>广州市越秀区人民南路88号肯德基二楼</span>
                            </p>
                        </li>
                        <li>
                            <h3>帮助与支持</h3>
                            <p>
                                <img src="img/1-list.png" alt="">
                                <span>使用帮助</span>
                            </p>
                            <p>
                                <img src="img/1-phone.png" alt="">
                                <span>+86 13826027418</span>
                            </p>
                            <p>
                                <img src="img/1-address.png" alt="">
                                <span>广州市越秀区人民南路88号肯德基二楼</span>
                            </p> 
                        </li>
                    </ul>
                </div>
            </div>

        </div>
    </body>
</html>
```

服务页面CSS代码（在首页CSS文件后面新增）

```
/* 服务页面样式 */
#service_body{
    width: 100%;
    padding: 30px 0;
}
#service_top{
    text-align: center;
    margin-bottom: 30px;
}
#service_top h1{
    font-weight: 400;
    margin-bottom: 10px;
}
#service_top h1 span{
    margin-left: 20px;
    color: #ef5050;
}
#service_body ul{
    list-style: none;
    width: 100%;
    padding: 0;
}
#service_body li{
    float: left;
    width: 50%;
    margin-bottom: 70px;
}
#service_box{
    text-align: center;
}
#service_box img{
    height: 100px;
}
#service_box h3{
    color: #ef5050;
    margin: 20px 0 10px;
}
#service_body p{
    color: #4b4b4c;
}
```



