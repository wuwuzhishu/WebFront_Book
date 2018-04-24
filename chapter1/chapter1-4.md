本次课程为实验，需要学生参考首页来完成

定价页面HTML代码

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
                            <li>
                                <a href="service.html">服务</a>
                            </li>
                            <li class="active">
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
            <!-- 定价主题部分 -->
            <div id="price_body">
                <div id="content">
                    <div id="price_header">
                        <h1>开启移动互联网时代的批发大门</h1>
                        <span>让营销更高效，让管理更简单，提供客户沟通、商品展示、店内管理、销售及库存所需的一切方式</span>
                    </div>
                    <div id="price_content">
                        <div id="price_box">
                            <div id="price_box_header">
                                <h3>进销存</h3>
                                <span>专为线下实体店铺提供进销存管理</span>
                            </div>
                            <div id="price_box_content">
                                <p class="font_bolder">￥1999 元/年</p>
                                <p>全套进销存工具</p>
                                <p>数据终身存储</p>
                                <p>不限账号个数</p>
                                <p class="font_bold">续费999元/年</p>
                                <button>免费试用版本</button>
                                <span><a href="">或立即购买</a></span>
                            </div>
                        </div>
                        <div id="price_box" class="price_box_mid">
                            <div id="price_box_header">
                                <h3>云商版</h3>
                                <span>为您新开一个店铺</span>
                            </div>
                            <div id="price_box_content">
                                <p class="font_bolder">￥1999 元/年</p>
                                <p>全套进销存工具</p>
                                <p>数据终身存储（阿里云）</p>
                                <p>含一台专用管理设备</p>
                                <p>含一个您的专属网店</p>
                                <p class="font_bold">续费2999元/年</p>
                                <button>免费试用版本</button>
                                <span>
                                    <a href="">或立即购买</a>
                                </span>
                            </div>
                        </div>
                        <div id="price_box">
                            <div id="price_box_header">
                                <h3>月租版</h3>
                                <span>为您提供最低成本的管理接入方式</span>
                            </div>
                            <div id="price_box_content">
                                <p class="font_bolder">￥599 元/年</p>
                                <p>拥有云商版的所有功能</p>
                                <p>按月付费，含一台专用设备</p>
                                <p>随时可退，无使用负担</p>
                                <p class="font_bold">续费2000元/年</p>
                                <button>免费试用版本</button>
                                <span>
                                    <a href="">或立即购买</a>
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- footer部分 -->
            <div id="footer">
                <div id="content">
                    <span>轻松批，让批发更轻松！！！</span>
                    <input type="button" value="免费试用版本">
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

定价页面CSS代码（在同一个CSS文件后面新增）

```
/* 定价页面样式 */
#price_body{
    background-color: #6C6B6B;
}
#price_header{
    text-align: center;
    color: #ffffff;
    padding: 50px 0;
}
#price_header h1{
    font-weight: 100;
    margin-bottom: 20px;
}
#price_header span{
    font-size: 14px;
}
#price_content{
    width: 1200px;
    overflow: hidden;
    margin: 0 auto;
}
#price_box{
    float: left;
    width: 300px;
    text-align: center;
    margin: 0 49px;
    border: solid 1px #ffffff;
    margin-top: 39px;
}
#price_box.price_box_mid{
    margin-top: 0px;
}
#price_box_header{
    background-color: #c4c4c4;
    padding: 20px 0;
    color: #ffffff;
}
.price_box_mid #price_box_header{
    background-color: #ef4f19;
}
#price_box_header h3{
    font-size: 24px;
    margin-bottom: 5px;
}
#price_box_header span{
    font-size: 14px;
}
#price_box_content{
    background-color: #ffffff;
    color: #222222;
    padding: 30px;
}
#price_box_content p{
    margin-bottom: 20px;
    color: #333435;
    font-size: 14px;
}
#price_box_content p.font_bolder{
    font-size: 24px;
    font-weight: 900;
}
#price_box_content p.font_bold{
    font-size: 18px;
    font-weight: 900;
}
#price_box_content button{
    display: block;
    width: 200px;
    margin: 0 auto;
    height: 40px;
    color: #ef4f19;
    border: solid 1px #ef4f19;
    border-radius: 10px;
    background-color: transparent;
    font-size: 18px;
    cursor: pointer;
}
.price_box_mid #price_box_content button{
    background-color: #ef4f19;
    color: #ffffff;
}
#price_box_content button:hover{
    background-color: #ef4f19;
    color: #ffffff;
}
.price_box_mid #price_box_content button:hover{
    background-color: transparent;
    color: #ef4f19;
}
#price_box_content span{
    margin: 30px 0;
    display: inline-block;
}
#price_box_content span a{
    color: #ef4f19;
    text-decoration: none;
}

```



