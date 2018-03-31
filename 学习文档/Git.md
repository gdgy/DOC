## git 配置 ##

### ssh生成 ###
	ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

### 密码 ###
	git config –global credential.helper store

### 用户名 邮箱 ###
	$ git config user.name 'github用户名'  
	$ git config user.email '邮箱'  