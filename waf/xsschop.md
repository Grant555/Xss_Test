### 前言
- - -
[xsschop](https://xsschop.chaitin.cn/) 是长亭XSS语义分析引擎的Demo站，[详细介绍](https://mp.weixin.qq.com/s/32w0eRS4_Ko3ItYRD7rPUg)长亭是唯一一家正式在WAF产品中使用语义分析方法来进行 XSS 检测的，我们可以通过这个Demo站来测试学习xss知识。

#### 简单的尝试
- - -
`<script>alert(1)</script>`   

![1](https://ws1.sinaimg.cn/large/005DAKuvgy1g2ggotblp5j309t060q2t.jpg)

把括号换成反引号，这里科普下在ES6中模板字符串用反引号标识``(`)``，``有人说alert(1)等同于alert`1`，``这两种方式确实都可以弹框，但是当你要`document.cookie`的时候。

用括号的。

![2](https://ws1.sinaimg.cn/large/005DAKuvgy1g2gxihhvjpj3083040glf.jpg)   

用反引号的。

![3](https://ws1.sinaimg.cn/large/005DAKuvgy1g2gxjcbkg9j306o040gle.jpg)