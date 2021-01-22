# sharingeye_使用文档
sharingeye是一款适用于企业外部威胁情报采集、资产监控扫描的系统，通过搜索功能可清晰的了解外部网络资产分布情况，并且可指定漏洞插件对搜索结果进行快速资产服务指纹检测。

本站只做初步探测，无攻击性行为。请使用者遵守[《中华人民共和国网络安全法》](http://www.npc.gov.cn/npc/xinwen/2016-11/07/content_2001605.htm)，勿将用于非授权的测试，本站不负任何连带法律责任。

## 一、注册阶段
1.1 用户名：邮箱（ **仅接受企业/公司的邮箱，后台将会审核**

1.2 密码：不少于6位

1.3 验证码

目前已经支持了对部分暗网的监控，github敏感数据泄漏的监控。

## 特点
通过模拟黑客的渗透的思路来监控各个公司的网络威胁和网络方面的漏洞，主要包括以下功能：


### 一、泄漏威胁(doing)

1.1 代码泄漏

    1.1.1 在GitHub代码源平台上，基于相关关键字匹配和目标站点员工信息的追溯泄漏威胁(已实现)。
    
    1.1.2 在gitee代码源平台上，基于相关关键字匹配和目标站点员工信息的追溯泄漏威胁(实现中)。


1.2 数据泄漏(暗网监控)：
    
    实时监控暗网，预警公司员工或用户信息数据泄漏，以应对合规与舆论公关。
    
    1.2.1 暗网中文网(已实现)
    
    1.2.2 阿里baba(实现中)
    
    1.2.3 茶马古道(实现中)
    
    1.2.4 楼兰(已实现)
    ...

### 二、 漏洞情报(实现中)

2.1 漏洞公开情报
    
    2.1.1 (cert360)[https://cert.360.cn/daily?date=]
    
    2.1.2 cnnvd
    
    2.1.3 cnvd
    
    2.1.4 cve
    
    2.1.5 exploitdb
    
    2.1.6 xz
     
    2.1.7 exploitalert
 
    2.1.8 xuanwu
    ...


### 二、资产威胁：

2.1 资产收集

    2.1.1 域名收集。包括子域名搜集(来源为搜索引擎、github、开放API等)、子域名爆破等…（已实现）
    
    2.1.2 端口扫描与中间件指纹识别（已实现）
    
    2.1.3 网站web应用指纹识别（已实现）
    
2.2 漏洞扫描
    
    2.2.1 扫描收集到的指纹中的通用漏洞(实现中)

2.3 定制化漏洞扫描

    2.3.1 扫描web服务和接口（SQLi、XSS、RCE等）中的常见漏洞。(未实现)
    
    2.3.2 基于定制的dicts，对需要认证和后台登录页面形式的中间件、web应用程序进行自动暴力破解。(未实现)
    
    2.3.3 扫描web服务中的敏感文件和文件夹具有高精度和兼容性。(未实现)
    
    2.3.4 根据前一阶段收集的公共信息和其他泄漏数据库生成定制的用户和密码dict。(未实现)
    
    2.3.5 IP地址定位和确定属于目标的C类网段。(未实现)
        

### 四、业务情报

4.1 合规监控

    4.1.1 微信(实现中)

4.2 羊毛党舆情
    
    4.2.1 zuanke8

    ... 

### 五、功能反馈
    
    在sharingeye-docs中直接提供issue即可










