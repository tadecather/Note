## Java 邮件发送

邮件在我们日常生活中的应用其实并没有很多的作用，但是在一些需要留痕的场合中，邮件的公信度可以说是其他任务任何通讯社交软件所不能比拟的。

在各种各样的系统中，都存在发送邮件的需求。用户注册时，绑定邮箱，以提供后续更改密码，修改重要用户信息等验证功能。重要通知时，发送邮件给对方，存在邮件，留痕，谁也别想甩锅给我。

### 一、邮件发送原理

邮件发送基于邮件发信服务器和邮件收信服务器。直接使用邮箱提供商所提供的工具时，一般可直接收取或发送邮件。当使用第三方工具去收取或者发送邮件时，就需要在邮箱设置中开通 smtp 和 pop3 服务。

下图来自 谢希仁 《计算机网络》

![邮件收发原理](.\image\邮件收发原理.png)

例如使用 foxmail 发送163 邮箱时，需要如下配置。

![image-20200702171710660](.\image\foxmail邮件发送.png)

如上图所示，我们需要四个关键要素：**账号、密码、发件服务器地址、发件服务器端口**。

### 二、邮件发送JAVA基础版

java 原生并不支持

### 三、邮件发送 hutool 工具包封装

### 四、邮件发送 Spring 封装

### 五、邮件发送 Spring boot  封装

### 六 、总结

