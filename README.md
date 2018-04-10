# ROLL Command

## firmware upgrade有两种方式
* 通过tftp：
> upload.cgi -tftp serverIP ImageName
* 通过http：
> upload.cgi -wget url

## 认证成功后，告知AP放行哪行sta
* 通过如下命令：
> firewall.cgi accept mac_list

***
**各参数定义如下：**
*serverip:NPQ serverIP*

*ImangeName:NPQ server上image的名字*

*url:要下载的firmware的url*

*mac_list:放行的mac地址，可以有多个，以";"分割*
