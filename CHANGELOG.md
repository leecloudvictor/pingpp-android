# ChangeLog

### 2.1.19 (2018-10-31)
* 新增：
    新增建行支付渠道

### 2.1.18 (2018-06-29)
* 新增：
    新增招行 app 支付

### 2.1.17 (2018-01-16)
* 更新：  
    更新支付宝 SDK  
    更新微信 SDK  
    更新银联 SDK  
* 新增：  
   pingpp_ui 库


### 2.1.16 (2017-12-14)
* 新增：  
    跨境支付宝APP支付  
    跨境微信APP支付

### 2.1.15 (2017-11-27)
* 更新：
    更新银联 SDK

### 2.1.14 (2017-09-28)
* 修复：  
修复 order 取值问题

### 2.1.13 (2017-09-13)
* 新增：  
添加线下渠道支付
* 更新：  
test 模式下支付状态的判断
* 修复：  
修复壹收款花呗分期入口


### 2.1.12 (2017-08-29)
* 更新：  
更新 Ping++ SDK v2.1.12  
更新 支付宝 SDK (alipaySdk-20170725.jar)  
更新 银联 SDK  
兼容账户系统 1.4  

### 2.1.11 (2017-07-24)
* 更新：
更新 Ping++ SDK v2.1.11

### 2.1.10 (2017-07-10)
* 更新：  
更新支付宝 SDK (alipaySingle-20170510.jar)  
更新微信 SDK v1.1.7  
更新接入文档  
兼容招行一网通混淆加密方式
* 修复：  
修复qpay在被杀死进程时的返回错误结果的问题

### 2.1.9 (2017-03-06)
* 更新支付宝SDK v15.2.8

### 2.1.8 (2017-01-12)
* 修复：
修复京东支付按返回键返回结果状态不正确问题
修复WebView在4.2系统以下检测出漏洞问题
* 更新：
更新壹收款到2.1.2
兼容微信新旧jar包
兼容招行一网通2.0

### 2.1.7
* 修复：
修复微信在Android7.0下的返回结果问题
* 更新：
更新银联支付到 3.3.5
* 新增：
添加账户余额系统(兼容charge与order对象)

### 2.1.6
* 更改：
更新支付宝SDK v15.2.2

### 2.1.5
* 新增：
添加QQ钱包(qpay)
* 更改
更新京东支付到2.0(jdpay_wap2.0)

### 2.1.4
* 新增：
添加招行一网通（cmb_wallet）


### 2.1.3
* 新增：  
添加么么贷（mmdpay_wap）
* 更改：  
更新支付宝到 alipaySdk-20160223.jar  
更新银联支付到 3.3.3  
更新微信支付

### 2.1.2
* 新增：  
添加量化派（qgbc_wap）  
添加分期乐（fqlpay_wap）

### 2.1.1
* 更改：  
统一 SDK 调用接口，使用 Pingpp 类
* 修复：  
在 Android 6.0 以上申请权限的问题

### 2.1.0
* 更改：  
更新壹收款

### 2.0.7
* 更改：  
改为 Library Project 导入方式  
修复不能去除微信 jar 包的问题

### 2.0.6
更换银联支付 SDK

### 2.0.5
更新银联支付到 3.1.0，接入方式改为 jar 方式接入。  
更新支付宝到 alipaySDK-20150818.jar

### 2.0.4
增加京东支付（jdpay_wap）

### 2.0.3
* 修复：  
Java 版本兼容问题

### 2.0.2
* 更改：  
新的测试模式

### 2.0.1
* 更改：  
百付宝 SDK 更新

### 2.0.0
* 更改：  
添加新渠道：百付宝  
callback 添加返回错误信息

### 1.0.5
* 修复：  
微信未登录情况下，点返回，应用无响应，需要再按一次返回才能继续操作

### 1.0.4
* 更改：  
更换了测试环境 URL
