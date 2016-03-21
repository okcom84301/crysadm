#迅雷云监工源代码
***

##用法
进入系统后先升级源，输入命令<br>
`sudo apt-get update` <br>
等一会自动下载，输入命令 <br>
`sudo apt-get install -y git` <br>
如果出现`bash: sudo: command not found`错误，说明没有安装这个程序，直接输入命令<br>
`apt-get install -y sudo git`<br>
用 `cd` 命令进入任意可写权限文件夹，输入命令<br>
`sudo git clone https://github.com/seatom/crysadm.git`<br>
等待下载完成，输入命令<br>
`cd crysadm  && sudo chmod +x setup.sh && ./setup.sh`<br>
此时等待安装，完成后会自动启动云监工。<br>
***
##PS:<br>
***
run.sh是运行脚本，down.sh是停止脚本，setup.sh是安装环境脚本。
***
***
##联系方式<br>
***
EMail:(seatom@qq.com)
***


如有任何疑问及Bug欢迎加入L.k群讨论
@爱转角遇到了谁 大力更新,请尊重作者
为了您的云监工安全,请立马修改config.py[SECRET_KEY] Key！请不要使用默认的
***   
- 端口：4000
- 第一次获得密码方法，端口后加/install

##  2016.03.21 更新

api.py更新日记:
更新用户提现接口	更新MINE信息接口  
新增免费宝箱接口	新增放弃宝箱接口  
新增秘银进攻接口	新增幸运转盘接口  

crysadm_helper.py更新日记:
删除老式矿机变量	    新增自动用户提现函数  
新增自动免费宝箱函数	新增自动秘银进攻函数  
新增自动幸运转盘函数

excavator.py更新日记:
添加设备升级函数	添加设备定位函数  
添加出厂设置函数	添加设备管理函数  
添加单个账号提现	添加单个账号进攻  
添加单个账号转盘	添加所有账号提现  
添加所有账号进攻	添加所以账号转盘  

admin.py更新日记:
添加自动用户提现变量	添加自动开免费宝箱变量  
添加自动秘银进攻变量	添加自动幸运转盘变量  
更改最高迅雷账号上限:100

ueer.py更新日记:
添加自动用户提现变量	添加自动开免费宝箱变量  
添加自动秘银进攻变量	添加自动幸运转盘变量  
更改注册后迅雷账号上限:20

web_common.py更新日记:
更换类型返回信息	删除老式矿机变量  

register.html更新日记:
添加注册成功提示框

excavator.html更新日记:
删除老式矿机信息	删除雇佣矿机信息  
添加秘银数量信息	添加今日产值信息  
添加设备升级按钮	添加设备定位按钮  
添加出厂设置按钮	添加设备管理按钮  
更换设备显示类型	添加设备固件版本显示  
添加设备端口映射显示	添加单个账号进攻按钮  
添加单个账号转盘按钮	添加所有账号进攻按钮  
添加所以账号转盘按钮

profile.html更新日记:
添加自动提醒开关	添加免费宝箱开关  
添加秘银进攻开关	添加幸运转盘开关  

user_management.html更新日记:
添加自动提醒开关	添加免费宝箱开关  
添加秘银进攻开关	添加幸运转盘开关  



***   

##  2016.03.18 更新

***   

感谢@爱转角遇见了谁 的源码，使监工又能用了，而且加了新功能

更新@爱转角遇见了谁 的源码，增加了自动转盘，自动进攻功能

***    
##2016.03.09 更新
***
更新user.py，解决登出其他用户直接到login页面问题
***
##2016.03.08 更新
***
感谢Dream.Fei的源代码  
更新开宝箱功能，说明进入crysadm文件夹看     

更改收水晶时间为6小时，迅雷帐号最大为200
***
##2016.03.04 14:30 更新
***
更新cron.sh脚本，实现每小时重启一次监工，分钟时间是随机一次
***
##2016.03.02 17:00 更新
***
更新README.MD文件
***
##2016.03.02 9:40更新
***
源代码降回提现功能版本<br>
开宝箱版有问题<br>
刷新数据改为15秒更新<br>
***
##2016.03.01 17:00更新
***
升级了开免费宝箱功能<br>
收水晶改为6小时收一次<br>
***
##以前更新
***
此版本增加了自动提现功能<br>
此版本加了环境安装脚本，安装脚本支持ubuntu 14.04，debian 8，kali 2.0，实测可用<br>
***

