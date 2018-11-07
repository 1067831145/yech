# 本电子书的介绍

这是我的第一本使用 GitBook 制作的电子书。
###1.放入链接
[百度](http://baidu.com)
```
   语法： [百度](http://baidu.com)
```

###3.放入图片(无效)
![图片](images/b3_gift3.png)


###4.符号
代码块
```
    代码块(三个`)    
    行内代码(两个`)
```


###5.改变文字颜色
<font color = "red">红色文字</font>

```
    <font color="red">红色文字</font>
```


###6.可以在目录下添加地址
```
    * [第一章](http://baidu.com)
```

###7.插件
npm install 想要的插件，或者在json上复制张贴再gitbook install
打赏插件
```
在book.json上添加    
     "plugins": [
        "donate"
    ],
     "pluginsConfig": {
        "donate": {
            "wechat": "https://darrenliuwei.com/images/wechatpay.jpg",
            "alipay": "https://darrenliuwei.com/images/alipay.jpg",
            "title": "",
            "button": "打赏",
            "alipayText": "支付宝打赏",
            "wechatText": "微信打赏"
        }
    }
在gitbook install

```

2.右上角插件跟踪项目  
```   
     "plugins": [
        "github-buttons@2.1.0"
    ]
     "github-buttons": {
            "repo": "darrenliuwei/gitbook",
            "types": [
                "star"
            ],
            "size": "small"
        }
```

3.编辑此页
