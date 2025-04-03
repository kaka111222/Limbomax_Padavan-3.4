

# Padavan
[k2p] 【230228】K2P Padavan 3.4 science+Zerotier 纯净版

23年02月28日更新
由于本人为高校全日制校畜，折腾路由器纯属个人兴趣爱好，平时需要做实验写论文。应评分请求新增了fRPC和OPEN.v.pn，其余没有改变，且没有验证，自用仍然为221122的版本。
-------------------------------------------------------------------------------------------
22年11月22日更新
原码作者更新了zerotier插件和“师夷长技以制夷”插件，所以固件也跟着更新了一下。
为什么不选择4.4版本是因为4.4的l2tp会掉线，不知道为什么，3.4用着很稳定又在感知上没有区别，所以还是选择3.4版本了。
-------------------------------------------------------------------------------------------

自己因为是在高校里面，需要L2TP拨号上网（padavan这方面很方便），并且只需要用到科学和Zerotier两个插件，但是奈何K2P只有16MB的ROM，找了一大圈也没找到适合的固件。后来索性自己编译了一个版本，如果恰好和我一样的需求就拿去用吧，就只有科学和zerotier两个插件。
自用科学和Zerotier都用着正常。

感谢https://github.com/zcmhi/Padavan和https://github.com/chongshengB/Padavan-build两位大佬提供原码和编译平台！



221122:下载链接：https://cloud.189.cn/t/mqimQjqYfy63 (访问码:tq9p)

230228:下载链接：https://cloud.189.cn/t/3AZVNfZN7Fvi (访问码:mqb1)


基于hanwckf,chongshengB以及padavanonly的源码整合而来，支持7603/7615/7915的kvr  
编译方法同其他Padavan源码，主要特点如下：  
1.采用padavanonly源码的5.0.4.0无线驱动，支持kvr  
2.添加了chongshengB源码的所有插件  
3.其他部分等同于hanwckf的源码，有少量优化来自immortalwrt的padavan源码  
4.添加了MSG1500的7615版本config  
  
以下附上他们四位的源码地址供参考  
https://github.com/hanwckf/rt-n56u  
https://github.com/chongshengB/rt-n56u  
https://github.com/padavanonly/rt-n56u  
https://github.com/immortalwrt/padavan
  
最后编译出的固件对7612无线的支持已知是有问题的，包含7612的机型比如B70是无法正常工作的  
已测试的机型为MSG1500-7615，JCG-Q20，CR660x  
  
固件默认wifi名称
 - 2.4G：机器名_mac地址最后四位，如K2P_9981
 - 5G：机器名_5G_mac地址最后四位，如K2P_5G_9981

wifi密码
 - 1234567890

管理地址
 - 192.168.2.1

管理账号密码
 - admin
 - admin

**最近的更新代码都来自于hanwckf和MelsReallyBa大佬的4.4内核代码**
- https://github.com/hanwckf/padavan-4.4
- https://github.com/MeIsReallyBa/padavan-4.4
