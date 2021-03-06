Cdn三种添加ssl证书的方法

一、第一种在站点设置中添加：

点击CDN管理--站点列表--需要添加ssl证书的站点名--站点设置--https设置--打开

![image](https://user-images.githubusercontent.com/90588289/134646039-f651a724-74a1-47cd-a239-efa504373d7d.png)

![image](https://user-images.githubusercontent.com/90588289/134646310-ee249a89-5e3f-43cd-b3bf-c8fd80f75e4f.png)

点打开，加入证书后点提交

![image](https://user-images.githubusercontent.com/90588289/133751344-d555b34b-50b6-4fa5-a63c-f44b7ba3e68a.png)

可以点检测功能检查证书是否有效，打勾说明证书是有效的，打叉说明证书无效

二. 第二种是在域名记录里添加：

点击CDN管理--站点列表--需要添加ssl证书的站点名--记录管理--选择要添加ssl证书的域名--修改--填写好ssl证书和密钥

如下图点击，添加证书后点确定即可

![133751358-61891461-df4a-467a-80e0-526160f901dc](https://user-images.githubusercontent.com/90588289/134646833-90af9524-7232-4f92-b50c-575e0ac3a62c.png)

三. 第三种是用sharkcdn自动获取证书功能：

开启申请ssl证书前域名要做好cname解析记录，或者域名直接解析到了节点的ip也行

如下图点击开启自动申请ssl证书的功能

![image](https://user-images.githubusercontent.com/90588289/133751382-f5222a12-ab59-420f-9eaa-14b4f81a60d6.png)

如下图显示就申请成功了，到期后会自动续期，（注：独立主控用户开通这个功能需联系客服开通）

自动申请证书也有可能失败，失败可先检查下解析是否做好，然后重新申请

![image](https://user-images.githubusercontent.com/90588289/133751396-6df1d446-a0c0-4576-b5d1-99e866a5c390.png)

[SSL管理](zh-cn/SharkCdnDoc/CDN管理/SSL管理/SSL管理.md)

以上就是三种添加证书的方式

备注：无
