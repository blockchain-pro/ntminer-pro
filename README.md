
# 以太矿工福音！

**增加针对三大主要矿池vpn+ssl加密的支持：**

    币印： 	poolin1.xxminer.com:8598
    
    鱼池： 	f2pool1.xxminer.com:8689
    
    E池：  	etherminer1.xxminer.com:8789

**增加备用节点：**

    币印：	poolin2.xxminer.com:8599    
	
    鱼池：	f2pool2.xxminercom:8699    
	
    E池： 	etherminer2.xxminer.com:8799
    


1. 休闲矿工xxminer致力于为国内用户提供快速稳定的中转矿池，前后端加密连接，v2ray+ssl 超强加密，超低延迟，本软件为自家矿场使用的中转矿池，现开放给社群使用，抽水0.1%作为日常开发维护。

1. 加密挖矿地址：

>     币印：stratum+ssl://poolin1.xxminer.com:8598
>     鱼池：stratum+ssl://f2pool1.xxminer.com:8689
>     E池：  stratum+ssl://etherminer1.xxminer.com:8789

>     eg:
>     带v2ray代理连接方式：
>     nbminer -a ethash -o stratum+ssl://poolin1.xxminer.com:8598 -u 0x877EE89a5682Dc17353128E81FAA0265481f4133.default –proxy=127.0.0.1:12808 -log –proxy=127.0.0.1:12808 为本地v2ray socket5 代理。
>     
>     不带v2ray代理连接方式：
>     nbminer -a ethash -o stratum+ssl://poolin1.xxminer.com:8598 -u 0x877EE89a5682Dc17353128E81FAA0265481f4133.default -log

3. 下载开源矿工 for 币印ssl加密矿池：
    > https://github.com/blockchain-pro/ntminer/releases/download/v1.5/Ntminer-for-vpn-ssl-v1.5.zip
    > 
    > 解压后填入挖矿账户，直接开挖，使用方法同原开源矿工
    > 
    > 如果有v2ray代理，勾选打开代理，启动v2ray，在高> 级参数栏上填入v2ray socket代理地址：   
    > -proxy=127.0.0.1:12808

    > 现在默认配置了免费节点试用，用户可以根据自己需要搭建或者购买专用vpn服务。

![image](https://github.com/blockchain-pro/ntminer/blob/dev-for-compile/docs/image1.png)

4. Hive OS 加密矿池连接飞行表配置：
> pool config 中手动添加矿池地址：
币印：poolin1.xxminer.com:8598
鱼池：f2pool1.xxminer.com:8689
E池： etherminer1.xxminer.com:8789


> Miner config中添加NBminer并修改Pool url 为stratum+ssl://%URL%

> stratum+ssl 的意思是采用ssl加密协议连接



    
![image](https://github.com/blockchain-pro/ntminer/blob/dev-for-compile/docs/hiveos-config.png)


# XxMiner客服中心:
    
电报: https://t.me/xxminercom


# 授权协议
The LGPL license。

# 友情链接
[鱼池](https://www.f2pool.com/)&nbsp;&nbsp;&nbsp;&nbsp;[BMiner](https://www.bminer.me/)&nbsp;&nbsp;&nbsp;&nbsp;[NBMiner](https://nbminer.com/)&nbsp;&nbsp;&nbsp;&nbsp;[挖币网](http://www.wabi.com/)