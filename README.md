## 如何使用terraform
* 第一次下载repo之后 - terraform init
* terraform plan
* terraform run

## 如何使用gitcrypt
* 确保安装gpg
* 确保安装git-crypt
* 查看有多少key
  * gpg --list-key
	* 会拿到userid: 541630D594D4C9A224676A4BC23F6C688AC5C147
* 初始化
	* git-crypt init
* 添加用户
	* git-crypt add-gpg-user 541630D594D4C9A224676A4BC23F6C688AC5C147
* 第一次下载repo之后，需要运行的命令
	* git-crypt unlock