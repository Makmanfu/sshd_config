1. 切换到root用户
	```
	sudo -i
	```
2. 下载安装脚本
	```
	wget --no-check-certificate -O shadowsocks-go.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-go.sh
	```
3. 为脚本添加x权限
	```
	chmod +x shadowsocks-go.sh
	```
4. 运行脚本并定义log文件
	```
	./shadowsocks-go.sh 2>&1 | tee shadowsocks-go.log
	```
	> Congratulations, Shadowsocks-go server install completed!

	>	Your Server IP        :  ****

	>	Your Server Port      :  ****

	>	Your Password         :  ****

	>	Your Encryption Method:  ****
5. 启动
	```
	/etc/init.d/shadowsocks start
	```
